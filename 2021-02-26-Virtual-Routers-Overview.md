#### Palo Alto Virtual Routers

>> Ahmet Numan Aytemiz, 26 February 2021

---

#### Virtual Routers

- Local, static or dynamic routes
- Path Monitoring (if we use mıltiple ISP)
- Routing Information base (RIB)
- Forwarding Information Base (FIB)

#### Add Default Route to reach the internet

**Network > Virtual Routers > VR-1 >  Static Route > Add**

![Image](/img/staticroute.PNG)

**commit**

#### Test İnternet Connectivity

`ping source 10.1.10.254 host 8.8.8.8`

![Image](/img/internet.PNG)

#### 