
first server code : 

<img width="728" height="405" alt="Screenshot 2026-01-10 at 9 57 14 PM" src="https://github.com/user-attachments/assets/41efd897-3048-40d1-a4b3-41a8b33710f4" />

created a socket called "s" for listening the connection request only.

listening - just making the connection . listening port does not participate in the furthur communication.

bind - used to for establising the location of the server that we are using that means we are maintaing the server in the address and the server is taking input in the given port ( that are localhost is the address(127.0.0.1) and port is 8080).

listen - it is the capacity of the number of clients that it can hold in the situation of traffic. if the server is busy in that time then it can hold maximum of 3 clients(in this case).

accept - this is an imp object that is used to accept the every request that the server gets.
the accept will give two outputs 
1) creates new socket for the communication with the client ( as said before the first socket(s) is used only for making the connection ) here in our case we have named the new socket as "c"

2) address of the client that is the ip address and the port of the client.

now the communication or any other requestes from the connected client will be happening in the new socket that is 'c' in this case.

the objects send recieve should be used as per the meaning like 
    c.send(bytes('welcome to ananth server','utf-8'))
in this line we are writing the c.send that means we need to specify which socket is sending the following message and also same as recive like which socket need to recieve the message. and store that in a varible later print that.

<img width="728" height="61" alt="Screenshot 2026-01-10 at 11 06 30 PM" src="https://github.com/user-attachments/assets/d27b498a-4a6c-481c-975a-10f481cc7850" />

client server : 

<img width="699" height="280" alt="Screenshot 2026-01-10 at 11 06 51 PM" src="https://github.com/user-attachments/assets/1dab658e-ef7b-460e-8afa-26ce699d59ad" />



