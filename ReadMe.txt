This is chat app by using Unity and Nodejs.

Server is made by using node.js. By using 'net' module, client and server is connected.
And in server, data is received by using stream from client.

Client is made by using Unity. In C# engine, 	TcpClient, NetworkStream are used to connect client and server.

---------------------------------------------------------------------------

This project is very simple for chatting each other.
First, user login in username.
    if user is sign in node server, user can send message all clients.

Second, user send any message to server and then server send user's message to other clients.
    all users can be received user's message.

Last step, user disconnect server.
    If user disconnect server, server is remove user's socket.