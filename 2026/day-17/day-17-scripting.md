# Day 17 of 90dayschallenge

# Task 1: For Loop
Create for_loop.sh that:
Loops through a list of 5 fruits and prints each one
- I have created a simple script that print all the fruits given in the loop.
"""
#!/bin/bash
for i in apple, banana, grapes, blueberry, strawberry
do
        echo "Fruits = $i"
done
"""
<img width="1240" height="172" alt="image" src="https://github.com/user-attachments/assets/ccecead1-c2c0-4de7-a6a5-37e0493f14cb" />

Create count.sh that:
Prints numbers 1 to 10 using a for loop
- I have created a script that will print all the number in range after taking the input from the user
#!/bin/bash
read -p "Enter the number for counting=" num
for(( i=0; i<=$num; i++))
do
        echo "$i"
done

echo "The series End here Thank You!"
<img width="956" height="293" alt="image" src="https://github.com/user-attachments/assets/b9f089a2-2376-4e00-83bf-9aeb50d5ee27" />

#!/bin/bash
#
read -p "Kindly provide the range of countdown=" Num

# Task 2: While Loop
Create countdown.sh that:
Takes a number from the user
Counts down to 0 using a while loop
Prints "Done!" at the end

while [ $Num -ge 0 ]
do
        echo "buckle up here we go! $Num"
        ((Num--))
done
echo "Let the show begin"
<img width="780" height="379" alt="image" src="https://github.com/user-attachments/assets/ae96f600-967f-4ac6-b154-26b1de380398" />
<img width="1120" height="305" alt="image" src="https://github.com/user-attachments/assets/e94e33e0-d840-48fa-933d-309900d671d8" />

- Task 3: Command-Line Arguments
Create greet.sh that:

Accepts a name as $1
Prints Hello, <name>!
If no argument is passed, prints "Usage: ./greet.sh "

"""
#!/bin/bash

if [ $# -eq 0 ];then
        echo "No arguments passed"
        echo "Usage Hello My name is <Name>"
        exit 1
else
echo "Hello Buddy My Name is $1"
fi
"""

<img width="1282" height="189" alt="image" src="https://github.com/user-attachments/assets/4f5a618e-e120-4c4f-8a5e-8847269225ab" />
<img width="947" height="324" alt="image" src="https://github.com/user-attachments/assets/ffb48fa7-803f-450e-9181-c21aa1b0f989" />

Create args_demo.sh that:

Prints total number of arguments ($#)
Prints all arguments ($@)
Prints the script name ($0)
<img width="1452" height="198" alt="image" src="https://github.com/user-attachments/assets/6af89489-21b5-4601-a656-9e34c3e242fd" />
<img width="827" height="260" alt="image" src="https://github.com/user-attachments/assets/3031a406-0c9e-48f4-82ad-3a2b32090373" />



