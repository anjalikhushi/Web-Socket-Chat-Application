Built the chat application with Spring Boot and WebSocket where anyone can communicate or chat with others. Just you need to type your name to login and start chatting with others.

Generally, the web application has developed in the model of request and response parameter, so whenever any request comes to the server then it returns the data as a response parameter, but if you noticed, the server never sends the data to the client on its own.

The server always waits for the client or browser request and accordingly sends the data in the form of JSON. In short, there is only one way of communication between the server and the client. The server always needs to be dependent on the client in order to send the data.

But with the help of the WebSocket Protocol, we can achieve the two-way communication between the server and the client, which means the server no need to wait for the client’s request to send the data.

<img width="944" alt="chat" src="https://github.com/anjalikhushi/Web-Socket-Chat-Application/assets/82653640/905218c1-69da-4c6c-96ce-8a2ea3ee4978">
