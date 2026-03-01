# day 23 of 90daysof Devops

# Task 1

1. What is a branch in Git?
A branch in git is different area where we can work like production, dev , test and other working on one branch can make thing difficult so we use the concept of branches. 
2. Why do we use branches instead of committing everything to `main`?
we use branches to organise our data in such way that it does not affects the prod branch or the main branch and we first make changes in our dev branch and then test it if everything goes well then we merge our changes to main branch
3. What is `HEAD` in Git?
head is the reference pointer that points to the branch where we are currently working
4. What happens to your files when you switch branches?
the data of that file remain the branch that that we are workign it does not show in the branch in which we switch.

# task 2
In your `devops-git-practice` repo, perform the following:
1. List all branches in your repo
to list all branch in our repo we use git branch command

2. Create a new branch called `feature-1`
To create a new branch with name feature1 i have used git branch feature1 command and created a new branch.
3. Switch to `feature-1`
I have switch to new branch using git checkout feature1 command 
4. Create a new branch and switch to it in a single command — call it `feature-2`
I have created and swutched to that ranch using git checkout -b feature 2 command 
5. Try using `git switch` to move between branches — how is it different from `git checkout`?
git switch help us to siwtch between different branches but git checkout help us to create and switch the branch at the same time
6. Make a commit on `feature-1` that does **not** exist on `main`
I have shared the screenshot showing that changes made to the feature1 branch does not refelect i main branch
7. Switch back to `main` — verify that the commit from `feature-1` is not there
git switch main
8. Delete a branch you no longer need
9. Add all branching commands to your `git-commands.md`

# Task 3
1. Create a **new repository** on GitHub (do NOT initialize it with a README)
I have created a new branch and clone it to my local using git clone command 
2. Connect your local `devops-git-practice` repo to the GitHub remote
git clone was the command use to connect the repo to local
3. Push your `main` branch to GitHub
git remote set-url origin https://siddhantsingh08:"PAT"@github.com/siddhantsingh08/Github-Pract
git push origin main
4. Push `feature-1` branch to GitHub
git push origin feature1
5. Verify both branches are visible on GitHub
verifed that both the branches are availiable on the git hub 
6. Answer in your notes: What is the difference between `origin` and `upstream`?


---

# Task 4: Pull from GitHub
1. Make a change to a file **directly on GitHub** (use the GitHub editor)
Done
2. Pull that change to your local repo
git 
3. Answer in your notes: What is the difference between `git fetch` and `git pull`?
git fetch is use to fetch the change from remote to local without merging 
git pull is use to fecth the changesb from the remote and merge it to local.
---

# Task 5: Clone vs Fork
1. **Clone** any public repository from GitHub to your local machine
Git clone is uee to clone the repo to the local to the local system
2. **Fork** the same repository on GitHub, then clone your fork
git fork is use to fork the git repo to git repo  directly
3. Answer in your notes:
   - What is the difference between clone and fork?
   - When would you clone vs fork?
   when i want to clone to it local i will use git clone and i will be git fork is use to clone the git repo to git account directly
   - After forking, how do you keep your fork in sync with the original repo?
   git upstream command 

![](2026-03-01-11-41-13.png)

![](2026-03-01-11-59-28.png)

![](2026-03-01-11-59-50.png)