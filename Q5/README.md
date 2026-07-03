# Question 5: Storage & Inode Monitoring

This directory tracks filesystem capacity metrics, focusing on storage utilization thresholds and index allocation states.

## 📁 Files Included

* **`answer.txt`**: Holds the exported log of storage distribution parameters across the system mount points.

---

## 📊 Monitored Parameters

* **Space Allocation:** Monitored system availability with human-readable formatting using `df -h`.
* **Index Limits:** Tracked unique filesystem inode capacities across storage controllers using `df -i`.
* **Directory Footprint:** Appraised individual directory sizes across block storage volumes using `du -sh`.
