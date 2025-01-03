# Simulation and Verification of HTTP and DNS Services in a Secured Network Environment

## Overview
This project mainly focuses on designing, simulating, and verifying a secure network topology in cisco packet tracer environment that includes HTTP and DNS services. The implementation ensures the efficient communication, data integrity, and robust security through HTTPS and access control mechanisms.

## Features
**Network Topology**: Two interconnected LANs with routers(1841), switches, and servers(HTTP,DNS).
**HTTP Server**: Provides web services with HTTPS for encrypted communication.
**DNS Server**: Resolves domain names into IP addresses for seamless connectivity.
**TLS Implementation**: It Ensures secure communication via HTTPS.
**Access Control**: It Enforces traffic regulation through ACLs to allow secure protocols while blocking unencrypted traffic.

## Objectives
1. Build a scalable and functional network infrastructure.
2. Configure and test essential services like HTTP and DNS.
3. Verify secure and efficient data flow using network simulation tools we have used here is cisco packet tracer.

We have enhanced our previous network topology by adding new routers and servers for HTTP and DNS and configured all PCs, servers, and routers using coaxiale cables and used DCE for serial communication we have changed the hardware by inserting WIC-2T for router for establishing serial connection over network topology. DNS and HTTPS services were successfully verified through simulation, with screenshots showing the topology, configurations, message flows, and verification results. The process includes HTTP requests from PCs to the server, with responses traveling through switches and routers, displaying time taken. Firewall rules were implemented using ACL commands to regulate traffic. Key accomplishments include HTTPS with TLS encryption, DNS for domain resolution, and ACL-based traffic control. Challenges in service configuration and routing were addressed through systematic testing and troubleshooting.

## Components
**Routers**: Manage traffic between LANs.
**Switches**: Enable communication within the same LAN.
**HTTP Server**: Responds to web requests from client devices.
**DNS Server**: Resolves domain names to IP addresses.
**Client PCs**: Represent users sending HTTP and DNS requests.

## Simulation Details
- **HTTPS Communication**: Validated TLS encryption for secure web requests.
- **DNS Resolution**: Successfully resolved domain names, enabling seamless web access.
- **Firewall Implementation**: ACLs configured to enforce secure communication by permitting only HTTPS and DNS traffic while blocking HTTP and other unauthorized traffic.

## Challenges and Solutions
- **Challenge**: Correctly configuring DNS and HTTP services and resolving routing conflicts.
- **Solution**: Systematic testing, troubleshooting, and configuration.

## Results
- Successful simulation of secure network communication.
- Verified encrypted traffic on port 443 with blocked HTTP traffic on port 80.
- Displayed a custom webpage, demonstrating proper HTTP server functionality.

## Getting Started
To replicate the simulation:
1. Set up network topology using simulation tools like Cisco Packet Tracer
2. Configure the components:
   - Assign IP addresses.
   - Configure routers, switches, and ACLs.
   - Set up DNS and HTTP servers with TLS for HTTPS.
3. Test the connectivity and verify encrypted communication.

## License
This project is open-source under the [[MIT License](LICENSE)](https://github.com/chandrashekhar8003/Simulation-Verification-of-HTTP-DNS-services..git).

## Contact
For inquiries or contributions, feel free to reach out via GitHub or email(chandrashekarmv18@gmail.com).

