# ✅ PHASE 8 – Backup & Restore Strategies  

## 🎯 Goal  
Protect AD and lab configurations from data loss.  

## Tasks Completed  
- Installed **Windows Server Backup** feature on ENSL-DC01.  
- Performed **System State Backup**:  
  - Backup location: `E:\ServerBackup`  
  - Confirmed backup completed successfully.  
- Configured **Daily Scheduled Backup**:  
  - Included System State for AD recovery.  
  - Backup type: Full server backup to external virtual disk (E:).  
  - Verified scheduled job appears in Task Scheduler.  
- Created **VirtualBox Snapshots** for ENSL-DC01:  
  - Naming convention: `PH8_Snapshot_Backup_[date]`  
  - Stored as restore point before major lab changes.  
- Verified backup integrity by reviewing job logs in Windows Server Backup.  
- Practiced **test restore simulation** (non-intrusive):  
  - Opened Recovery Wizard and walked through options without executing actual restore.  

---

## ✅ Outcome  
- Lab now has dual backup strategy:  
- **Windows Server Backup** for system state and data.  
- **VirtualBox Snapshots** for fast rollback.  
- Confident restore process tested at simulation level.  
- Ensures domain services and configurations can be recovered after failure.  

---

## 📂 Screenshots  
All screenshots for this phase are in the [SCREENSHOTS_PHASE_8.zip](./SCREENSHOTS_PHASE_8.zip) file.  
