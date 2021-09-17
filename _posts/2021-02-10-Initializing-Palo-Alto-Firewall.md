#### Initializing Palo Alto Firewall

> Ahmet Numan Aytemiz , 10 February 2021

---

- Use case and network diagram
- Initial Configuration
- Graphical User Interface
- Management Settings
- Configuration Management

https://docs.paloaltonetworks.com/pan-os/9-0/pan-os-admin.html (choose version)

####Accessing Firewall

**From Web or SSH:**

- Default Ip Address : 192.168.1.1
- SSH or HTTPS

**From Console:**

- 9600 Data Rate
- 8 Data Bits
- Parity: none
- Stop bits: 1
- Flow Control : None

**Console via virtualization software**

####Boot Firewall VM

![Image](images/boot1.PNG)

####Login with admin/admin username password

![Image](/img/login.PNG)

#### First Config

**Configure Management IP Address And Mgmt Route**

```
admin@PA-VM> configure
admin@PA-VM# set deviceconfig system type static
admin@PA-VM# set deviceconfig system ip-address 10.1.10.253 netmask 255.255.255.0 default-gateway 10.1.10.2
admin@PA-VM# commit
```

![Image](/img/configfirst.PNG)

####Configuration Changes

| running-config.xml                        | Candidate Configuration                                    | Commit                     
| ------                                    | ---                                                        | ---                   
| The Configuration file firewall is using  | File used to stage all changes before applying them        | copies candidate config to running config and saves a copy