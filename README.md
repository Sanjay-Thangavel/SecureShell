# Secure Shell Using WebSockets

Mock SSH using websockets with encryption.

**SSH**, also known as **Secure Shell**, is a network protocol that provides administrators with a secure
way to access a remote servers. SSH establishes a cryptographically secured connection between two
parties(client and server), authenticating each side to the other, and passing commands and output back and
forth.

For our project we have implemented a simple **SSH** using **websockets**, with the server written in Python
and the client in Javascript. User and password authentication is also implemented. The password is
encrypted before sending and hashed before storing.
