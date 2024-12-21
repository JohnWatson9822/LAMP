# LAMP

This is a simple TCP/IP server which uses HTTPS. This project is to understand the client-server communication.
Since this is developed for windows we are using Winsock. For other UNIX like systems we can simply use sys/socket.
Though we are using Winsock instead of sys/socket both are quite similar.

1. Initialize Winsock.
2. Create a socket.
3. Bind the socket.
4. Start listning.
5. Accept the incoming connections.
6. Read the request.
7. Send the response.
8. Disconnect.

For TCP/IP server implementation we've refered Microsoft Documentation (https://learn.microsoft.com/en-us/windows/win32/winsock/creating-a-basic-winsock-application).

On top of this we are just implementing HTTP.

TO DO's:
1. Handle different types of requets.
2. Implement file handling to send responses.
3. Implement multithreading to handle multiple clients.
4. Add GUI.
