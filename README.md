
Project Description

We have implemented a reliable transport protocol over the UDP protocol. We refer to the reliable transport protocol as Simple Transport Protocol (STP). STP will include most (but not all) of the features that are described in TCP. Examples of these features include timeout, ACK, sequence number etc. Note that these features are commonly found in many transport protocols.  

we have implemented Simple Transport Protocol (STP), a piece of software that consists of a sender and receiver component that allows reliable unidirectional data transfer. STP includes some of the features of the TCP protocols.

STP has two separate programs: Sender and Receiver. we only have to implement unidirectional transfer of data from the Sender to the Receiver. Data segments will flow from Sender to Receiver while ACK segments will flow from Receiver to Sender. 

We are not using TCP sockets directly.

