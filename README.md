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
## Client
![image](https://github.com/Suresh-2006/2c.ARP_RARP_PROTOCOLS/assets/149347611/739baac5-9a2f-4fe7-a12f-408e5ca21c57)

## Server
![Screenshot 2024-03-31 215212](https://github.com/Suresh-2006/2c.ARP_RARP_PROTOCOLS/assets/149347611/9a8f11be-502f-4485-b10e-5c45f0226cf5)

## OUPUT - ARP
## Client
![Screenshot 2024-03-31 215831](https://github.com/Suresh-2006/2c.ARP_RARP_PROTOCOLS/assets/149347611/2ed13fa8-55fd-4b6e-be41-34902831e88a)

## Server
![image](https://github.com/Suresh-2006/2c.ARP_RARP_PROTOCOLS/assets/149347611/b03216d7-0374-4d51-b7da-f576b5544fa5)


## PROGRAM - RARP
## Client
![image](https://github.com/Suresh-2006/2c.ARP_RARP_PROTOCOLS/assets/149347611/d39b8cf2-c5dc-47e2-8cb9-d0f41239a287)

## Server
![image](https://github.com/Suresh-2006/2c.ARP_RARP_PROTOCOLS/assets/149347611/2e3a824e-ece4-40d3-aa9d-36fbd57e0fbe)

## OUPUT -RARP
## Client
![image](https://github.com/Suresh-2006/2c.ARP_RARP_PROTOCOLS/assets/149347611/f7b40e7c-3e86-4bd5-9c47-9f086831f065)

## Server
![image](https://github.com/Suresh-2006/2c.ARP_RARP_PROTOCOLS/assets/149347611/3cc842db-f089-457b-a720-389be936ef87)

## RESULT
Thus, the python program for simulating ARP protocols using TCP was successfully 
executed.
