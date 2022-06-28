# Socket.io

## [Web Sockets](https://en.wikipedia.org/wiki/WebSocket)

*What is a Web Socket?*

A communications protocol.

*Describe the Web Socket request/response handshake and what happens once the connection is established.*

A client sends a WebSocket handshake request and the server will respond with a WebSocket handshake response. Once connected the communication is switched to a "bidirectional binary protocol" rather than the HTTP protocol. WebSocket protocol allows interaction between a web browser and a web server with lower overhead.

*Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.*

request

## [Socket.io Tutorial](https://www.tutorialspoint.com/socket.io/)

*What does the event handler io.on() do?*

It "handles connection, disconnection, etc., events using the socket object."

*Describe some possible proof of life or proof that the code works as expected*

Checking server connection using `nodemon`. Logging to the console 'A user connected' or 'A user disconnected.'

*What does socket.emit() do?*

Allows you to create and fire custom events.

## [Socket.io vs Web Sockets](https://www.educba.com/websocket-vs-socket-io/)

*What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).*

WebSocket is the communication protocol allowing bidirectional communication between the client and server. Socket.io is a library enabling this communication using the WebSocket protocol.

*When would you use Socket.IO?*

To handle degradation of technical alternatives, to various support levels and inconsistencies in browsers.

*When would you use WebSockets?*

When you want real-time, efficient communication between a client and web server. 

## OSI Model Explained

*What are a couple of key takeaways from this video?*

Open System Interconnection Model defines how data is translated from one computer to another, regardless of OS. The Open System Integration Model was introduced in 1984 by ISO to standardize these communications. The model contains the following layers: Application, Presentation, Session, Transport, Network, Data Link, and Physical. 

## TCP Handshakes Explained

*Translate the gist of this video to a non-technical friend*

Transmission Control Protocol (TCP) data is delivered successfully and accurately. Many applications use TCP. Before transmitting data a TCP connection must be made with a three-way handshake.

1. Client sends a SYN segment to the server asking for synchronization (i.e. the connection).
2. The server replies with SYN-ACK (meaning synchronization and acknowledgement). The server acknowledges the request and asks the client to also open a connection.
3. The client replies with ACK.

Once the previous steps are completed the two-way connection is established.
