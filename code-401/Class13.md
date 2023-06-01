# Class 13 Socket.io

#### Link to article: [Socket.io Chat Example](https://socket.io/get-started/chat/)

#### Link to article: [Rooms](https://socket.io/docs/v4/rooms)

#### Link to article: [Namespaces](https://socket.io/docs/v4/namespaces/)

***

**Bookmarks**

#### Link to article: [Socket.io Emit Cheatsheet](https://socket.io/docs/v4/emit-cheatsheet/)

***

## Socket.io Chat Example

**Explain to a non-technical recruiter what the Chat Example (above) does.**
> The Chat Example is a simple application that allows users to chat with each other in real-time. It uses Socket.IO, a tool that enables communication between a server and clients, to send and receive messages instantly.

**What proof of life are we getting on the backend from the above app?**
> The backend of the app confirms its existence by printing "a user connected" when a user connects and "user disconnected" when a user disconnects.

**Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?**
> To send a message to everyone except for a specific emitting socket, we can use the "broadcast" flag provided by Socket.IO.

## Rooms

**What is a room and how might a room be useful?**
> A room in Socket.IO is an arbitrary channel where sockets can join and leave. It allows broadcasting events to a specific group of clients. Rooms are useful for targeting and sending messages to a subset of connected sockets.

**How do you join a room?**
> To join a room in Socket.IO, you call the `join` method on a socket instance and provide the name of the room as a parameter.

**How do you leave a room?**
> To leave a room in Socket.IO, you call the `leave` method on a socket instance and provide the name of the room as a parameter.

## Namespaces

**What is a Namespace and what does it allow you to do?**
> A Namespace in Socket.IO is a communication channel that allows you to separate and organize the logic of your application over a shared connection. It provides separate event handlers, rooms, and middlewares for better organization and isolation of functionality.

**Each namespace potentially has its own what? (hint: 3 things)**
> Event handlers, rooms, and middlewares.

**Discuss a possible use case for separate namespaces**
> Separate namespaces can be useful for creating distinct communication channels for authorized users or multiple tenants in an application.

## Reflection

**What are your learning goals after reading and reviewing the class README?**
> My learning goals are to understand the concept of messaging queues, their purpose in routing events and messages between clients, and the challenges involved in ensuring message delivery and client subscription management.