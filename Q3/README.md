# Question 3: Hard Links vs. Symbolic Links

This directory explores the functional differences between hard links and symbolic (soft) links when the original source file is deleted.

## 📁 Files Included

* **`hardlink.txt`**: A hard link pointing directly to the file's data inode. Remains readable even after the original file is deleted.
* **`symlink.txt`**: A symbolic link pointing to the original file path. Becomes a broken/dangling link once the target is removed.

---

## 🔬 Core Experiment Steps

1. **Creation:** Created `original.txt` containing `"Important Data"`.
2. **Linking:** * Formed a hard link using `ln original.txt hardlink.txt` (shared Inode `131502`).
   * Formed a symbolic link using `ln -s original.txt symlink.txt`.
3. **Disruption:** Removed the source file (`rm original.txt`).
4. **Result:** `cat hardlink.txt` successfully printed the data, while `cat symlink.txt` threw a `No such file or directory` error.
