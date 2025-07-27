# Lab Notes

### Lab Overview
- The goal of this lab was to take previous knowledge and apply it to Wireshark by actually capturing packets and interpreting the meaning of them

### What I learned 
- I learned how to use Wireshark to cpature packets and view them. I learned how to view and see the source and destination MAC and IP addresses and noticed how they are reversed depending on if it is a request or a reply. I learned more about how NIC and routers have different uses when being used as capture points for packet traffic. Routers are better for viewing the traffic of multiple devices while NIC as a capture point is good for monitoring the traffic of one device.

### What I struggled with
-  I struggled with capturing the reply and request packets at first. At first glance the sources and destinations were the same and not reversed in the pcap files, but it was due to me saving all of the packets in the request file rather than just the request I wanted. This was because I used "save as" instead of exporting it and when I did I had a setting that was called "All files" instead of only the one I had selected. I figured this out after sometime andused this to see differences in the soruces and destinations of requests and replies.

### Note Structure
- I put picture in my notes as well as labeled all of the field sections with their assigned number ( IP address, MAC address, etc.). I also created bullet points hilighting important info and a few sentences describing the different uses for different capture points
