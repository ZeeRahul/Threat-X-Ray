# Threat-X-Ray
Threat X-Ray a advanced malware scanning tool built with Python that detects suspicious URLs and files using behavioral analysis, download triggers, and phishing indicators. Includes popup alerts and detailed reports.


Threat X-ray 🛡️
A Smart Malware Scanning & Detection Tool

Threat X-ray is an advanced malware scanning utility developed in Python that analyzes URLs and files for suspicious activity, phishing patterns, automatic downloads, and broken links. It provides real-time popup alerts and generates a detailed security report, making it ideal for researchers, security professionals, and enthusiasts.

✅ Key Features
🔗 Phishing & URL Scanning: Analyze URLs for malicious content, automatic download triggers, or broken links.

📥 Download Activity Monitoring: Detects unexpected or stealthy downloads triggered by URL visit.

🚨 Real-time Popup Alerts: Notifies users instantly with a categorized alert (Safe / Malicious).

📊 Detailed Report Generation: Summarizes scanning behavior including status codes, redirections, and threat indicators.

🧪 Custom URL Input: Enter and scan URLs manually or via batch import.

💻 User-Friendly Interface (if GUI included with PyQt5 or Tkinter)

🛠️ Tech Stack
Python 3.x

requests, re, tkinter or PyQt5 (for GUI and alerts)

os, webbrowser, and other standard libraries

Optional: Integration with VirusTotal API or WHOIS for threat enrichment

