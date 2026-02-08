# day 14 of 90dayschallenge 

# OSI(open system interconnection)
OSI model has 7 layer in it which help us to understand how two system communicates with each other
A-Application layer - this layer is used to assgin the proctol such as http or https this is the seventh layer of osi model
P-Presentation layer - this layer is responsible for encrypting the data and data formating ithis is the sixth layer of osi model
S-Session layer- this layer establish a session between the host and client this the fifth layer of osi model
T-Transport layer - this layer is responsible for transportation and assign the protocol such tcp/udp
Network- this layer is responsible for assign host and the destination ip and segment the data into packets 
Datalink layer- this layer the data which is segmented is converted into elctronics signal.
Physical layer- this layer is responsible for transfering the electronic signal through optical fiber 

# TCP/IP
this is the practical implementation of osi model but it has only four layer 
application, presentation and session layer combines to form one layer application
Transport layer is similar to osi
Internet layer- is similar to network layer
physical layer is combination of datalink layer and physical layer.

- **Identity:**  hostname -I this command is use to display the host ip-175.34.56.202
- **Reachability:** ping google.com this command is use to. check weather the site is responsive or not.
- **Path:** traceroute google.com this command is use to display all the hops( or ips that occured while reaching google.com)
- **Ports:**netstat this command is use to check the port as well as display all active internet connections
- **Name resolution:** nslookup this command is use to display the ip address of the dns eg nslookup google.com

1- Today i learned about how thw data flow between two system
2- What are different networking command that help us debug the networking issue

