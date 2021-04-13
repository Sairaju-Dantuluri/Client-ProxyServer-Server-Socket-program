# Client-ProxyServer-Server-Socket-program
A file transfer socket program

Client asks Proxyserver for a txt file. If the proxy has the file it sends it to the client. 
If file is not available,  the proxy requests server for the file, and if the server has it file is send to the proxy and 
subsequently to the client.

if another client asks for the same file proxy will send the file without the interference of the server.

The above proxyserver accepts multiple clients at the same time.
