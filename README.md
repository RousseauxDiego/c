# C Project<br>

## Description<br>
This project explores fundamental concepts of programming in C, including pointers, pipes, forks, and inter-process communication (IPC). It implements a client-server architecture to simulate interaction between two separate processes.<br><br>

The goal is to understand and implement low-level mechanisms for communication between a client and a server.<br><br>

## Key Concepts<br>
1. **Pointers**<br>
   - Used to manipulate memory addresses and share data between functions or processes.<br>
2. **Pipes**<br>
   - A method of communication allowing two processes to transmit data through a unidirectional channel.<br>
3. **Fork**<br>
   - Used to create child processes from a parent process.<br>
4. **Inter-Process Communication (IPC)**<br>
   - Implemented using pipes to enable message exchange between the client and the server.<br><br>

## Main Features<br>
- **Server**: Handles requests sent by the client and sends responses.<br>
- **Client**: Sends requests to the server and processes the responses.<br>
- Use of `fork` to manage parallel processes.<br>
- Error handling to ensure program robustness.<br><br>

## Requirements<br>
- C Compiler (e.g., `gcc`).<br>
- Unix/Linux system recommended for `fork` and pipes functionality.<br>
- `make` to automate compilation.<br><br>

## Compilation and Execution<br>

### Step 1: Compile the code<br>
To compile using `make`, run:<br>
```bash<br>
make

