# Read: 13 - Message Queues

## Reading

[Socket.io Chat Example](https://socket.io/get-started/chat/)

1. **Explain to a non-technical recruiter what the Chat Example (above) does.** A bi-directional communication channel between a client and a server, using the server to push messages to clients
2. **What proof of life are we getting on the backend from the above app?** Connected to the server and that a client is connected - via the use of console logs in the terminal
3. **Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?** `socket.broadcast.emit`

[Rooms](https://socket.io/docs/v4/rooms)

1. **What is a room and how might a room be useful?** A room is an arbitrary channel that sockets can join and leave. It can be used to broadcast events to a subset of clients.
2. **How do you join a room?** Use `socket.join` to subscribe the socket to a given channel
3. **How do you leave a room?** Use `socket.leave` to leave a room, otherwise sockets leave all channels automatically upon disconnection.

[Namespaces](https://socket.io/docs/v4/namespaces/)

1. **What is a Namespace and what does it allow you to do?** A Namespace is a communication channel that allows you to split the logic of your application over a single shared connection (also called "multiplexing").
2. **Each namespace potentially has its own what? (hint: 3 things)** Event handlers, middlewares, rooms
3. **Discuss a possible use case for separate namespaces** Your application has multiple tenants so you want to dynamically create one namespace per tenant

### Bookmark and Review

[Socket.io Emit Cheatsheet](Socket.io Emit Cheatsheet)
