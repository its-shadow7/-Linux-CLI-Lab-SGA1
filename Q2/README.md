# Question 2: Project Workspace & Permissions

This directory contains the documentation and verification for setting up a secure project workspace with restricted access permissions.

## 📁 Files Included

* **`Project_Workspace_Report.txt`**: Contains the full verification logs showing the directory structure creation and the exact permission states applied to the project files.
* **`Screenshot 2026-07-03 203649.png`**: Terminal screenshot verifying the execution of the permission configuration commands.

---

## 🔒 Implemented Security Configurations

The following access control tasks were accomplished in this section:
1. **Directory Isolation:** Created a distinct project workspace environment (`secure_project`).
2. **Permission Hardening:** Utilized `chmod 750` to grant full access (read, write, execute) to the owner, read/execute permissions to the group, and completely blocked all public/other users from accessing the folder contents.
3. **Audit Logging:** Verified the absolute flags using `ls -ld` to confirm the resulting `drwxr-x---` footprint.
