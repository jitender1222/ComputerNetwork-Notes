OSI Model

`Open system interconnection model`

It is a standard which defines how the servers or computers are interconnected with each other.

There are few layers inside the OSI Model.

1. Application Layer

2. Presenatation Layer

3. Session Layer

4. Transport Layer

5. Network Layer

6. Data Link Layer

7. Physical Layer

**Application Layer**-> It is the top most layer in the OSI model .Whenever a sender sends something the first layer it can interact is the application layer.

**->** Whenever a sender sends something the application layer is responsible for providing the data for the very first time into the network.

**->** Responsible for reading and writing the data.

**->** It contains the application that helps users to interact on the network.For example Like the social media or a browser all of the things that the user interact and receive some response are all present inside the application layer.

**->** Error handling can also be done. For example if a user send the data which is not valid to that particular network then only it will throw an error.

`Architecture based on Application Layer `

1. Client-Server

2. Peer to Peer

3. Hybrid Server

4. client server-> It is a 2 level architecture.

`Server`-> It is basically a process and it provide a centralized area by which we can access various services such as websites and webApps whihc are directly connnected to the server.

`client`-> It is moreover like the frontend were the user can interact with.

1.1 `Peer to Peer` -> In this their are multiple networks in the world which are interconnected to each other. Every end system will help the other end systems to get the data. For example Torrent is based on Peer to Peer architecture .

1.2 `Hybrid`-> It is a combination of Client server and Peer to Peer architecture.

2. `Presentation Layer` -> It will take the data from the application layer and the data comes in the form of characters,numbers so the presentation layer convert this data in the form of machine representable format ie. 0 and 1.Here all the encryption and decryption of the messages is done with the help of SSL.

3. `Session Layer` -> The session layer provides the mechanism for opening, closing and managing a session between end-user application processes.In case of a connection loss this protocol may try to recover the connection. If a connection is not used for a long period, the session-layer protocol may close it and re-open it. It provides for either full duplex or half-duplex operation and provides synchronization points in the stream of exchanged messages.

4. `Transport Layer`-> The basic function of the Transport layer is to accept data from the layer above, split it up into smaller units, pass these data units to the Network layer, and ensure that all the pieces arrive correctly at the other end.The Transport layer also determines what type of service to provide to the Session layer, and, ultimately, to the users of the network. The most popular type of transport connection is an error-free point-to-point channel that delivers messages or bytes in the order in which they were sent.

The transport layer also identifies errors like damaged packets, lost packets, and duplication of packets, and provides sufficient techniques for error correction.

5. `Network Layer`-> It handles the service requests from the transport layer and further forwards the service request to the data link layer.It is responsible for breaking down the data segments into data packets and is tasked with reassembling them on the receiver side.This layer also ensures that the packets are transmitted over the best possible route to the destination system, governed by Internet protocols.

The network layer translates the **logical addresses** into physical addresses.

**Logical Addressing:** The `data link` layer implements the `physical addressing` and `network layer` implements the `logical addressing.` Logical addressing is also used to distinguish between source and destination system. The network layer adds a header to the packet which includes the logical addresses of both the sender and the receiver.

For Example -> Suppose Bob and Alice are connected to the same local area network (LAN), and Bob wants to send Alice a message. Because Bob is on the same network as Alice, he could send it directly to her computer across the network. However, if Alice is instead on a different LAN several miles away, Bob's message will have to be addressed and sent to Alice's network before it can reach her computer, which is a network layer process.

6. `Data Link`-> The “Data-Link layer,” is responsible for maintaining and terminating the established connection between the network devices over the network channel.

The Data-Link Layer has two sublayers:

The first is the `“medium access control,”` which uses the MAC addresses from the network devices to transmit data between them.

The second layer is the `“logical link layer,”` which identifies, checks flow control, and performs the error check for the transmitted data.

`How it works`

To begin with, the network layer will share the data packets with the data-link layer.

The data-link layer handles these data packets by integrating them with the frame structure. The frame acts as a header for the data packet,and it contains the information about the destination address, sender address, and other related services.

The final data format in the data-link layer is known as the data frame, which is then transmitted to the physical layer of the OSI Model.

7. `Physical Layer:`-> Physical layer in the OSI model plays the role of interacting with actual hardware and signaling mechanism. Physical layer is the only layer of OSI network model which actually deals with the physical connectivity of two different stations. This layer defines the hardware equipment, cabling, wiring, frequencies, pulses used to represent binary signals etc.

The physical layer converts the data frame received from the data link layer into bits, i.e., in terms of ones and zeros. It maintains the data quality by implementing the required protocols on different network modes and maintaining the bit rate through data transfer using a wired or wireless medium.
