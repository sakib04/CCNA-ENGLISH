# Network
A network is a system that connects two or more computers or devices, enabling them to share information and resources. Through a network, devices can communicate with each other and exchange data.

The main purposes of a network are:
- **Data Sharing**: Sharing data, files, software, etc., between different devices.
- **Resource Sharing**: Sharing resources like printers, scanners, hard disks, etc.
- **Communication**: Communication through emails, messaging, video conferencing, etc.
- **Internet Access**: Enabling internet usage.
Networks can be of different types, such as:

- **LAN** (Local Area Network): A network used in smaller areas, such as within an office or home, connecting computers.
- **WAN** (Wide Area Network): A network used over large areas, such as the connection between two cities or countries.
- **MAN** (Metropolitan Area Network): A network used within a city or a part of a city.
- **PAN** (Personal Area Network): A small network, such as a Bluetooth or Wi-Fi connection between two devices.

Network components include:
- Router
- Switch
- Hub
- Modem
- Cables, which facilitate the transfer of data within the network. A network can be part of larger systems like the internet or intranet.

# Network Cable

An RJ45 connector is what you would plug into any laptop, as this interface has been standardized, and various vendors have agreed to create devices according to this specification or standard, making life much easier. In the old days, vendors used to work according to their own preferences. They would create their own protocols and specifications, which were not good for customers. It was great for the vendor because if we bought their equipment, we would be locked into that vendor’s ecosystem.

Cisco started in 1984, and like any company, it had its share of odd controversies. They claim to have invented the router, which became their reputation: "We invented the router." However, if you type it into Google, you’ll see a sixty-year-old person saying, "No, I invented the router, and Cisco stole it." Anyway, it might be true. Perhaps that sixty-year-old person did invent the router and Cisco stole it. But undeniably, Cisco took that idea and popularized it worldwide. They massively developed it. Therefore, Cisco's reputation is based on creating the fundamental routers for today’s networks. Today, Cisco is undoubtedly the industry leader in stable networking equipment. A large part of the world’s network infrastructure is related to their name, and they are known for their reliability.


Let’s assume we have an office in New York with a PC, a server, and a printer that need to communicate with each other. For this, I will install a network switch and connect the devices to the switch using Ethernet cables. The switch will look something like this. The switch is the device that facilitates the connection for my Local Area Network (LAN). In the New York office, I might also have a laptop connected wirelessly. I can send a file from one person to another, store it on a file server, or use a shared printer, so no one needs to buy their own inkjet printer, which is very difficult to support. All such communications happen through the switch. Now, all my devices in New York can talk to each other. I’ve created a local area network, which is a network that connects devices in a small area like an office or university campus.

However, I don’t want all my devices in the office to just talk to each other; they will also want to communicate with other devices on the internet. For that, I will use a router, which can make advanced routing decisions to direct traffic between different parts of the network. This is how the router works, and it would look like this. Additionally, hackers or other malicious actors could try to attack the network, so I will set up a firewall to keep the different parts of our network safe from each other.

Now, the New York office's local area network is connected to the internet. But in a large company, there’s not just one office. Let’s say we also have an office in Boston, with similar devices and a local area network. We need to connect the New York and Boston offices so that the devices in both offices can communicate. I could securely communicate via the internet, but another option is to establish a dedicated connection between the routers in the two offices, which would provide us with a Wide Area Network (WAN) connection between the two offices.

The main purpose of networking is to establish connections between different devices. Key features of a network include topology, which determines how devices are connected, and network speed, which typically increases with higher costs. Other important network features include security, where firewalls, routers, and switches play critical roles, as well as ensuring availability by doubling components to avoid single points of failure. Scalability and reliability are also important, as the network must grow easily and work consistently.

Ultimately, although not immediately, people will one day say, "We need to communicate outside our organization." This is where the router comes into play. A router allows communication beyond your local area network (LAN) to a wide-area network (WAN) or a larger network. Essentially, the router marks the boundary between your network and another network. It also typically provides a security boundary, but it limits your traffic as well. So, when I send all types of communications here, we may experience an information flood. We’ll discuss various types of messages, but you might notice broadcast messages spreading throughout the entire company and leaking to other places. But it won't scale if every broadcast leaks outside the company, and everyone starts to see each other’s traffic. This is why the router creates a boundary.

Now, we can add some features that a router should support, such as security. You know, this is a crucial task, but it’s not mandatory. It’s just a boundary. I think a router provides a service called Network Address Translation (NAT), which translates your network’s IP addressing into internet addressing. This is a great feature, and almost 99% of routers support it, but it’s not mandatory. So, what does a router do? It creates a boundary between your network and another network, between your world and the rest of the world.





