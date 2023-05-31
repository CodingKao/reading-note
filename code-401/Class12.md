# Class 12 Socket.io

#### Link to article: [Web Sockets](https://en.wikipedia.org/wiki/WebSocket)
#### Link to article: [Socket.io Tutorial](https://www.tutorialspoint.com/socket.io/)
#### Link to article: [Socket.io vs Web Sockets](https://www.educba.com/websocket-vs-socket-io/)
#### Link to video: [OSI Model Explained](https://www.youtube.com/watch?v=vv4y_uOneC0)
#### Link to video: [TCP Handshakes Explained](https://www.youtube.com/watch?v=xMtP5ZB3wSk)

***

**Bookmarks**

#### Link to article: [Socket.io Documentation](https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/api-server/)
#### Link to article: [Socket.io Server API](https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/api-server/)
#### Link to article: [Socket.io Client API](https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/api-server/)
#### Link to article: [Socket Testing Tool](https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/api-server/)

***

## Web Sockets

**What is a Web Socket?**
> A web socket is a technology that allows real-time communication between a web browser and a server, enabling instant data exchange and updates without the need for continuous page reloading.

**Describe the Web Socket request/response handshake and what happens once the connection is established.**
> The Web Socket handshake is a process where the client and server exchange information to establish a connection. Once the connection is established, they can send and receive data in real-time.

**Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.**
> request 

## Socket.io Tutorial

**What does the event handler `io.on()` do?**
> The event handler io.on() is used to listen for and handle events in a web application. It executes a function when a specific event occurs.


**Describe some possible proof of life or proof that the code works as expected**
> Successful execution of desired functionalities, the appearance of expected output or log messages, and passing relevant unit tests.


**What does socket.emit() do?**
> The socket.emit() function sends data from the client to the server or from the server to a specific client in a real-time communication using web sockets.

## Socket.io Tutorial

**What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).**
> WebSocket is a communication protocol that enables real-time, bidirectional communication between a client and a server. Socket.IO is a library built on top of WebSocket that provides additional features like event-based communication, room management, and fallback options for older browsers.

**When would you use Socket.IO?**
> Socket.IO is useful when you need real-time, event-driven communication between a client and server, especially in applications that require features like broadcasting messages or handling multiple connections simultaneously.


**When would you use WebSockets?**
> You would use WebSockets when you need to establish a direct, persistent connection between a client and a server to enable real-time, bidirectional communication.

## OSI Model Explained

**What are a couple of key takeaways from this video?**
> The OSI model, or Open System Interconnection model, is a framework that defines how different computer systems can communicate with each other. It consists of seven layers that handle specific tasks in the communication process.  Physical, Data Link, Network, Transport, Session, Presentation, and Application.


## TCP Handshakes Explained

**Translate the gist of this video to a non-technical friend**
> TCP, or Transmission Control Protocol, is a method used by computers to send and receive data over the internet. It ensures that the data arrives in the correct order and without errors.


## Reflection

**What are your learning goals after reading and reviewing the class README?**
> My learning goals are to understand how computer networks work using the OSI network model. I also want to learn about TCP and UDP protocols, stateful networking, packets, buffered transfer, web sockets, Socket.io, and networking events. Additionally, I aim to create a Socket.io server that can handle events and enable real-time messaging. By using events, I will be able to correctly direct incoming messages and their accompanying information.