
## 🛠️ 3. Server Configuration (DHCP + DNS)

### 3.1 Static IP Settings  
Describe how you configured the server's static IP.


📸 **Screenshot: Server IP configuration**

---

### 3.2 DHCP Configuration  
Describe the DHCP pool you created (gateway, DNS, start IP, etc).

The DHCP pool (serverPool) was configured with a default gateway of 192.168.2.1, a DNS server of 192.168.2.2, a start IP address of 192.168.2.100, a subnet mask of 255.255.255.0, and a maximum of 50 users.

📸 **Screenshot: DHCP settings**

<img width="971" height="466" alt="image" src="https://github.com/user-attachments/assets/9a91de3f-6ac1-4741-86ab-ca367d5d07f0" />


### 3.3 DNS Configuration  
Explain how you enabled DNS and created name records.

The DNS service was enabled by switching the status to "On," and name records were created by adding "A Record" entries that map the computer names (librarypc1, librarypc2, and librarypc3) to their respective IP addresses (192.168.2.100, 192.168.2.101, and 192.168.2.102).

📸 **Screenshot: DNS service + name entries**
<img width="918" height="389" alt="image" src="https://github.com/user-attachments/assets/5dc2fbe7-408e-43ff-b6ba-f1c78cb84407" />

