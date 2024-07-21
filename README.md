# Evilbytecode Shellcode Execution Tactics

This repository contains various projects that demonstrate techniques for executing shellcode and performing advanced memory manipulation.


### APC Injection
Exploits the Asynchronous Procedure Call (APC) technique to execute malicious code within target processes.

### Early Bird APC Injection
A variation of APC Injection focusing on executing code before the main process starts.

### Local Mapping Injection
Demonstrates malicious code injection via memory mapping into local processes.

### Local Payload Execution
Addresses the direct execution of malicious payloads in a system's local environment.

### Payload Execution Fibers
Demonstrates running shellcode using Fibers, a type of lightweight thread.

### Payload Placement
Shows how to store shellcode in the .text section of a process and execute it.

### Process Injection (Shellcode)
Exploits shellcode injection directly into running processes to control or execute malicious tasks.

### Registry Shellcode
Demonstrates writing and reading shellcode to/from the Windows Registry.

### Remote Function Stomping Injection
Exploits the substitution of functions in remote systems to carry out malicious activities.

### Remote Mapping Injection
Demonstrates malicious code injection via memory mapping into remote processes.

### Remote Thread Hijacking
Focuses on hijacking threads in remote system processes to execute malicious code.

### Threadless Injection
Demonstrates threadless injection using Go & C, where shellcode is injected without creating a new thread.
