# Network Reconnaissance
- Performed an attack on Windows Server to find out what services are running on the machine

  <img width="936" height="721" alt="image" src="https://github.com/user-attachments/assets/e114ad1a-fdb2-49b9-a586-908c96cd22ef" />

### Discovery show that the Windows Server has many open services running which can be exploited.

- 53 => DNS
- 88 => Kerberos
- 135 => msrpc
- 139 => net-bios-ssn
- 389 => Active Directory LDAP (Domain: org.workspace.test, Site: Default-First-Site-Name)
- 445 => Microsoft-ds?
- 464 => kpasswd5?
- 593 => Microsoft Windows RPC over HTTP 1.0
- 636 => Active Directory LDAP (Domain: org.workspace.test, Site: Default-First-Site-Name)
- 3268 => tcpwrapped
- 5985 => http 

# From pfSense Log Detection

<img width="721" height="513" alt="image" src="https://github.com/user-attachments/assets/89089d23-8e0d-4eea-9ab0-e235ecd7257a" />

# Event Created from Wazuh Dashboard

<img width="946" height="715" alt="image" src="https://github.com/user-attachments/assets/20eb946a-f96a-42e0-8fde-cacab32c8c86" />
