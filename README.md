**2.1. Original code of broadcast chat.**  
![](2.1.1.png)  
![](2.1.2.png)  
After the server is run with the command `cargo run --bin server` and each client is run with the command `cargo run --bin client`, from the output above it can be seen that each client and also the server get chat broadcasts from each client. Every time a client types a message on the command line, the string will be sent to the server and the server will continue to send it to all clients connected to it.  

