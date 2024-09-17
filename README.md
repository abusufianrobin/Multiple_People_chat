Completed Features:
Multiple Clients, Single Server Setup:

You successfully implemented a system where multiple clients connect to a single server using the IP address localhost (127.0.0.1) and port 8080.
Automatic Client Naming:

Each client receives a unique name upon connecting, such as Client-0, Client-1, etc.
Console-based Communication:

Clients send messages from their console, which are broadcasted by the server to all other connected clients.
Server-side Event Messaging:

The server prints event messages to its console, including information about connected clients and messages being broadcasted.
Bonus Features:
Logging Server Event Messages to a File:

The server logs important event messages (e.g., client connections, message broadcasts) into a file, allowing for persistent records of server activities.
Sending Previous Messages to New Clients:

When a new client joins the server, all previous messages are sent to them so they can catch up on the ongoing conversation, along with the sender's names.
Threading for Concurrent Clients:

Each client is handled in a separate thread, allowing simultaneous communication between multiple clients without blocking the server or other clients.
Client-Server Mapping:

A hashtable is maintained on the server to map each client’s socket to their unique name, making it easier to identify and manage clients.
These features form a solid foundation for real-time communication in your socket-based messaging system. You can build on these with additional features as mentioned earlier to further enhance the project.
