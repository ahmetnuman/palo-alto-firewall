#### Palo Alto Next Generation Firewall 

> Ahmet Numan Aytemiz, 10 February 2021

---

| Single-pass Architecture    | Traditional Firewall                               
| ------                      | ---                                     
| More Security               | Stack Seperate Functions 
| Best Perofomance            | Worse Performance                
| Inspection Up Front         | Less Secure                             
| Inspection Done Once        |                            


| User-ID                                 |                           
| ------                                  |                                     
| Integrate with Active Directory         |  
| Define Groups and Roles                 |                 
| Track Top Application for User or Group |                              
| Set Policy Based on User or Group       |      


| App-ID                     |                           
| ------                     |                                     
| Layer 7 Classificataion    |  
| Block evasive Applications |   

| Content-ID                  |                           
| ------                      |                                     
| Intrusion Prevention System |  
| Wildfire- Anti Malware      |    
| Command And Control         |    
| File and Data Filtering     |    
| URL Filtering               |  



             
![Image](/img/architecture.png)

**Control and Data Plane**

| Control Plane               | Data Plane                               
| ------                      | ---                                     
| Management of the Firewall  | Policy Processing 
| Configuration               | Network Activity                
| Logging                     |                           
| Reports                     |   

| Additional Features |                           
| ------              |                                     
| IPSEC VPN and NAT   |  
| QoS                 |    
| High Availability   |    
| Managing the Firewall (Panorama)  |    
| Global Protect        |  
| Virtual and Phsical   |  