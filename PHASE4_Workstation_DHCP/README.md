# Phase 4 – Workstation Join + DHCP Setup  

## Goal  
Add Windows 10 workstations to the domain and configure DHCP for automatic IP addressing.  

## Tasks Completed  
- Installed and configured the DHCP Server role on ENSL-DC01  
- Created a DHCP scope:  
  - Name: ENSL-Scope  
  - IP Range: 192.168.100.50 – 192.168.100.200  
  - Subnet Mask: 255.255.255.0  
  - Default Gateway: 192.168.100.1  
  - DNS Server: 192.168.100.10 (Domain Controller)  
- Activated the DHCP scope  
- Joined Windows 10 workstation(s) to the **ensl.lab** domain  
- Verified DHCP leases and domain join status  

---

## Screenshots  
[Click here to download all screenshots (ZIP)](./SCREENSHOTS_PHASE_4.zip)  
> **Note:** GitHub can’t preview large ZIP files. Click the link to download.
