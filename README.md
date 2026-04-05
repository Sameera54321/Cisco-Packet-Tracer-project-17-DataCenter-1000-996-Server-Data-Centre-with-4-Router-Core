# Cisco-Packet-Tracer-project-17-DataCenter-1000-996-Server-Data-Centre-with-4-Router-Core
I’m thrilled to share my latest networking project – DataCenter‑1000 – a Cisco Packet Tracer simulation that models a large data centre containing 996 servers (Server0 … Server995) interconnected via four core routers (Router1 – Router4).

![image alt](https://github.com/Sameera54321/Cisco-Packet-Tracer-project-17-DataCenter-1000-996-Server-Data-Centre-with-4-Router-Core/blob/main/4.jpg?raw=true)

## 📌 Summary

### DataCenter‑1000 is a high‑density data centre simulation built with Cisco Packet Tracer. It consists of:

    4 core routers (Router1, Router2, Router3, Router4) – providing redundant, high‑speed connectivity

    996 server nodes (Server0 through Server995) – representing a large server farm

    Total 1000 network devices in a single simulation file

### The project explores:

    Dynamic routing (OSPF or EIGRP) across a multi‑router core with many attached server subnets

    IP address planning for 996 servers (e.g., using /24 subnets per rack or VLSM)

    VLAN segmentation to isolate server groups (web, database, storage, etc.)

    Redundancy and load balancing (e.g., equal‑cost multipath – ECMP)

    Basic security (ACLs, port security) and network services (DHCP, DNS) if deployed on some servers

## ✨ Features

    ✅ 996 servers – each configurable with static or DHCP addresses

    ✅ 4 core routers – full mesh or partial mesh for redundancy

    ✅ Dynamic routing – OSPF (multi‑area) or EIGRP for automatic route exchange

    ✅ Scalability testing – routing table size, convergence time, simulated server traffic

    ✅ VLAN segmentation – logical grouping of servers (e.g., VLAN 100–200)

    ✅ Redundancy – multiple paths between any two servers

    ✅ Full Packet Tracer file (.pkt) – ready to open and experiment

    ✅ Documentation – IP addressing plan, routing protocol design, VLAN mapping, router configs

## 🛠️ Built With

    Cisco Packet Tracer – version 8.x (or later)

    CLI – router and server configuration

    (Optional) Python – if used to generate repetitive server configurations or IP lists

## 🤝 Contributing

Contributions are welcome! If you want to extend or improve the simulation:

    Fork the repository.

    Add new features – e.g., layer‑2 switches between routers and servers, load balancers, firewall appliances, or IPv6.

    Optimise routing protocol settings (summarisation, stub areas, etc.).

    Implement server services (HTTP, DNS, DHCP, FTP) on selected servers.

    Update the documentation with your changes.

    Open a pull request with a clear description.

## 📜 License

Distributed under the MIT License. See the LICENSE file for more information.
You are free to use, modify, and share this project for educational purposes.
