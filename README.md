# simple-chat
Networks project fom Uni

## **Usage**:
To initiate the server, open a terminal in the project directory and execute the following command:
```bash
gcc -o server server.c
./server
```

In a new terminal or tab, to execute a client execute the following command:
```bash
gcc -o client client.c
./client hostname port_num
```
Where is 'hostname' you have to write the server IP, and in 'port_num' you have to write the server port. *default port is 1234.*
If you wish to open more clients, just execute:
```bash
./client hostname port_num
```

The first message written by a client will be used for the client username.
```
username
```

If you wish to send a message to specific user:
```
-username hello friend
```
If you wish to send a message to every user:
```
+The grades are out everyone!
```

- Authors:
  - [Tomás Antunes](https://github.com/tomassantunes)
  - [Daniel Barreiros](https://github.com/dbarreiros)