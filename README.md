# Linux CLI Lab (SGA1)

This repository contains structured solutions and verification logs for the Linux Command Line Interface (CLI) Lab. Each directory represents a standalone milestone exploring essential system administration, security configurations, file management, and diagnostics.

---

## 📂 Repository Navigation Map

Click into any directory below to view specific command implementation logs, terminal screenshots, and diagnostic answers:

* 📁 **[Q1](./Q1)**: **Environment Diagnostics**
  * Baseline Google Cloud Shell hardware, terminal environment variables, and initial configuration audits.
* 📁 **[Q2](./Q2)**: **Project Workspace & Permissions**
  * Secure environment hardening utilizing absolute notation permissions (`chmod 750`) and ownership restrictions.
* 📁 **[Q3](./Q3)**: **Hard Links vs. Symbolic Links**
  * Functional analysis of file system behavior, tracking data persistence at the inode level upon source deletion.
* 📁 **[Q4](./Q4)**: **Input/Output Redirection & System Limits**
  * Practical routing of standard error descriptor logs (`2>`) and inspecting system kernel restrictions (`ulimit`).
* 📁 **[Q5](./Q5)**: **Storage & Inode Monitoring**
  * Reports assessing block device allocations (`df -h`), individual file footings (`du -sh`), and index limits (`df -i`).

---

## 🛠️ Summary of Utilized Utilities

The files stored within this repository demonstrate hands-on familiarity with the following core utilities:
* **System Metrics:** `df`, `du`, `ulimit`
* **File & Security Ops:** `ln`, `chmod`, `mkdir`, `rm`
* **Stream Controls:** Operator redirection (`>`), Error pipelines (`2>`), and input inspectors (`cat`)
