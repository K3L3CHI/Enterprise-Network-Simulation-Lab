# ✅ PHASE 6 – Group Policy Management  

## Goal  
Assign delegated permissions and apply real-world policies based on security group membership.  

## Tasks Completed  
- Installed Group Policy Management Console (GPMC)  
- Created and linked GPOs to OUs with Security Filtering:  
  - GPO_DisableCMD_TestLab — Blocks Command Prompt for SG_TESTLAB_USER  
  - GPO_DisableControlPanel_TestLab — Blocks Control Panel and PC Settings for SG_TESTLAB_USER  
  - GPO_LoginBanner_GeneralWorkstation — Displays authorized access notice for SG_GeneralWorkstation  
- Added Enterprise-WS01 to SG_GeneralWorkstation for login banner testing  
- Verified policies apply correctly via `gpupdate /force`  
- Tested and confirmed targeted restrictions only affect intended users/workstations  
- Backed up created GPOs for reuse  

---

## 📂 Screenshots  
All screenshots for this phase are in the [SCREENSHOTS_PHASE_6.zip](./SCREENSHOTS_PHASE_6.zip) file.  
