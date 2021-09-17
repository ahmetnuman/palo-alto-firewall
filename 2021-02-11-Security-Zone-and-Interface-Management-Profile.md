#### Security Zone and Interface Management Profile

> Ahmet Numan Aytemiz, 11 February 2021

---

#### Security Zones

- Controls traffic
- Intrazone - Allowed By Default
- Interzone - Denied by default
- Each interface assigned to a zone

#### Interface Management Profile

- Allows specific management functions
- Allow ping
- Default is to deny management services

#### Configure Security Zones

Create INSIDE, DMZ and OUTSIDE zones according to lab topology INSIDE, DMZ and OUTSIDE

**Network > Zones > Add**

![Image](/img/INSIDE.PNG)

![Image](/img/ZONES.PNG)

Add interface management profile to allow ping to the intefaces..

**Network > Network Profiles > Interface Mgmt**

![Image](/img/manprof.PNG)

then commit....



