# C Networking – Exercise 3

## Overview

This repository contains the solutions to **Exercise 3** from the *Computer Networks* course, implemented in **C**.  
The project is divided into two parts:

- **Part A** – Socket programming and basic server implementation  
- **Part B** – Concurrent networking and threaded client‑server interaction

## Topics Covered

- Socket programming (TCP/UDP)
- Client/server communication
- Multi‑client handling
- Concurrency with threads
- Message passing between networked processes

## Repository Structure
Part A/ # Socket server and networking code
Part B/ # Threaded networking and concurrent communication

## Technologies

- **C** — primary language
- **BSD sockets API** for network communication
- **pthread** (POSIX threads) for concurrency
- Compilable with a standard GCC toolchain

## Building & Running

### Part A

```bash
cd "Part A"
gcc -o server server.c   # adjust filenames if needed
./server
```

### Part B
```bash
cd "Part B"
gcc -o client client.c server.c -lpthread   # example
./server
```
# and then run client
Note: Each part may include multiple C source files. Use a Makefile or gcc directly.

## Example Usage

For Part A:
```bash
./server
```
# Connect using telnet / netcat or custom client

For Part B:
```bash
./server
./client
```
Follow the on‑screen instructions and input formats.

## What You’ll Learn

This project demonstrates:
- Low‑level socket I/O in C
- Communication protocols
- Handling multiple clients
- Concurrency and thread synchronization
