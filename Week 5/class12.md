# Socket.io

----

**Web Sockets**

**1. What is a Web Socket?**

> Technology that allows real-time communication between a web browser (client) and a server. It creates a long-lasting connection that enables them to send messages back and forth without delay.

**2. Describe the Web Socket request/response handshake and what happens once the connection is established.**

> WebSocket begins with a handshake process where the client requests a WebSocket connection from the server. If the server agrees, they exchange special keys to verify each other's identity. Once the verification is successful, the WebSocket connection is established, enabling instant message exchange. Both the client and server can now send messages to each other without delay. Either party can decide to close the connection when needed, allows the client and server to establish a direct line of communication. Once established, they can freely exchange messages in real-time, creating a seamless and responsive connection.

**3. Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.**

> request

----

**Socket.io Tutorial**

1. What does the event handler io.on() do?

> Used to listen for events from clients connected to the server. It allows us to register functions that will be executed when a specific event occurs. By using io.on(), you can handle different events and respond accordingly, enabling real-time communication between the server and clients in a straightforward manner.

2. Describe some possible proof of life or proof that the code works as expected

> Logging & Code review

3. What does socket.emit() do?

> Creates custom events

----

**Socket.io vs Web Sockets**


1. What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).

> WebSocket is a protocol that allows real-time communication between a client and server. Socket.IO is a library built on top of WebSocket that adds more features and simplifies real-time communication in web applications. It's like WebSocket is the foundation, while Socket.IO enhances it by providing additional tools and capabilities.

2. When would you use Socket.IO?

> Socket.IO is commonly used when we need to build applications that require real-time communication or event-driven functionality. 

> EX: chat applications, Collaborative Applications & multiplayer games.

3. When would you use WebSockets?

> WebSockets are used when we want to create applications that require real-time, two-way communication between a client and server. 
> EX: Chat and Messaging Applications, Collaborative Editing Tools & Real-Time Updates
