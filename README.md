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

![image](https://github.com/user-attachments/assets/5eacea1c-16bd-49e5-866b-77cb828a7a7e)


## OUPUT - ARP

![image](https://github.com/user-attachments/assets/63deb03e-c4b7-494c-821e-9885cf775c30)



## PROGRAM - RARP

![image](https://github.com/user-attachments/assets/7ccc05f4-9068-439e-8403-5d7cf4f7163c)


## OUPUT -RARP

![image](https://github.com/user-attachments/assets/3cb59bfe-1e78-4f1d-82dc-acc160cf633d)


## RESULT
Thus, the python program for simulating ARP protocols using TCP was successfully 
executed.
