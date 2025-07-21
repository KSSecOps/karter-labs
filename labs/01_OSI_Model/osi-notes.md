# OSI_model Notes
### Layer 1 : Physical

- Layer one deals with the physical hardware that is used to transfer bits

- Bits are also known as raw data

- Examples of media/medium which is the hardware used to transfer this data are copper wires and fiber-optic cables

- there are different ways to transfer this data which includes Optical signal (light), electrical signals ( electricity), and Wireless signals such as infared and radio waves


### Layer 2 : Data link

- Layer 2 or the data link layer involves the communication between devices on the same local network ( LAN) 

- Each device on the LAN is given a MAC address to differentiate each device

- Switches are a common hardware utilized at this layer 

- each device's MAC address is mapped to a port 

- When data is sent in,  the switch will look at which port it needs to forward the data to 

### Layer 3: Network

 - This layer is all about communication between different networks

 - Routers are present at this layer to route data packets and find the best path for them to travel across networks

 - Each device on the network is assigned a different IP through Dynamic Host Configuration Protocol ( DHCP)

 - IP address are used to identify a device's location on a network

- This layer also handles packet fragmentation and reassembly

- Uses tools such as ping to determine whether or not a device is reachable on a network

### Layer 4: Transport

- This layer is all about ensuring the data gets to where it needs to go

- There are typically two common transport methods known as TCP and UDP

- UDP is faster and connectionless, however, it has the downside of being less reliable

- TCP is typically slower, but in return is more reliable at ensuring data gets to where it needs to be

### Layer 5: Session

- This layer deals with terminating and establishing sessions as its main function

- It is responsible for determining who is sending and receiving data

- It controls dialogue and the two main types of dialogue are half-duplex and Full-Duplex

- Half-duplex allows for only one device to send data at a time

- Full-Duplex allows for both devices to send and receive data at the same time

- this layer also is responsible for session recovery it instances of crashing or errors 

### Layer 6: Presentation 

- Layer 6 deals with all of the formatting of data and files 

- It is responsible for processes such as compression, Decryption, and encryption

- Some format types include JPEG, PNG, mp4, and mp3 files

- Encryption is the act of converting data into code to prevent unwanted or unauthorized access

- Decryption is the opposite and is used to convert that encrypted data back into its original form

### Layer 7 : Application 

- This is where the user interacts

- It manages high-level protocols such as HTTP, DNS, and FTP

- It is resposible for for providing network services to applications

- HTTP is used to access broswing websites online

- DNS is used to convert the names of website ( url) into an IP so that computers can locate each other

- FTP stands for file transfer protocol. It allows you to download and upload files

  

