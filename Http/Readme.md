## HTTP

It stands for hyper text transfer protocol.

Http is a set of rules and regulations to send the data which is hypertext.
Hypertext is a kind of special document which contains another document in the form of hypertext and their can be multiple such objects one objects is link to many such objects.

objects contains mp3 files , png, jpg files and other hypertext also every object has a URL which is link by the `URL` to the other object.

`URL id divided into multiple parts`

![](./Assests/Screenshot%202023-04-25%20093041.png)

Let's say we write
`http://flipkart.com/image/23.jpg?q=50`

![](./Assests/Screenshot%202023-04-25%20093705.png)

Http defines the whole procedure that how the server and client will interact.

The first message that we send -> Http request

The second message that we receive -> Http response

![](./Assests/Screenshot%202023-04-25%20095335.png)

**`Http is a stateless protocol`** which means server does not store any information about the client.

Http is depend upon TCP protocol.

`When we have to send the request to the server first we they established a TCP connection over that they established a HTTP connection on the basis of this we can send the request and receive the response.`

There are two types of Http connections-

1 -> Persistent http

2 -> Non-persistent http

Persistent http connection are those which does not break even after when we request something and we receive the response the connection did not break.

Web sockets are the example of this protocol.

In Non-Persistent http connection every time the tcp connection established after that when we request something and on the basis of our request we receive the reponse from the server after that the connection breaks.

Example -> When we open a website it reload and when we have to fetch something like details about some food it will again make a request and after that the connection breaks so this process continues .
