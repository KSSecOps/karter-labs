# Packet Structure

### Bits

- Bits are the smallest unit of data and can only be ones or zeros

- These get converted to electircal, optical, or wireless signals ( infrared and radio waves)

- Bits are in the lowest layer known as the physical layer 

- All the structured data ( things such as headers and the payload) from layers above gets converted into bits so that the user can send out information

- Bits are carried across a medium such as fiber-optic cables or copper wiring

### Frames 

- Frames are located on the Data Link layer (layer 2) 

- They carry the frame header and encapsulates the two headers in the layers above known as the the IP header and the UDP/TCP header

-  Frames typically carry a trailer for error checking. One of the error checking methods used is known as Frame Check Sequence (FCS). 

- FCS generates a number based on the bits and compares it to the receiving end's data to determine if there was an error

### Packets 

- Packets are located on the Network layer ( layer 3 )

- Packets carry fewer headers than frames do because the layers below carry more for reliable delivery

-  Packets typically contain an IP header, do not have a trailer for error checking, and the TCP/UDP header.

-  Packets are typically smaller and are broken down to make routing more efficient 

- The main purpose of a packet is to route data across different networks

### Segments

- Segments are located in the Transport layer (Layer 4)

- Segmenting's main job is splitting data into easier to manage pieces

- It carries the TCP/UDP header, but none of the other headers as it has not been encapsulated

- It is typically used to organize data before it is sent to the recipient
   
### Maximum Transmission Unit (MTU) and Fragmentation 

- MTU is the maximum amount of data that can be transmitted by a frame or packet in a network

- This setting is important and ties into fragmentation. If a packet or frame exceeds the limit of a network fragmentation is used to break it down into smaller pieces

- Fragmentation is important but can have effects on network performance such as less efficient memory allocation

- IP fragmentation occurs at the Network layer (layer 3)

- Delays and packet loss can occur if fragments are lost

- MTU discovery is used to optimize transmission of data between networks

### Summary of Lab

Packets, frames, and segments are formatted units of data that carry a payload (data) over the network. They go through a process of encapsulation in which one layer engulfs another. For example at the Transport layer (layer 4) a segment gets ecapsulated to become a packet (layer 3 ) and the packet becomes engulfed to become a frame (layer 2). Frames carry and frame header, and typically have a trailer for error checking method such as FCS. As the encapsulation process goes down the layers, they add more headers, and continue to wrap in more data  After this the data gets converted into bits and sent out. If you were receiving info rather than sending it, the process is reversed and the bits are first turned into frames and so on until the data reaches the application layer ( layer 7 ) where the user can view the data. 
  
