#### Palo Alto Layer 3 Interface Setup

> Ahmet Numan Aytemiz, 11 February 2021

---

According to lab topolgy create Layer 3 Interfaces.

**Network > Interfaces**

![Image](/img/ethernet11.PNG)

![Image](/img/iip.PNG)

![Image](/img/manp.PNG)

**Similarly add configure ethernet 1/2 and ethernet 1/3 then commit** after that interface config will be look like ;

![Image](/img/configs.PNG)

#### Add Default Route to reach the internet

**Network > Virtual Routers > VR-1 >  Static Route > Add**

![Image](/img/staticroute.PNG)

**commit**

#### Test İnternet Connectivity

`ping source 10.1.10.254 host 8.8.8.8`

![Image](/img/internet.PNG)


