# Reading-12 #

**What is a Web Socket?**
A Web Socket is a communication protocol that provides full-duplex communication channels over a single TCP connection. It enables interaction between a web browser (or other client application) and a server with lower overhead compared to traditional HTTP connections.

**Describe the Web Socket request/response handshake and what happens once the connection is established.**
The WebSocket handshake involves an initial HTTP request from the client to the server, containing specific headers indicating the intention to upgrade the connection to a WebSocket. Upon receiving this request, the server responds with a confirmation, and once the handshake is complete, the connection upgrades to WebSocket protocol. Once established, both client and server can send and receive messages asynchronously.

Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.
Web Sockets provide a standardized way for the server to send content to a client without first receiving a request from that client.

**What does the event handler io.on() do?**
The event handler io.on() in Socket.IO binds a callback function to a particular event emitted by either the server or the client. It allows the application to respond to events such as connection, disconnection, or custom events defined by the user.

**Describe some possible proof of life or proof that the code works as expected.**
Possible proof of life for WebSocket or Socket.IO code includes logging connection events, such as successful connections or disconnections, and monitoring message exchanges between the client and server. Additionally, testing the code with various scenarios, including edge cases and error handling, can provide confidence that the code functions as expected.

**What does socket.emit() do?**
socket.emit() in Socket.IO sends a custom event from the server to the client (or vice versa), along with optional data payloads. It allows for the transmission of real-time data between client and server, triggering actions or updating the UI based on the received event.

**What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).**
WebSocket is a protocol that provides a communication channel between a client and a server over a single TCP connection. Socket.IO is a library that abstracts WebSocket and other transport mechanisms (such as long polling) to provide real-time bidirectional event-based communication. In analogy, WebSocket is like the underlying protocol (like Git for version control), while Socket.IO is a higher-level library built on top of WebSocket (similar to GitHub for Git).

**When would you use Socket.IO?**
Socket.IO is useful when you need real-time, bidirectional communication between a client and a server and want to handle various transport mechanisms transparently. It's particularly beneficial for applications requiring features like chat applications, live updates, or collaborative tools where instant communication is essential.

**When would you use WebSockets?**
You would use WebSockets when you need a low-latency, full-duplex communication channel between a client and a server without the overhead of HTTP. It's suitable for scenarios where real-time data transfer, such as stock tickers, online gaming, or live sports updates, is crucial.

**What are a couple of key takeaways from this video?**
I leanred about the imprtance of the HIerchical structure and the purpose of each layer. Such as the Physical layer which deals with the actual physical connections and hardware.

**Translate the gist of this video to a non-technical friend**
Imagine you want to have a conversation with a friend, but you're in different rooms and can't hear each other well. So, you agree on a special way to start your chat. First, you send a message asking if they're ready to talk. Your friend then responds, saying they're ready too. Finally, you both confirm that you're ready to start your conversation. This process ensures that you're both on the same page and ready to exchange messages clearly. In computer networks, this "conversation starter" is like a TCP handshake, where two devices establish a reliable connection before sharing data.

## Things I want to know more about ##
