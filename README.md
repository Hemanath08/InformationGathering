# NAME: K.HEMANATH
# REGISTER NO: 212223100012
# Ex-02 InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

## Architecture Diagram
```
                      +-------------------------+
                      |     Attacker System     |
                      |     (Kali Linux)        |
                      +-----------+-------------+
                                  |
                                  | Terminal / Browser
                                  | Executes Recon Tools
                                  v
      +------------------- Passive Recon --------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   WHOIS Query  | --> |    Domain Registrars    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   DNS Enum     | --> |     Public DNS Servers  |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      +-----------------------------------------------------+

                                  |
                                  v

      +------------------ Active Recon ----------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   Nmap Scan    | --> |  Target Host/Network    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | WhatWeb, Wapp | --> |   Target Web Application |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | theHarvester   | --> |     Search Engines      |  |
      |  +----------------+     +------------------------+  |
      +-----------------------------------------------------+

                                  |
                                  v
                    +-----------------------------+
                    |     Collected Information   |
                    | - IPs, Subdomains           |
                    | - Open Ports & Services     |
                    | - Technology Stack          |
                    | - Emails, Metadata          |
                    +-----------------------------+
```

## OUTPUT:
### Whois
<img width="1919" height="1015" alt="image" src="https://github.com/user-attachments/assets/58803e41-5191-4be3-b5f6-314679e06f7b" />
<img width="1918" height="1018" alt="image" src="https://github.com/user-attachments/assets/565e7608-2cab-4d1a-a530-9d5b20da0580" />
<img width="1918" height="1015" alt="image" src="https://github.com/user-attachments/assets/094d949b-8a0f-4eb1-8224-2ffe2216a478" />
<img width="1917" height="1016" alt="image" src="https://github.com/user-attachments/assets/baa798f8-8687-486b-a839-92d0e30cad74" />

### Finding Hosting Company :
<img width="1919" height="972" alt="image" src="https://github.com/user-attachments/assets/d4f87da2-4a71-47f1-8ab5-f3cd795c02f0" />
<img width="1918" height="1017" alt="image" src="https://github.com/user-attachments/assets/aec6b44d-5411-47d9-8c9a-6ee23a8c7850" />
<img width="1919" height="1020" alt="image" src="https://github.com/user-attachments/assets/f8d5bf8c-d643-48d5-87ed-d933fa54077d" />

### History of the website :
<img width="1919" height="1016" alt="image" src="https://github.com/user-attachments/assets/21ee599e-e6c5-475a-af25-06ada662ab46" />
<img width="1919" height="1016" alt="image" src="https://github.com/user-attachments/assets/3c409310-4f45-44c4-a576-46a756f61eb8" />
<img width="1919" height="1013" alt="image" src="https://github.com/user-attachments/assets/5e6da515-1465-4e25-93b5-e98fb0f553ff" />
<img width="1919" height="1015" alt="image" src="https://github.com/user-attachments/assets/c50a72f0-58f8-48ed-ae8b-579335794b4a" />
<img width="1919" height="1016" alt="image" src="https://github.com/user-attachments/assets/105aef4c-e050-4bf5-b389-3e0bb09e8e70" />

### ping command :
### Kali Linux:
<img width="806" height="442" alt="image" src="https://github.com/user-attachments/assets/17b898ff-7c18-4698-a570-05c0f09ff11b" />

### Windows:
<img width="1470" height="482" alt="image" src="https://github.com/user-attachments/assets/b36cfbb1-16d2-4c55-9023-a56ab0b1280e" />


### whois :
<img width="1905" height="733" alt="image" src="https://github.com/user-attachments/assets/4f3a339c-dee6-46be-b73c-932eb6c8d43b" />
<img width="863" height="737" alt="image" src="https://github.com/user-attachments/assets/c41f6e40-d7bb-4c64-bd62-e0090552334a" />

### netcat :
<img width="1195" height="491" alt="image" src="https://github.com/user-attachments/assets/da9cf7ae-6be9-4794-bf5e-141daab53c25" />

### nmap :
<img width="1166" height="358" alt="image" src="https://github.com/user-attachments/assets/603afeec-4b5b-420a-a135-b4c8fec07aec" />

### whatweb :
<img width="1898" height="186" alt="image" src="https://github.com/user-attachments/assets/32223c7d-1d94-498b-9d56-63abcb3dac17" />

### httprint :
<img width="1218" height="772" alt="image" src="https://github.com/user-attachments/assets/431fae01-e177-4482-9051-c02e579377ea" />

### TCP traceroute :
<img width="1900" height="457" alt="image" src="https://github.com/user-attachments/assets/faddc14f-dd4b-4f9e-9577-4e4968a3fe20" />

### UDP traceroute :
<img width="1147" height="516" alt="image" src="https://github.com/user-attachments/assets/f6fd8295-baa6-49c0-b619-84f74db88f4e" />


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
