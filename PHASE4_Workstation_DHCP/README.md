# Phase 4 – Workstation Join + DHCP Setup  

## Goal  
Connect the client machine to the domain and automate IP assignment using DHCP.  

## Tasks Completed  
- Renamed and configured **Enterprise-WS01** (Windows 10)  
- Joined workstation to **ensl.local** domain  
- Installed and configured DHCP on **ENSL-DC01**  
- Configured DHCP scope:  
  - IP Range: 192.168.100.30 – 192.168.100.100  
  - Exclusions: 192.168.100.30 – 192.168.100.39  
  - DNS: 192.168.100.10  
  - Gateway placeholder: 192.168.100.1  
- Reserved IP **192.168.100.99** for **Enterprise-WS01**  
- Resolved DHCP issues and verified successful IP assignment  

---

## Outcome  
The workstation is now domain-joined, and IP assignment is handled automatically through DHCP with proper reservations and exclusions.  

---

## Screenshots  
[Click here to download all screenshots (ZIP)](./SCREENSHOTS_PHASE_4.zip)  
> **Note:** GitHub can’t preview large ZIP files. Click the link to download.
