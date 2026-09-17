1. What is Networking?
Networking is the practice of connecting two or more computing devices together using cables or wireless signals to share data, files, and resources (like the internet or printers).

2. LAN, WAN, and the Internet

LAN (Local Area Network): A network confined to a small geographic area, such as a single home, office room, or school lab. It offers high data transfer speeds.

WAN (Wide Area Network): A network that spans a large geographical area, connecting cities, states, or countries. It often connects multiple LANs together.

Internet: The largest public WAN on earth. It is a globally connected system of millions of private, public, academic, and government computer networks.

3. What is the OSI Model?
The OSI (Open Systems Interconnection) model is a conceptual framework created by the ISO. It standardizes how computer systems transmit data over a network by breaking the communication process down into 7 independent layers.

4. The 7 Layers of the OSI Model

Layer 7 - Application: Interfaces directly with user applications (HTTP, HTTPS, FTP, SSH).

Layer 6 - Presentation: Handles data formatting, encryption, and compression (SSL/TLS, JSON, JPEG).

Layer 5 - Session: Establishes, maintains, and terminates communication sessions between applications.

Layer 4 - Transport: Manages end-to-end communication, error recovery, and flow control (TCP, UDP).

Layer 3 - Network: Routes packets across different networks using logical addresses (IPv4, IPv6, ICMP, Routers).

Layer 2 - Data Link: Transmits data frames between devices on the same physical link using MAC addresses (Switches, Ethernet).

Layer 1 - Physical: Transmits raw unstructured bits (0s and 1s) over physical media like cables, radio waves, or optical fiber.

5. What is the TCP/IP Model?
The TCP/IP model is the practical, real-world networking suite that powers the modern internet. Unlike the conceptual 7-layer OSI model, it groups networking tasks into 4 streamlined layers: Application, Transport, Internet, and Network Access.

6. Difference between OSI and TCP/IP

Feature	OSI Model	TCP/IP Model
Nature	Theoretical reference model	Practical, implementation-oriented model
Number of Layers	7 Layers	4 Layers
Approach	Vertical strict separation of concerns	Flexible and protocol-centric
Usage	Used for teaching and conceptual design	Powers the modern Internet
7. What is an IP Address?
An IP (Internet Protocol) address is a unique numerical identifier assigned to every device on a network. It acts like a digital home address, allowing devices to locate each other and route data accurately across the network.

8. What is DNS?
DNS (Domain Name System) functions as the address book of the internet. It translates human-friendly domain names (like google.com) into computer-readable IP addresses (like 142.250.182.206) so browsers can fetch web pages.

9. What is ICMP?
ICMP (Internet Control Message Protocol) is a network-layer protocol used by network devices to send error messages and operational diagnostics. It does not carry user data; instead, diagnostic commands like ping and traceroute rely on ICMP to evaluate connectivity and calculate latency.

10. Why is Networking Important in DevOps?

Container & Pod Communication: Microservices inside Docker containers or Kubernetes pods need internal networking (ClusterIP, Ingress, CNI) to communicate.

Cloud Infrastructure: Provisioning virtual infrastructure requires configuring VPCs, subnets, routing tables, and internet gateways.

Security & Access Control: Securing CI/CD pipelines and production clusters requires setting up firewalls, Network Security Groups (NSGs), and reverse proxies (NGINX).

High Availability & Routing: DevOps engineers design architectures using Load Balancers, CDN routing, and DNS failovers to prevent system downtime.
