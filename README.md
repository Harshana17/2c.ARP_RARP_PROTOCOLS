# 2c.SIMULATING ARP /RARP PROTOCOLS
## AIM
To write a python program for simulating ARP protocols using TCP.
## ALGORITHM:
## Client:
1. Start the program
2. Using socket connection is established between client and server.
3. Get the IP address to be converted into MAC address.
4. Send this IP address to server.
5. Server returns the MAC address to client.
## Server:
1. Start the program
2. Accept the socket which is created by the client.
3. Server maintains the table in which IP and corresponding MAC addresses are
stored.
4. Read the IP address which is send by the client.
5. Map the IP address with its MAC address and return the MAC address to client.
P
## PROGRAM - ARP

![image](https://github.com/user-attachments/assets/12a3f5fa-d3b7-4c26-8865-0284aef0cb71)

## OUPUT - ARP

![image](https://github.com/user-attachments/assets/eb7c6163-68ff-4d29-86ed-b5ac77ed9871)


## PROGRAM - RARP

![image](https://github.com/user-attachments/assets/28d88830-52ae-4b9f-b30b-b5afb61d4031)

## OUPUT -RARP

![image](https://github.com/user-attachments/assets/1825cb89-71f3-4d16-af11-3ee1a7682839)

## RESULT
Thus, the python program for simulating ARP protocols using TCP was successfully 
executed.
