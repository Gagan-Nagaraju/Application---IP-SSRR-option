# Application---IP-SSRR-option
Development of an application to walk around an ordered list of nodes similar to IP SSRR option

Authors: Gagan Nagaraju & Harishkumar Katagal
CSE 533 - Assignment 4
********************************************************************************************

• Developed an application using raw IP sockets to walk around an ordered list of nodes similar to the IP SSRR option.
At each node, the application pings the preceding node in the tour using its Ethernet address which is obtained using the ARP module.
• After the tour finishes, the group of nodes visited during the tour exchange multicast messages.

#USER DOCUMENTATION:

Following are the files that contain the source codes for the assignment 4.
arp_hkatagal.c
arp_hkatagal.h
get_hw_addrs.c
hw_addrs.h
tour_hkatagal.c
tour_hkatagal.h

To compile and generate executables use the "Makefile" and issue a "make". This will generate the *.o and the executable files: tour_hkatagal arp_hkatagal.

Run the executable on all the nodes and specify the tour at the source node.

The ping messages, multicast messages and other appropriate messages are displayed on the terminal.
***********************************************************************************************