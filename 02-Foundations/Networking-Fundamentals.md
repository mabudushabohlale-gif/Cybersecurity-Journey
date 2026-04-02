# 🛜Networking Fundamentals

## 📌Overview
This section covers the fundamentals of netwoking, including how devices communicate, how data is transferred and the key protocols used in modern networks.

___

## 🛜What is Networking?
Networking is the process by which devices are connected to communicate and exchange data with each other.

## 🧑‍💻Types of networks
**LAN**: Small network (Home, School, Office)

**WAN**: Large network connecting multiple LANS (Internet)

### 🔑Key points
- Networking allows devices to communicate with each other.
- Networking is sent and received in the form of packets.
- Devices in a network are called hosts.
- Networks can be local(LAN) or global(Internet).
- Communication relies on protocols like Domain Name System(DNS) and Hypertext Transfer Protocol(HTTP).

### 💻Examples
1. Your devies sends a request
2. Your request travels through the network using routers
3. The server receives the request
4. The server sends back a response to your device

**This is an example of devices communicating over a network.**

## 💻IP addresses and Octets
- An IP address identifies a device on a network
- IPv4: 4 Ockets separated by periods, e.g, '192.168.1.100'
- Each Ockets equal to 8 bits - total 32 Bits
- IP addresses can be **Static** (manually assigned) or **Dynamic** (assigned by DHCP)

___

## 💡Subnetting
- Devides a network into smaller networks called subnets
- Helps manage IP addresses efficiently
- Subnet mask shows which part is networks vs host

___

## 🔁ARP (Address Resolution Protoco)
- Maps an IP into a **MAC address**
- Ensures data reaches the correct device in a LAN
- Works automatically in the background

___

## ⚡DHCP (Dynamic Host Configuration Protocol)
- Assigns IP addresses automatically to devices.
- Follows **DORA** process.
  1. **Discover** - Devices ask for an IP
  2. **Offer** - Server offers and IP
  3. **Request** - Device requess that IP
  4. **Acknowledge** - Server confirms the assignment

  __

  ## 🔨Ping and connectivity
 - **Ping** tests connectivity between devices
 - Send ICMP packets and waits for a response
 - Example: 'ping 192.168.1.1' - Checks if the devices is reachable


___

##💻Examples
When you visit a website:

1. Your device gets an IP from DHCP
2. Sends a request through routers
3. Routers fowards packets using IP addressing
4. ARP Revolves around MAC addresses in local netwroks
5. Server responds - response follows best path back

___

### 🧠Analogy
Networking is like sending letters:
- IP = Street Address🏠
- MAC = Persons name👤
- Packets  = Letters📩
- Routers = Mail delivery routes🚚

___

## 🗨️ My understanding
Networking is how devices communicate using IP addresses, Subnets, Mac addressing and protocols. tools like ping help verify connectivity while DHCP and ARP automate mapping and addressing. Subnetting organizes networks efficiently, making communication faster and more secure.
