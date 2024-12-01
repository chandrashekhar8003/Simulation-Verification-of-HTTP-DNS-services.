# Simulation and Verification of HTTP and DNS Services in a Secured Network Environment

## Overview
This project mainly focuses on designing, simulating, and verifying a secure network topology in cisco packet tracer environment that includes HTTP and DNS services. The implementation ensures the efficient communication, data integrity, and robust security through HTTPS and access control mechanisms.

## Features
**Network Topology**: Two interconnected LANs with routers(1841), switches, and servers(HTTP,DNS).
**HTTP Server**: Provides web services with HTTPS for encrypted communication.
**DNS Server**: Resolves domain names into IP addresses for seamless connectivity.
**TLS Implementation**: Ensures secure communication via HTTPS.
**Access Control**: Enforces traffic regulation through ACLs to allow secure protocols while blocking unencrypted traffic.

## Objectives
1. Build a scalable and functional network infrastructure.
2. Configure and test essential services like HTTP and DNS.
3. Verify secure and efficient data flow using network simulation tools we have used here is cisco packet tracer.

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
3. Test connectivity and verify encrypted communication.

## License
This project is open-source under the [MIT License](LICENSE).

## Contact
For inquiries or contributions, feel free to reach out via GitHub or email(chandrashekarmv18@gmail.com).

