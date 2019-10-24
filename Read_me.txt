
Read me file

1) Attached two files
	a) Sender3.java -- Acts as 1 Router 
	b)RoutingTable.java - A Routint table for a single router

2) Need to copy same sender3.java and RoutingTable.java (No need of any change) on all 11 machines.
3) Need to compile both the java files.
4) Need to run sender3.java
5) Need to enter Command line arguments with Multicast address, Port number and Rover id
	
	1) Multicast address - 224.0.0.3
	2) Port Number - 520
	3)Rover Id - 2

	eg. Sender3.java 224.0.0.3 520 2

6) The sender and receiver thread are running in While(True) loop, and will keep sending the packets.
7) Routing table will be printed only in case of change.
8)The packet received from self, will never be decoded and hence only once the initial douting table with self information
will be printed. 