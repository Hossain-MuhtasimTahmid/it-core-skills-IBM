# Networking
* When many groups of devices are connected to each other in a way that they can share data and resources between each other, they form a network.
  * Modem is required to talk to the Internet and a Router is required to help manage the traffic.
<img width="570" height="180" alt="networknotebyibm" src="https://github.com/user-attachments/assets/f7a0a87d-1e2b-4bad-9dfa-fc093bf8bf61" />

* Data is transferred across networks in packets. --> A large file (like a video, which can be many gigabytes) can be broken down into very small chunks called data packets. The network can transfer each chunk separately and networking resources can reassemble them on the receiving side.
* Wireless fidelity (wifi) networks transmit data using radio signals.
* Radio technology. A radio sends and receives information in electromagnetic sound waves.
* Router(connected to the Internet Service Provider & sends data)-> home or school network.-->
  * A box that manages network traffic between the device and the internet.
* Network Interface Controller (NIC)-> wired network (hardware)->to send and receive data to the connected computer.
* Mobile Phone-> Radio hardware -> sends and receives data from cell towers.
* Modem-> Modulate + Demodulate-> Modulate is sending/transmitting & demodulate is receiving/demodulating. -->
  * Computer part that conncets to an internet service and it might be an external box or an internal card.
* Gateway-> A box that contains both modem and router.
* Internet servers (Data)-> Modem -> Router -> The devices
<img width="681" height="328" alt="datasending receiving" src="https://github.com/user-attachments/assets/520e50c4-0978-46fc-9648-b621c7261dc9" />

* Media Access Control (MAC)-> Globally unique and cannot be same (ex: passport number)
* Internet Protocol (IP)-> Not unique-> indentifies devices on a perticular network.
<img width="536" height="357" alt="mac ipcomparison" src="https://github.com/user-attachments/assets/b3d66878-4697-4c0b-9238-b48e6e67f0f0" />

* QUIZ 1-->
  * The large data gets broken down into small packets, and each packet is sent separately and then reassembled on the receiving side.
  * When you send a message from your home, data travels to your router, which routes the message to the internet and then to the routers of the people in your group.
  * On a private network like a home, business, or school network, the router assigns all the devices on that network an individual IP address that is associated with the device’s MAC address.
<img width="855" height="378" alt="networkingquiz1" src="https://github.com/user-attachments/assets/e052df12-3998-4a89-974c-a0c3dd21cb83" />

* PANs- Personal Area Network, from the name itself I can undersatnd that it has to be used on a personal level, the devices need to be in the same place.
* LANs- Local Area Network, mainly used by corporations or at home or at shops or cafes' to have private network connection, so no random person can access without permission.
* WANs- Wide Area Network, the internet is called the open WAN because it covers the world and devices don't need permission to access it, but some networks which require security credentials are called closed networks.
* VPNs- Virtual Private Networks, it works like a tunnel from one LAN to another so sometines people working remotely can use vpn to access to private LANs of their company or schools.
* QUIZ 2-->
  * A local area network (LAN) the secure way to let some people in and keep others out.
  * A personal area network (PAN) is ideal for transferring a single image to a nearby device.
  * Routers transmit traffic from one side of a network or device to the other side of the network or device.
<img width="837" height="382" alt="quiz2networkbasics" src="https://github.com/user-attachments/assets/c75ce934-3f8c-45a5-ad89-e095629cdfa7" />

* Domain Name System (DNS)-> DNS allows us to access websites using easy-to-remember names instead of numeric IP addresses.
* Transmission Control Protocol (TCP)-> TCP/IP handles data
  * Data is broken up into packets and sent over the internet in chunks and reassembled at the destination. The technology that enables this type of transmission is called TCP/IP.
  * Protocol: A protocol is a set of rules or a procedure for how something is be done.
 * Metadata ->is essential for ensuring that all the data arrives at the proper destination and that the receiving end knows what to do with it.
* In IP addresses-> In 192.168.1.10, 192.168.1 is the network part and 10 is the device (host) part.
<img width="790" height="384" alt="dns" src="https://github.com/user-attachments/assets/878b156f-a4a2-479e-9499-91892642d5b9" />
<img width="535" height="296" alt="domaintypes" src="https://github.com/user-attachments/assets/11333241-d584-417e-af7a-933c94edb4e6" />

* QUIZ 3-->
  * The TCP/IP protocols define how data on a network should be broken up, how it should be transmitted from network to network, and the structure of packets.
  * The DNS is like a big address book that matches domain names with IP addresses.
  * Domains are groupings of networks, and in www.ibm.com the IBM name is considered a subdomain of com.
  * The protocols that TCP/IP uses to enable reliable data transfer by defining how data on a network is broken up, how it is transmitted, and how it is structured.
<img width="854" height="381" alt="networkingquiz3" src="https://github.com/user-attachments/assets/6b578e66-bbbb-49e6-9f6f-615eae048d19" />

* Firmware-> Operating system of routers and modems.
* Password manager. A password manager is a software program for managing, creating, storing, and updating your passwords. A password manager helps you to log in to websites securely.
* Threat actor. A threat actor is someone like a cybercriminal or an organization that is responsible for a threat or malicious impact on the security of an organization or an individual system user.
* Phishing attacks. These types of emails try to make you select a link, call a number, or download a file in order to extract personal information.
* Heuristics: You hover over or select the sender’s name to reveal the actual sender’s email address.
  * For example, if you get an email that appears to be from IBM Support, you can hover over the sender’s address. If it shows a personal email address or a non-IBM address, you will be able to tell the email is not actually from IBM support and assume it is a scam.
* QUIZ 4-->
  * Two-factor authentication requires that people enter a code, pick an answer from a list, respond to a phone call, or answer a question in order to confirm their identity.
  * Keeping firmware up to date can help plug security holes and help the hardware to perform better to prevent certain types of attacks.
<img width="847" height="381" alt="networkingquiz4" src="https://github.com/user-attachments/assets/3faadbdf-70b0-4ad6-9e93-a845e19f3e75" />

* All hardware has a special identification (ID) called a media access control (MAC) address.
* Type CMD in your searchbar and type "ipconfig/all" to find the physical address which is the MAC address of the device.
* Routers use subnets. ->Subnet. A subnet is an address for a network within a network. The subnet helps your router to sort and send information to its destination.
<img width="401" height="337" alt="howRouterWorks" src="https://github.com/user-attachments/assets/277bbfce-0912-4595-afc1-2ef5649a61ae" />

* Data is sent from the internet to your router, which is assigned a unique IP address.
 * Your router creates a subnet for your home network.
 * Your subnet ID is 192.168.1.
 * Each device within your subnet gets an IP address, also called the host ID, based off of your subnet ID.
 * The last number in the IP address is how the subnet identifies each device.
 * The IP address for your specific device is 192.168.1.10.
*QUIZ 5-->
<img width="852" height="381" alt="networkingquiz5" src="https://github.com/user-attachments/assets/9e140d86-2332-4056-ad2a-eaf450c51468" />

* QUIZ 6-->
  * An operating system is a type of system software that manages how the software installed on the device works with the device hardware.
  * A stateless application may be run entirely online in your browser.
  * A stateful application, like an operating system, contains all the information needed to make the application work in the memory of the device.
  * The web browser application is stateless because it processes the information as the information is received and renders the information as the information arrives.
<img width="842" height="381" alt="networkingquiz6" src="https://github.com/user-attachments/assets/dc0d0055-9220-4f3a-8160-9eed1d9a1e37" />

# Important summary
* Compression technology uses tokens to help networks transfer large amounts of data.
* Personal area networks (PANs) and local area networks (LANs) are private, while wide area networks (WANs) can be private or open.
* Media access control (MAC) addresses are unique and permanent.
* Devices can share internet protocol (IP) addresses.
* Domain name system (DNS) technology is like a big address book for IP addresses.
* Using a password manager and enabling two-factor authentication (2FA) are two ways to help protect you from security breaches.
<img width="839" height="379" alt="networkingfinalquiz" src="https://github.com/user-attachments/assets/ee8a815a-5f15-4fd3-b785-a309a1ef0209" />



