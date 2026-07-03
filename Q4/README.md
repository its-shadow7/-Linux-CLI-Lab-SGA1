# Question 4: Input/Output Redirection & System Limits

This directory covers standard error redirection and inspecting system resource limitations using the shell built-ins.

## 📁 Files Included

* **`error.txt`**: Captures the standard error output (`stderr`) from a failed file access command.
* **`output.txt`**: Intended for standard output (`stdout`) logs.

---

## ⚙️ Implemented Tasks

1. **Error Redirection:** Executed `ls missing_file.txt > output.txt 2> error.txt` to safely route the command's diagnostic error string directly into `error.txt`.
2. **Resource Limits:** Evaluated process limitations using `ulimit -a` to inspect active kernel restriction metrics (such as maximum file size, scheduling priority, and stack allocation parameters).
