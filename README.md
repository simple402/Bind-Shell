# Bind Shell Server
This Python-based bind shell server allows remote command execution on a target machine by listening for incoming connections on a specified port. Once a client connects, it can send commands to be executed on the server, and the output is returned to the client. This tool is intended for educational purposes, penetration testing, and understanding network security concepts.

# Features
* Command Execution: Execute shell commands on the target machine and receive the output.
* Multi-threading: Handle multiple client connections simultaneously using threads.
* Customizable Port: Specify the port on which the server listens for incoming connections.
# Requirements
* Python 3.x
* click library (install via pip install click)
