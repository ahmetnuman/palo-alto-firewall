#### Enable Intrazone and Interzone Rules Logs on Palo Alto

>> Ahmet Numan Aytemiz, 27 February 2021

---

By default it is disabled both intrazone and interzone rule logs.  
 
 - Intrazone traffic is allow by default.
 - Interzone traffic is deny  by default.

#### Enable intrazone-default and interzone-default Rule logs

**Polices >> Security >> intrazone-default > Override** 

**Polices >> Security >> interzone-default > Override** 

![Image](/img/enable_logs.PNG)

**commit**


