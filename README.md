# WebRTC

This repository works as test for learning WebRTC. Also taking notes and describe how does it work.

## Idea

To connect a `clientA` with `clientB` using WebRTC the only necessary action is that each client know the direction of the other client, this action is usually done by a server but it also may be done sending this info by other message service.

As usually, a middle server send the info to communicate between clients to start the communication between them. The protocol used to sen others info is `SDP`.

The info sended is the `ip` address and the `port` where is listening of each client.

To send info between clients, they will use the `UDP` protocol, insetad of `TCP` protocol due its speed when sending packages
