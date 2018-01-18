Layers in the OSI Model
---

># physical Layer
> moving individual bits from on (node) to the next
> - Physical characteristics of interfaces and media
> - Representation of bits
> - Data rate(transmissionrate).
> - Synchronization of bits
>   : the sender and the receiver clocks must be synchronized.
> - Line configuration
> - Physical topology
>   : how devices are connected to make a network.
>   : mesh topoloby, star topology, ring topology, bus topology
> - Transmission mode
>   : simplex, half-duplex, or full-duplex.

***

># Data Link Layer
> 
> - Framing
>  : make data manageable data units(frame)
> - Physical addressing
> - Flow control
> - Error control
>  : detect and retransmit damaged or lost frames.
> - Access control

***

># Network layer
> the source-to-destination delivery of a packet. The layer is often needed to transmit data to other link not same link.
> - Logical addressing
> - Routing
>   : On a large network or internetworks, the connecting devices route or switch the packets to their final destination. One of the functions of network layer is to porvide this mechanism.

***

># Transport Layer
> Process-to-process delivery. 
> ensures that the whole message arrives intact and in order.
> - Service-point addressing
>   : port address(deliver a whole message to right process(program)).
> - Segmentation adn reassembly.
> - connection control
> - Flow control
> - Error control


***

># Session Layer
> the network dialog controller. It establishes, maintains, and synchronizes the interaction between communicating systems.
> - Dialog control
>   : It allows the communication to take place in either half-duplex or full-duplex mode.

> - Synchronization.
>   : to add check points(synchronization points)
>   : to prevent overhead by resending some damaged data.


***

># Presentation Layer
> - Translation
>   : interoperability between different encoding methods.
> - Encryption
> - Compression


***

># Application Layer
> enables the user to access the network.
> - Network virtual terminal
> - File tranfer, access, and maangement(FTAM)
> - E-mail services.
> - Directory services.


