# Lab 2 notes

### Lab overview
This lab was used to create a visual chart highliting the encapsulation process while understanding the differences in structure and in purpose of frames, packets, and segements.


### What I learned 
Frames, packets, and segments are all different and have different roles that make them all important in the process of sending and receiving data. The encapsulation process is the process of data being engulfed to be turned from a segment to a packet to a frame. Segments are found in the transport layer ( layer 4) and are used to organize data and split it into manageable pieces. For example when watching a video the segementing chooses how the video data is split up. As far as structure goes it has a TCP/UDP header and the payload ( data). After Segments become encapsulated, they turn into packets. Packets are at the 3rd layer( Network) and the main purpose is to route between different networks. For example when messaging someone far away the packets hop between networks. They typically have a smaller size and are broken down. Structure for packets is the IP header and the previous header and a payload. Frames ( layer 2) are the last in the encapsulation process if you're the one sending data and its structure is the Frame header and the previous headers, a payload, and a trailer. Trailers are typically in frames and used for error checking through methods such as FCS. Frames are used for transferring between two connected devices and they handle the physical transmission of data. For example when printing on your home wifi the frames handle the transmission from your laptop to your printer.  I learned how MTU and fragmentation are used to help networks efficiently transfer data and how MTU is in place to prevent fragmentation from happening often as this can affect memory allocation. 

### Issues/struggles
I struggled a little bit with differentiating the difference between and packet and a frame, more specifically there purpose/use. Segments stood out as when you segment things you break them into pieces so that made sense, however, with the frames and packets the main difference is that a packet is used for transmission between two different routers while frames are between two devices on the same network. It made sense later though as I tied packets to IP's which deal with differing networks and frames with MAC addresses which are associated with same local network (LAN) 

### Note structure
I structure my notes into bullet point about each of the different data formats and created a summary hilighting the important pieces of what I learned in this lab
