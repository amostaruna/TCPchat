# SimpleTCPChat
Simple Server and multiple Client chat program using TCP Protocol and multi thread with C# Language
# How Server Program Works
![Screenshot (161)](https://user-images.githubusercontent.com/64347680/124783389-39432e00-df6f-11eb-8be0-db248306289c.png)

1. Server Program Will wait for Client Connection (TCP Listener)
2. If Client connected, server will start a new client thread for receiving, broadcast and save client messsages.
3. If Client Program is sending  a message, Server will receive it, encode it from ASCII to string, save it into "ChatData.txt" and broadcast the message to other client.
# Server Flowchart
![untitled](https://user-images.githubusercontent.com/64347680/124790080-0f8d0580-df75-11eb-9ac0-313a70f675dd.png)
# How CLient Program Works
![Screenshot (162)](https://user-images.githubusercontent.com/64347680/124783518-54ae3900-df6f-11eb-8849-67b749af4c2b.png)

1. Client program will try to connect to the server (TCP Client)
2. If user try to send messages, Client Program will write the string from client, encode it into ASCII and send it to server network stream
3. If server is sending a broadcast, client will receive it, encode it from ASCII to string and show the broadcast messages.
# Client Flowchart
![Client Flowchart](https://user-images.githubusercontent.com/64347680/124790164-23d10280-df75-11eb-98c2-1dd88f32c1bb.png)

# Installation
1. Clone the repository
2. in the server code, change "C:\Users\Amos Taruna\source\repos\Server_AJK\ChatData.txt" into your desired storage folder.
3. Move "ChatData.txt" to your desired folder.
# Preview
![image](https://user-images.githubusercontent.com/64347680/124463240-cb570500-ddbc-11eb-8b8b-5b4e697a0525.png)
# Contact 
email : amostaruna@gmail.com
