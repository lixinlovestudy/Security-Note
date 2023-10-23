# Security-Note
I made a mindmap to help review the concepts I learned in Security+

# This is a Markdown Format

# CompTIA Security+ Domains Breakdown

## 1. Attacks, Threats, and Vulnerabilities (24%)
   - **Network Attacks**
     - Common network attacks:
       - DoS (Denial of Service)
       - DDoS (Distributed Denial of Service)
       - Man-in-the-Middle attacks
       - SYN/ACK floods
       - Smurf attacks
     - Attack vectors:
       - IP spoofing
       - ARP spoofing
       - DNS spoofing
   - **Malware and Attacks**
     - Malware types:
       - Viruses
       - Worms
       - Trojans
       - Ransomware
     - Social engineering attacks:
       - Phishing
       - Spear-phishing
       - Vishing (voice phishing)
   - **Vulnerabilities and Weaknesses**
     - Common vulnerabilities:
       - Software vulnerabilities
       - Misconfigured settings
     - Attack surface reduction:
       - Hardening systems and applications
       - Patch management
       - Least privilege principle

## 2. Architecture and Design (21%)
   - **Network Design**
     - Secure network topologies:
       - Star topology
       - Mesh topology
       - Bus topology
     - DMZ (Demilitarized Zone):
       - Isolation of untrusted networks
       - Proxy servers in DMZ
     - VLANs (Virtual LANs):
       - Logical network segmentation
     - Segmentation:
       - Separating critical assets
   - **Security Components**
     - Firewalls:
       - Packet filtering firewalls
       - Stateful firewalls
     - Proxies:
       - Forward proxies
       - Reverse proxies
     - NIDS/NIPS (Network Intrusion Detection and Prevention Systems)
   - **Secure Protocols**
     - SSL/TLS and HTTPS:
       - Encrypting data in transit
       - Secure Sockets Layer (SSL) and Transport Layer Security (TLS)
     - IPsec (Internet Protocol Security) and VPNs:
       - Site-to-site VPNs
       - Remote access VPNs
   - **Secure Topologies**
     - Star, mesh, ring, bus topologies
     - Secure cloud and virtualization environments:
       - Cloud security models (IaaS, PaaS, SaaS)
       - Virtualization security considerations

## 3. Implementation (25%)
   - **Secure Network Configurations**
     - ACLs (Access Control Lists):
       - Controlling network traffic
     - NAT (Network Address Translation):
       - Hiding internal network structure
   - **Host Hardening**
     - OS and application hardening:
       - Disabling unnecessary services
       - Regular patching and updates
     - Patch management:
       - Vulnerability assessment
       - Patch deployment processes
   - **Implement Secure Protocols**
     - SSH (Secure Shell):
       - Secure remote access
     - SCP (Secure Copy Protocol):
       - Secure file transfers
     - SFTP (SSH File Transfer Protocol):
       - Secure FTP over SSH
   - **Wireless Security**
     - WPA3 (Wi-Fi Protected Access 3):
       - Stronger encryption
       - Simultaneous Authentication of Equals (SAE)
     - EAP-TLS (Extensible Authentication Protocol - Transport Layer Security):
       - Certificate-based authentication
     - Wireless encryption:
       - WPA2-Enterprise
       - Hidden SSIDs

## 4. Operations and Incident Response (16%)
   - **Monitoring Tools**
     - Log analysis:
       - Identifying security incidents
     - SIEM (Security Information and Event Management):
       - Real-time security event monitoring
   - **Incident Response**
     - Incident handling procedures:
       - Preparation, identification, containment, eradication, recovery, lessons learned
     - Forensics and evidence collection:
       - Legal and technical considerations
   - **Change and Patch Management**
     - Change control processes:
       - Risk assessment
       - Testing and validation
     - Patch management procedures:
       - Regular patching schedules
   - **Disaster Recovery**
     - Backup strategies:
       - Full, incremental, differential backups
     - Business continuity planning:
       - Continuity of operations in case of disasters

## 5. Governance, Risk, and Compliance (14%)
   - **Security Policies, Procedures, and Awareness**
     - Security policies and procedures:
       - Documenting security guidelines
       - Employee awareness training
     - User training and awareness programs:
       - Recognizing phishing attempts
       - Reporting incidents
   - **Risk Management**
     - Risk assessment and analysis:
       - Identifying and prioritizing risks
       - Quantitative and qualitative risk assessment
     - Risk mitigation strategies:
       - Transference, avoidance, acceptance, mitigation
   - **Business Impact Analysis**
     - BIA (Business Impact Analysis):
       - Identifying critical systems and processes
     - Impact assessment:
       - Downtime, data loss, financial implications
   - **Compliance and Frameworks**
     - Industry regulations:
       - HIPAA, GDPR, SOX, FISMA
     - Security frameworks:
       - NIST, ISO 27001, CIS Controls
