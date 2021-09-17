#### Palo Alto Admin Account Overview

> Ahmet Numan Aytemiz, 10 February 2021

---

#### Administrator Access

- Enough access without too much access
- Responsibilities are clearly defined
- Admin Roles Profiles : Audit Admin; Crypto Admin; Security Admin
    - **auditadmin**—The Audit Administrator is responsible for the regular review of the firewall’s audit data.
    - **cryptoadmin**—The Cryptographic Administrator is responsible for the configuration and maintenance of cryptographic elements related to the establishment of secure connections to the firewal
    - **securityadmin**—The Security Administrator is responsible for all other administrative tasks (such as creating Security policy) not addressed by the other two administrative roles.
- Admin Dynamic Roles :
    -   **Superuser** : Full access to the firewall, including defining new administrator accounts and virtual systems. You must have Superuser privileges to create an administrative user with Superuser privileges.
    -   **Superuser (read-only)** : Read-only access to the firewall.
    -   **Device administrator** : 	Full access to all firewall settings except for defining new accounts or virtual systems.
    -  **Device administrator (read-only)** : Read-only access to all firewall settings except password profiles (no access) and administrator accounts (only the logged in account is visible).
    - **Virtual system administrator** : Access to selected virtual systems on the firewall to create and manage specific aspects of virtual systems. A virtual system administrator doesn’t have access to network interfaces, VLANs, virtual wires, virtual routers, IPSec tunnels, GRE tunnels, DHCP, DNS Proxy, QoS, LLDP, or network profiles.
    - **Virtual system administrator (read-only)** : Read-only access to selected virtual systems on the firewall and specific aspects of virtual systems. A virtual system administrator with read-only access doesn’t have access to network interfaces, VLANs, virtual wires, virtual routers, IPSec tunnels, GRE tunnels, DHCP, DNS Proxy, QoS, LLDP, or network profiles.






