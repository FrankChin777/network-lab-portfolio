# Frank Chin — Network Lab Portfolio

Home lab built on Proxmox + Cisco CML targeting CCNA certification.
Target roles: Tier 1 NOC, Junior Network Engineer, MSP Support Engineer.

## Labs

### School Campus Network — Westside Community University
- 20-node CML topology across 10 campus buildings
- VLANs: MGMT, FACULTY, STUDENT, SERVERS, SECURITY
- 802.1X port authentication via FreeRADIUS
- OSPF, HSRP, LACP EtherChannel, L3 switching
- Automated with Ansible cisco.ios across all 10 access switches
- Status: In Progress

### Bank Network — Simple Local Bank
- PCI-DSS focused security design
- ASAv firewall, TACACS+, ACLs, port security
- Status: In Progress

### Game Studio Network — Frankie's Game Studio
- Dual-ISP redundancy, VRRP load balancers, DMZ
- Status: In Progress

## Tools
- Cisco CML Personal (20-node license) on Proxmox VE
- Ansible 2.18 with cisco.ios collection
- Jira for change management (senditsp.atlassian.net)
- GitHub for version-controlled config storage

## Certifications
- CompTIA Network+ (Completed)
- Cisco CCNA (In Progress)
