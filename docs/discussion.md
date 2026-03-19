Question 1 - What is an IP address?
- Why do we need IP addresses?
- What is the relation between TCP and IP?
- What is a socket? Have you heard of different types of sockets?
- What is up with the address: 127.0.0.1?

An ip adress is a number that connects to a device, so each device has an ip adress to commuicate with it, which is why we need it. For devices to talk to each other. 
TCP is Transmission Control Protocol, meaning, it handles the transition process from ip to ip. It is what delivers the message, whereas ip is what sends and receives the message.
A socket is where the message is received on the computer. It is more specific than just the ip, as it receives it in a program/process. Http uses sockets.  
127.0.0.1 is localhost, meaning your own pc

Question 2 - What does a client-server architecture mean?
- Give a concrete example of where you would encounter this in real life.
- How do you decide who is the server and who is the client?

A client-server architecture is a model of dividing a number of tasks between two types of entities. The first type is the client, that works as a service requester. The other type is the server, that works as the opposing service provider.

A real life example could be your laptop that sends a request by googling something, where this query is received by the server somewhere, that could be represented by one of google's data centers that hereafter handles this query as designed.

To decide who is the server and who is the client, we can use a simple way of distinguishing them. The client is simply whoever/whatever that is trying to gain some sort of information, whereas the server is where this data is stored that has the functionality of supplying said data.

Question 3 - What is the difference between client-server architecture and the broker architecture?
- What are the benefits of the broker pattern?
- What could be potential downsides?

The difference between a client-server and a broker architecture is that a broker architecture has a sort of middleman inbetween. The broker architecture still has a client and a server, however all the data goes through the middleman/broker, which is a huge upside. Since they aren't directly connected, both the client and server are interchangeable, as opposed to the direct client-server architecture where they are mutaually dependable. 

A potential downside could be performance, since another link in the chain could potentially cause an increased latency. Another downside could be if there is an instability on the broker link, since if that link goes down, it would take the entire system down, since everything is connected through that.7

Question 4 What does Peer-to-Peer mean?
- What are the main characteristics of this architecture?
- Have you encountered it anywhere online?
- Does Peer-to-Peer applications mean that there are no servers and only clients?
- What benefits could there be to using this pattern?
- What downsides could there be to this pattern?

Peer-to-Peer means that pcs directly communicate with each other, where they do not communicate through a server. So the main characteristic is not using a server. This is often used in gaming, where you make your own server to play with your friends, and then they connect to that server. Example for this is if the serverhost is lagging, everyone will lag, however if there is a online big server, only the player will lag. 
It does not mean that there are no servers, it means devices can be servers. The benefits are that no central server is needed, so you can for example play at all times, it is also more cost effecient, and can be faster since its direct. However the security could be weaker, and the internet is local so it needs to be good, if not the server will run poorly.  