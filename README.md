# Task4 in opertaing systems.

# waiters:
> Avihay Finish , 208907113.

> Amit Rovshitz , 207701426.

- [Our Project](#our-project)
    - [How to use](#how-to-use)
    
# Our Project:

> This project is a chat server capable of handling multiple clients using the reactor design pattern. The reactor consists of a linked list of file descriptors representing connected clients, with a corresponding handler function for each client. <br>
> When a client connects to the server, it is added to the linked list. The server then uses the 'poll' function to listen on the file descriptors, allowing it to monitor incoming messages from the clients. When a client sends a message, the 'poll' function notifies the server, indicating that there is a message available on the corresponding FD. <br> 
> This design allows the server to efficiently manage and respond to messages from multiple clients, making it suitable for concurrent chat communication. <br>  

# How to use

> To trying this tool, follow these steps: <br>
> **1:** Copy the URL of this Git project by clicking on the green button and then the copied button. <br>
> **2:** Open your Visual Studio Code or CLion and navigate to the directory where you want to clone the files. In the terminal, run the command 'git clone 'URL'', replacing 'URL' with the copied URL of this project. <br>
> **3:** Run the command 'make all' in the terminal. This will compile the code and generate the executable file. <br>
> **4:** Now that you have the executable file, run the command './react_server' to start the server. <br>
> **5:** To create clients and connect them to the server, open a new terminal window and run the command 'telnet 127.0.0.1 9034'. This will create a client that connects to the server, allowing you to send messages. You can create multiple clients using this method, as the server is designed to handle multiple connections. <br>

**Please note that you need to have a GCC compiler installed on your machine for this to work.**
