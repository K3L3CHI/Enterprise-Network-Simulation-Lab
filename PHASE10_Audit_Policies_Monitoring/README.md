# ✅ PHASE 10 – Audit Policies & Monitoring  

## 🎯 Goal  
Establish auditing and monitoring across the domain to track key security-related actions, ensuring visibility into logons, file access, process activity, and policy changes.  

## 📌 Tasks Completed  
- ✅ Enabled **Advanced Audit Policies** via Group Policy:  
  - Logon Events  
  - Object Access  
  - Account Management  
  - Process Creation  
- ✅ Created **Event Viewer filters** on DC and WS for quick visibility of key events.  
- ✅ Deployed GPO so all domain-joined machines follow the same audit settings.  
- ✅ Installed **Sysmon** on DC and WS.  
- ✅ Applied a **Sysmon configuration file** to capture detailed events (process creation, network connections, etc.).  
- ✅ Verified logs in **Event Viewer → Microsoft → Windows → Sysmon → Operational**.  

---

## 📊 Outcome  
- Auditing and Sysmon are active across the lab.  
- The DC and WS are now generating **detailed logs** of important activities, giving better visibility into security-related actions across the domain.  

---

## 📂 Screenshots  
All screenshots for this phase are in the [SCREENSHOTS_PHASE_10.zip](./SCREENSHOTS_PHASE_10.zip) file.  
