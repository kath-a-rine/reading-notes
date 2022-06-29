# Message Queues

## [Socket.io Chat Example](https://socket.io/get-started/chat/)

*Explain to a non-technical recruiter what the Chat Example (above) does.*

The chat example shows a bi-directional communication channel between a client and server.
*What proof of life are we getting on the backend from the above app?*

Through console.logs in the terminal confirming proof of life.

*Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?*

`socket.broadcast.emit`

## [Rooms](https://socket.io/docs/v4/rooms)

*What is a room and how might a room be useful?*

"A room is an arbitrary channel that sockets can `join` and `leave`." A room can be used to broadcast messages to relevant clients.

*How do you join a room?*

Call `join` to subscribe the socket to a channel. Then use `to` or `in` to broadcast or emit to specific rooms.

*How do you leave a room?*

To leave, call `leave` in the same way you would `join`.

## [Namespaces](https://socket.io/docs/v4/namespaces/)

*What is a Namespace and what does it allow you to do?*

"A communication channel that allows you to split the logic of your application over a single shared connection." 

*Each namespace potentially has its own what? (hint: 3 things)*

- event handlers
- rooms
- middleware

*Discuss a possible use case for separate namespaces*

- creating spaces only authorized users are allowed to access