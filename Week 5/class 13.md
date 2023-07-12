# Message Queues

----

**Socket.io Chat Example**

1. Explain to a non-technical recruiter what the Chat Example (above) does.

> The Chat Example is like a computer program that can have conversations with people. You can type messages or questions, and it will respond as if it's a real person talking to you. It has been trained on a lot of information from the internet, so it knows about many different things. You can ask it questions, ask for explanations, or just chat casually.

2. What proof of life are we getting on the backend from the above app?

> The backend of the application is like a computer system that handles the messages you send and sends them to the AI model for processing. It then receives the model's responses and sends them back to you. The backend might keep track of things like how many messages are sent and how quickly the model responds.

3. Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?

> We can use broadcast flag. Specifically, we can use the socket.broadcast.emit() method to send an event to all connected sockets except the socket that initiated the event.

----

**Rooms**

1. What is a room and how might a room be useful?

> A room in Socket.IO is like a virtual group where connected sockets can join. It helps organize and manage sockets based on their purpose or shared interest. Rooms are useful because they allow you to send messages or events specifically to sockets within a particular room, rather than broadcasting to everyone.

2. How do you join a room?

> using join method: socket.join('roomName');

3. how do you leave a room?

> using leave method: socket.leave('roomName');

----

**Namespaces**

1. What is a Namespace and what does it allow you to do?

> In Socket.IO, a namespace is like a separate communication channel that allows you to organize different parts of your application. It acts as a distinct path or URL within the Socket.IO server. Namespaces provide benefits such as isolation and organization by separating functionalities into separate channels. 


2. Each namespace potentially has its own what? (hint: 3 things)

> Sockets, events & configuration


>