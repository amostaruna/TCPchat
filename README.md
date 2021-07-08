# TCP Chat Program

# Features
1. Can accept multiple Clients
2. Using Multithread for lightweight processing
3. Using TCP Protocol
4. Saving the message everytime server receiving it.
5. Broadcasting incoming message to other clients except the message sender.
6. Each Client can have their own unique username
# Server and Client Connection Flowchart
![Server Flowchart (2)](https://user-images.githubusercontent.com/64347680/124899813-ad7edf80-e00a-11eb-878f-7d8ed5aba96a.png)

# How Server and Client Program Works
![Screenshot (161)](https://user-images.githubusercontent.com/64347680/124783389-39432e00-df6f-11eb-8be0-db248306289c.png)
![Screenshot (162)](https://user-images.githubusercontent.com/64347680/124783518-54ae3900-df6f-11eb-8849-67b749af4c2b.png)

1. Server Program Will wait for Client Connection 
2. If Client connected, server will add client to client list and start a new clientListener thread for receiving, broadcast and save client messsages.
3. If Client Program is sending  a message, Server will receive it, save it to .txt and broadcast the message to other client except the sender.
# Installation
1. Clone the repository
2. in the server code, change "C:\Users\Amos Taruna\source\repos\Server_AJK\ChatData.txt" into your desired storage folder.
3. Move "ChatData.txt" to your desired folder.
# Preview
![image](https://user-images.githubusercontent.com/64347680/124463240-cb570500-ddbc-11eb-8b8b-5b4e697a0525.png)
# Contact 
email : amostaruna@gmail.com
