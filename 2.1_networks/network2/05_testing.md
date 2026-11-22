

## 🔍 5. Testing & Verification

### 5.1 Ping Tests  
Did the PC successfully ping a DNS name (e.g., `library_pc1`)?  
Explain the result.

Yes, the PC successfully pinged all three DNS names (librarypc1, librarypc2, and librarypc3). The DNS server correctly resolved each hostname into its corresponding IP address, and all tests showed 0% packet loss, proving that name resolution and network communication are working properly.

📸 **Screenshot of successful ping**

<img width="450" height="655" alt="image" src="https://github.com/user-attachments/assets/17ef3d9b-2ef1-4106-8c4a-49e2fa82688e" />


### 5.2 DNS Resolution  
Describe whether DNS resolved the hostname correctly.

Yes, DNS resolved the hostnames correctly by mapping each name (librarypc1, librarypc2, and librarypc3) to its exact IP address (192.168.2.100, 192.168.2.101, and 192.168.2.102).

### 5.3 DHCP Lease Verification  
Describe the IPs assigned to each PC.  
Do they match the DHCP pool?

Yes, the IPs assigned to the PCs match the DHCP pool range, successfully leasing addresses starting from 192.168.2.100

📸 **Screenshot: `ipconfig /all`**
