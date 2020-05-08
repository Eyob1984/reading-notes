# Reading-Notes

                        ** Class-17-reading-TCP Server**

#### What do the layers in the OSI and TCP/IP models represent?

* *OSI model* is a generic model that is based upon functionalities of each layer. *TCP/IP* model is a protocol-oriented standard. ... *OSI model* gives guidelines on how communication needs to be done, while TCP/IP protocols layout standards on which the Internet was developed. So, *TCP/IP* is a more practical model.

#### What is the benefit of transforming data into packets?

* Packets are about one kilobyte in size, so that they’re easy to send over the internet.

#### UDP is often referrered to as a connectionless protocol. Why is this?

* Because UDP are not secured as compared TCP. When transferring data it doesn’t establish a strong secure connection between the sending server and the receiving server

#### Can a socket server application have multiple socket connections? Can a socket connection application be connected to multiple socket servers? Can an application be both a socket server and a socket connection?

* On the TCP level the tuple (source ip, source port, destination ip, destination port) must be unique for each simultaneous connection. That means a single client cannot open more than 65535 simultaneous connections to a server. But a server can (theoretically) server 65535 simultaneous connections per client.


[reference 1](https://www.tutorialspoint.com/OSI-vs-TCP-IP-Reference-Model)

[reference 2](https://serverfault.com/questions/533611/how-do-high-traffic-sites-service-more-than-65535-tcp-connections)

[home](https://eyob1984.github.io/reading-notes/)




