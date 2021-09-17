#### Palo Alto Firewall Notes

> Ahmet Numan Aytemiz, 28.02.2021

---

#### 1. Palo Alto Firewall Getting Started

- Understanding firewall basics and Palo Alto's Advantages
- Initializing the Palo Alto
- Administering the firewall
- Deploying Palo Alto in layer 3 mode
- Processing Palo Alto Traffic
- Seeting up security rules to shape traffic

![Image](/img/palo_lab.png)


#### Introduction to Firewall and Firewall History

> Ahmet Numan Aytemiz, 9 February 2021

---

#### What is a firewall

- Filters incoming and outgoing traffic
- Allow only desired traffic
- Based on defined set of rules in a sequence
- If-Then statement

  - #### If-Then Statement

      - if packet is RED then ALLOW
      - if packet is BLACK then DENY
      - if packet is white then ALLOW  

#### Packet Filtering Firewalls (Stateless Firewall (Legacy))

- Original Firewall 
- Source and Destination Address or Ports
- Access Control Lists (ACL)
- In Stateless Firewalls each interfaces has their own rules

Rule 1 :
   - Allow Traffic From 10.17.5.0/24 going to 192.168.0.0/24 using HTTPS
Rule 2 : 
   - Allow Traffic from 10.17.5.0/24 going to 172.16.85.0/24 using FTP

Src.IP : 10.17.5.20 , Dst.IP : 172.16.85.116 , Port: 443 ----> what happed this packet according to above rules ?
Src.IP : 10.17.5.20 , Dst.IP : 192.168.0.96 , Port: 443 ----> what happed this packet according to above rules ?

#### Statefull Firewall 

- Still uses layer 3 and layer 4 acls
- Dynamically creates rules to allow return traffic by monitoring source and destination ports
- Maintains information in an state table
- Allows for hess administrative overhead

#### Next Generation Firewalls

- Ability to look at the application layer (layer 7)
- Decrypt Traffic
- URL filtering
- Integrate with other systems on the network such as active directory
- IDS/IPS tecnolgy
- Terminate VPN Client's
- IPSEC VPN's
- Cloud Based Malware Protection
- SD-WAN





