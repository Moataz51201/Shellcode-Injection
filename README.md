# Shellcode Injection

This repository contains a detailed guide and example implementation of Shellcode Injection using the Win32 API. The project demonstrates the steps and processes involved in injecting shellcode into a target process on Windows.

## Features
- Detailed walkthrough of Shellcode Injection.
- Example code using Win32 API functions like `OpenProcess`, `VirtualAllocEx`, and `CreateRemoteThread`.
- Pre-requisites for understanding Windows internals, threads, processes, and memory management.

## Pre-requisites
1. Knowledge of:
   - Windows Internals (Processes, Threads, Handles, Memory Management)
   - Programming in C and Assembly
2. Tools:
   - Visual Studio for compiling the code.
   - Msfvenom for generating shellcode.

## Usage
1. Compile the code using Visual Studio:
   - Open the project and build the executable.
2. Run the executable with the target process ID:
   shellcode-injection.exe <ProcessID>
