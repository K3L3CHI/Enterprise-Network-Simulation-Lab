# Phase 3.5 – DNS Configuration & Verification  

## Goal  
Ensure reliable hostname resolution inside the lab environment.  

## Tasks Completed  
- **Forward Lookup Zone**  
  - Confirmed *ensl.local* created during DC promotion.  
  - Verified A records:  
    - dc01.ensl.local → 192.168.100.10  
    - ws01.ensl.local → 192.168.100.99  
- **Reverse Lookup Zone**  
  - Created *100.168.192.in-addr.arpa.*  
  - Verified PTR records:  
    - 192.168.100.10 → dc01.ensl.local  
    - 192.168.100.99 → ws01.ensl.local  
- **Testing**  
  - On WS01:  
    - ping dc01.ensl.local → reply ✅  
    - nslookup dc01.ensl.local → 192.168.100.10 ✅  
    - nslookup 192.168.100.99 → ws01.ensl.local ✅  
- **Integration**  
  - DHCP option 006 points clients to 192.168.100.10 for DNS.  
  - Verified domain logon and GPO processing succeed.  

---

## Outcome  
DNS is fully functional with forward & reverse lookups.  
This forms the **critical foundation** for AD, GPO, file shares, and printing.  

---

## Screenshots  
[Click here to download all screenshots (ZIP)](./SCREENSHOTS_PHASE_3.5.zip)  
> **Note:** GitHub can’t preview large ZIP files. Click the link to download.
