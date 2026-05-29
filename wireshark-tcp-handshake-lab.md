# Wireshark TCP 3-Way Handshake Lab

## Objective
To observe and understand how a TCP connection is established using packet analysis.

## Tools Used
- Wireshark
- Ubuntu Linux VM

## Environment
- Operating System: Ubuntu (Virtual Machine)
- Network Interface: enp0s3
- Tool: Wireshark

## What I Did
- Started a packet capture on my network interface
- Generated traffic by visiting a website (example.com)
- Filtered traffic to isolate TCP SYN packets
- Identified SYN, SYN-ACK, and ACK packets
- Traced a full TCP 3-way handshake between client and server

## Key Observations

### SYN (Client → Server)
- My machine initiated a connection request to a remote server

### SYN-ACK (Server → Client)
- The server responded acknowledging the request

### ACK (Client → Server)
- My machine confirmed the connection

## TCP 3-Way Handshake Flow
Client → SYN → Server  
Server → SYN-ACK → Client  
Client → ACK → Server  

## What I Learned
- How TCP connections are established
- How to filter and analyze packets in Wireshark
- How client-server communication works at the network level
- How to identify SYN, SYN-ACK, and ACK packets in real traffic

## Key Takeaway
Every web connection begins with a TCP handshake, and packet analysis tools like Wireshark allow visibility into this process.
