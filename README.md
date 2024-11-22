C Project

Description
This project explores fundamental concepts of programming in C, including pointers, pipes, forks, and inter-process communication (IPC). It implements a client-server architecture to simulate interaction between two separate processes.

The goal is to understand and implement low-level mechanisms for communication between a client and a server.

Key Concepts
1. Pointers
Used to manipulate memory addresses and share data between functions or processes.
2. Pipes
A method of communication allowing two processes to transmit data through a unidirectional channel.
3. Fork
Used to create child processes from a parent process.
4. Inter-Process Communication (IPC)
Implemented using pipes to enable message exchange between the client and the server.

Main Features
Server: Handles requests sent by the client and sends responses.
Client: Sends requests to the server and processes the responses.
Use of fork to manage parallel processes.
Error handling to ensure program robustness.

Requirements
C Compiler (e.g., gcc).
Unix/Linux system recommended for fork and pipes functionality.
make to automate compilation.

Compilation and Execution

Step 1: Compile the code
To compile using make, run:
bash
make all  
This will generate two executables: server and client.

Step 2: Start the server
First, start the server:
bash
./server  

Step 3: Start the client
Then, in another terminal, start the client:
bash
./client  
 
Project Structure
server.c: Server source code.
client.c: Client source code.
Makefile: Script to automate compilation and file management.

Author
Diego Rousseaux