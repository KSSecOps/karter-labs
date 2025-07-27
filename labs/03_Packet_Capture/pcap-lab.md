# Packet capture notes

## Request 
**Source MAC address:** 10:7c:61:1d:6a:a0

**Destination MAC address:** e8:9c:25:2a:3f:dc

**Source IP address:** 23.48.203.101

**Destination IP address:** 192.168.50.64

**Protocol:** ICMP (1)

**TTL:** 128

<img width="1439" height="1194" alt="image" src="https://github.com/user-attachments/assets/9bd51f43-3e28-449d-ad62-019d799290ed" />

## Reply
**Source MAC address:** e8:9c:25:2a:3f:dc

**Destination MAC address:** 10:7c:61:1d:6a:a0

**Source IP address:** 192.168.50.64

**Destination IP address:** 23.48.203.101

**Protocol:** ICMP (1)

**TTL:** 64

<img width="2023" height="1581" alt="image" src="https://github.com/user-attachments/assets/7c9e25a5-3a49-4827-9fdd-64f2f03e8484" />


## Capture points
Router - If I were to capture the packet traffic at the router it would be helpful in viewing traffic coming in from external sources and other networks. It allows you to see traffic from all the devices on the network as well which can be useful It can be extremely useful in monitoring outside threats in situations where security is priority. 

NIC - If I were to capture packets here I would be able to monitor the traffic coming into the the specific device I am currently looking at. Only difference is I can't view packets going into other devices


## Packet Understanding
- The  Source and Destination MAC addresses are on layer 2 (Data link)  and tell which  devices on the same local network (LAN) are communicating with each other

- Similarly to the MAC addresses, the source and destination IP addresses display what devices are coomunicating at the third layer ( Network layer)

- A packet request is a device asking another device to recieve or obtain information

- contrary to a request, a reply is when the device sends the data to the device that requested info

- Protocols exists and function to determine how a packet is interpreted through things such as ICMP, TCP, and UDP

- TTL or Time to live is the number of hops a packet can last or travel for. This is used to prevent them from endlessly travel in a network loop


