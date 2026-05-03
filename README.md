<h1 align="center">🛡️ DFIR Investigation – M57 Patents</h1>
<p align="center">Digital Forensics | Incident Response | Cybersecurity Project</p>

---

📌 Overview
This project is a **Digital Forensics & Incident Response (DFIR)** investigation using the **M57 Patents dataset**.  
The analysis was conducted with Autopsy to identify suspicious activity and determine whether data exfiltration occurred.

---

🎯 Objectives
- Verify integrity of forensic evidence  
- Analyze system and user activity  
- Identify Indicators of Compromise (IOCs)  
- Reconstruct an attack timeline  
- Determine if data exfiltration took place  

---

🛠️ Tools & Technologies
- **Autopsy 4.23.0**  
- **NIST CFReDS Dataset (M57 Patents)**  
- Windows forensic analysis environment  

---

🔍 Investigation Highlights
- 📧 Email Analysis: Suspicious communication with external contacts  
- 🌐 Web Activity: Multiple patent-related downloads  
- 💾 USB Devices: Multiple external drives connected in a short timeframe  
- 📁 File Artifacts: Access to sensitive patent documents  
- ⚠️ Threat Indicators: Encrypted files, compressed archives, and unusual activity  

---

🧠 Attack Summary
1. User conducted patent research  
2. Accessed and collected sensitive files  
3. Created compressed archive (data staging)  
4. Transferred data via USB devices  
5. Communicated externally via email  

---

🚨 Key Findings
- Insider threat activity identified  
- Evidence of unauthorized data access  
- High likelihood of data exfiltration via USB and email  
- Suspicious communication with external parties  

---

📊 Conclusion
The investigation concludes with high confidence that an insider threat occurred and sensitive data was exfiltrated.

---

📂 Project Structure
M57-DFIR-Project/
│── report/
│   └── M57_Forensic_Report.pdf
│── images/
│   ├── autopsy.png
│   ├── email.png
│   └── usb.png
│── README.md

---

🚀 Skills Demonstrated
- Digital Forensics  
- Incident Response  
- Threat Hunting  
- Timeline Reconstruction  
- Analytical Thinking  

---

🔗 Dataset Source
https://cfreds.nist.gov




