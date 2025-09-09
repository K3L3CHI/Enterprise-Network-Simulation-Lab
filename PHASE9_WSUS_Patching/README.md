# ✅ PHASE 9 – Windows Server Update Services (WSUS) & Patching  

## Goal  
Implement centralized patch management using **Windows Server Update Services (WSUS)** to control how updates are delivered, tested, and approved across domain-joined machines.  

## ✅ Completed Tasks  
- Installed and configured **Windows Server Update Services (WSUS)** role on ENSL-DC01 with local content storage.  
- Set up computer groups in WSUS (e.g., Workstations) for client targeting.  
- Created and linked a WSUS **Group Policy Object (GPO)** to the **General Workstation OU**:  
  - Pointed clients to WSUS server (`http://ENSL-DC01:8530`).  
  - Enabled client-side targeting (auto-assign WS01 to Workstations).  
  - Configured automatic updates (download + scheduled install).  
- Forced client registration: confirmed **Enterprise-WS01** reports to WSUS.  
- Ran synchronization with Microsoft Update → downloaded available patches.  
- Approved targeted updates (e.g., Windows Defender definition updates) for deployment.  
- Verified on **Enterprise-WS01** that approved updates are detected, downloaded, and installed.  

---

## 🎯 Outcome  
- Domain-joined workstations now receive updates from the **internal WSUS server** instead of directly from the internet.  
- This enables **controlled patch testing, approval, and deployment** — ensuring security while reducing external bandwidth usage.  

---

## 📂 Screenshots  
All screenshots for this phase are in the [SCREENSHOTS_PHASE_9.zip](./SCREENSHOTS_PHASE_9.zip) file.  
