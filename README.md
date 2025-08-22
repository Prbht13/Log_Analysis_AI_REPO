

🔍 **AI-Powered Log Anomaly Detection with Python**  

This repository demonstrates how to use **Machine Learning (Isolation Forest)** in **Python** to detect anomalies in log files. Logs often contain valuable insights into application performance, system errors, and security events. By applying AI, we can automatically detect unusual patterns that might indicate failures, attacks, or misconfigurations.  

---

## ⚙️ How It Works  

1. **Read Logs**  
   - The script reads logs from a file (`system_logs.txt`).  

2. **Parse Logs**  
   - Extracts:  
     - `timestamp` → Log timestamp  
     - `level` → Log severity (INFO, WARNING, ERROR, CRITICAL)  
     - `message` → Log message content  

3. **Feature Engineering**  
   - Converts severity levels into numeric scores.  
   - Calculates message length as an additional feature.  

4. **AI Model: Isolation Forest**  
   - Identifies unusual log entries based on severity and message length.  
   - Flags anomalies automatically.  

5. **Output**  
   - Prints detected anomalies with a clear ❌ **Anomaly** or ✅ **Normal** label.  

---
