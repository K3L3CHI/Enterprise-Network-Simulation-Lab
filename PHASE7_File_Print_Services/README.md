# ✅ PHASE 7 – File & Print Services  

## 🎯 Goal  
Introduce shared resources with access control and provide centralized print services.  

## Tasks Completed  

### 1. File Shares with Permissions  
- Created departmental shared folder: `\\ENSL-DC01\HR_Docs`.  
- Applied **Share Permissions**:  
  - SG_HR_USERS → Full Control (or Modify, per design).  
- Applied **NTFS Permissions**:  
  - SG_HR_USERS → Modify.  
  - Administrators → Full Control.  
  - Creator Owner → Special permissions for subfolders.  
- ✅ Verified: HR users can access, non-HR users are denied.  

---

### 2. Shared Drives  
- Departmental folder accessible via UNC path:  
  - `\\ENSL-DC01\HR_Docs` (confirmed working).  
- Tested with users:  
  - HR user (Adeleke Chigozie) → Access ✅  
  - Non-HR user (Elijah Michaelson) → Access Denied ✅  

---

### 3. Print Server Setup  
- Installed **Print and Document Services** role on ENSL-DC01.  
- Created a test shared printer:  
  - Name: **OfficePrinter**  
  - Share path: `\\ENSL-DC01\OfficePrinter`  
  - Assigned driver: Generic / Text Only (lab simulation).  
- ✅ Verified printer object is visible to clients.  
- Tested adding printer from client:  
  - By IP → Worked  
  - By hostname → Resolved after fixing DNS  

---

## ✅ Outcome  
- Centralized shared folder with controlled access (department-only).  
- Centralized print server in Active Directory environment.  
- Verified functionality with test users.  

---

## 📂 Screenshots  
All screenshots for this phase are in the [SCREENSHOTS_PHASE_7.zip](./SCREENSHOTS_PHASE_7.zip) file.  
