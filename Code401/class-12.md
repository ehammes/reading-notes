# Read: 12 - Socket.io

## Reading

[Web Sockets](https://en.wikipedia.org/wiki/WebSocket)

1. **What is a Web Socket?** A computer communications protocol, providing full-duplex communication channels over a single TCP connection
2. **Describe the Web Socket request/response handshake and what happens once the connection is established.** To achieve compatibility, the WebSocket handshake uses the HTTP Upgrade header to change from the HTTP protocol to the WebSocket protocol. The WebSocket protocol enables interaction between a web browser (or other client application) and a web server with lower overhead than half-duplex alternatives such as HTTP polling, facilitating real-time data transfer from and to the server. This is made possible by providing a standardized way for the server to send content to the client without being first requested by the client, and allowing messages to be passed back and forth while keeping the connection open. In this way, a two-way ongoing conversation can take place between the client and the server.
3. **Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.** Request

[Socket.io Tutorial](https://www.tutorialspoint.com/socket.io/)

1. **What does the event handler io.on() do?** The io.on event handler handles connection, disconnection, etc., events in it, using the socket object.
2. **Describe some possible proof of life or proof that the code works as expected** Use console logs when a connection is made and disconnected
3. **What does socket.emit() do?** Creates custom events

[Socket.io vs Web Sockets]

1. **What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).**

    * `WebSocket` is the communication Protocol that provides bidirectional communication between the Client and the Server over a TCP connection; WebSocket remains open all the time, so they allow real-time data transfer.
    * `Socket.IO` is a library that enables real-time and full-duplex communication between the Client and the Web servers. It uses the WebSocket protocol to provide the interface. Generally, it is divided into two parts; both WebSocket vs Socket.io are event-driven libraries.

2. **When would you use Socket.IO?** Works on all platform, server or device - ensuring quality, reliability, and speed. Works on work-based events. Handles support level and the inconsistencies from the browser.
3. **When would you use WebSockets?** Real-time communication between the client and the webserver, provides full-duplex communication, removes the overhead, reduces complexity, is effortless and efficient.

### Videos

[OSI Model Explained](https://www.youtube.com/watch?v=vv4y_uOneC0)

1. **What are a couple of key takeaways from this video?** To communicate between computers this is called the OPI model - Open Systems Interconnection model. This was introduced by ISO in 1984 and the model includes the following layers: application, presentation, session, transport, network, data link, physical. All these layers are needed to communicate and transfer data across computers, servers, etc.

[TCP Handshakes Explained](https://www.youtube.com/watch?v=xMtP5ZB3wSk)

1. **Translate the gist of this video to a non-technical friend** TCP - Transmission Control Protocol. TCP involves the following steps in order to establish a connection and transfer data:
    1. The client sends a SYN segment to the server, asking for synchronization
    2. The server replies with SYN-ACK
    3. The client replies with ACK (essentially acknowledging with 'yes')

### Bookmark and Review

* [Socket.io Documentation](https://socket.io/docs/)
* [Socket.io Server API](https://socket.io/docs/server-api)
* [Socket.io Client API](https://socket.io/docs/client-api)
* [Socket Testing Tool](https://amritb.github.io/socketio-client-tool/)