# Computer Networks
A set of multiple labs done for the course 'Computer Networks I' from the University of Toronto, aimed to introduce the basics of socket programming. Code is held in a private repository to prevent academic misconduct so please message me if viewing access is desired.

## File Transfer Lab
Used UNIX sockets to implement a simple client and server program which transfer files from the client to the server. This (make up) file transfer protocol is based on UDP, but used acknowledgements to guarentee transfer. It also implemented the following features:
* Fragmentation
* Flow Control 
* ACK/NACK


## Text Conferencing Lab
This lab used UNIX TCP sockets to implement a simple text conferencing application. It implemented the following features:
* Multiple users
* Database of login credentials, and users must login before accessing the application
* Support for group chat
* Inviting other users to group chats
* Querying online users
