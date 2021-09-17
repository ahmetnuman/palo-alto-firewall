#### Security Policy with App-ID 

>> Ahmet Numan Aytemiz, 27 February 2021

---

#### Sample Security Rule to Access Internet

- Name : Internet-Access
- Source Zone : INSIDE
- Source Address : Any
- Destination Zone : OUTSIDE
- Destination Address : Any
- Application : web-browsing, ssl and dns
- Serivce/URL : application -default
- Allow : Log at Session Start

![Image](/img/security_rules.PNG)

#### Source NAT Rules

- Name : Internet-Access
- Source Zone : INSIDE
- Destination Zone : OUTSIDE
- Translation Type : Dynamic IP and Port
- Address Type : Translated Address (10.1.10.254)

![Image](/img/nat_rules.PNG)

#### Verify Internet Access from Client

![Image](/img/testconn.PNG)

#### Verify Traffic Logs

**Monitor >> Logs >> Traffic**

![Image](/img/traffic_logs.PNG)