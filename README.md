# Cybersecuirty-SOC-L1-and-L2-Projects


1) Multiple Login Failures
Objective: Detect brute-force or password-spraying attacks.

Microsoft Sentinel Setup:

Data Source: Azure Active Directory (AAD) or Windows Security logs.



2) Typical Travel (Impossible Travel)
Objective: Detect logins from different countries within a short timeframe.

Microsoft Sentinel Setup:

Data Source: SigninLogs



3) Malware Detection
Objective: Detect known malware file drops or alerts from Defender/AV.

Microsoft Sentinel Setup:

Data Source: Microsoft Defender for Endpoint.



4) Ransomware File Activity
Objective: Detect rapid encryption behavior (mass file changes).

Microsoft Sentinel Setup:

Data Source: Microsoft Defender for Endpoint


5) Email Header Analysis (Phishing Detection)
Objective: Detect spoofed or phishing emails using header anomalies.

Microsoft Sentinel Setup:

Data Source: Office 365 logs (EmailEvents)
