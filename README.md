# telnet-chat-server

## This project is a simple TCP/IP based chat app based on C#.

- Implement a TCP server application performing as a chat server. 
- Clients should be able to connect to the listening port using plaintext protocol and be able to communicate with each other. 
- Messages are separated by <LF>, when connected:
- User should be presented with a list of users currently online, 
- Everyone see messages from everyone, 
- Server should support /nick <nickname> 
- Command for users to be able to redefine the default auto-assigned nickname "GuestNNN" and /register command for users to be able to protect their nickname


### Installation

Clone the project

```sh
$ git clone https://github.com/jonpecson/telnet-chat-server
$ npm install -d
$ node app
```

Running the Server:
1. Open the ChatAppV2.sln
2. Select ChatServer as Startup Project
3. Click 'Start'


Running the Client:
1. Open another instance of ChatAppV2.sln
2. Select ChatClient as Startup Project
3. Click 'Start'
 
You can then run a multiple instance of the client.
