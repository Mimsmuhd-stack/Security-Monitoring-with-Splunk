# Security-Monitoring-with-Splunk
This repository contains my hands-on security monitoring and log analysis project using **Splunk**, focused on the **Frothly dataset**.  

The goal is to demonstrate practical use of Splunk for cloud security monitoring and incident investigation, showcasing how to extract meaningful insights from large datasets.

---

## 📌 Project Overview
The Frothly dataset simulates logs from a fictional company. Using Splunk, I performed queries and analysis to answer real-world security questions, including:

- 🔍 Detecting suspicious endpoint activity.  
- 🗂️ Investigating misconfigured S3 buckets.  
- 👥 Tracking IAM user behavior in AWS logs.  
- 💻 Identifying endpoints mining cryptocurrency.  
- 🪟 Comparing Windows OS editions across endpoints.  

---  
## Methodology
- **Data Sources**: AWS CloudTrail logs, S3 access logs, system logs, and endpoint telemetry ingested into Splunk.
- **Tools Used**: Splunk Search Processing (SPL) for searching, querying, and extracting relevant events; AWS logs; Sysmon; DNS and Endpoint security logs. 
- **Kali Linux** (virtual lab environment) 
- **Approach**: For each question, appropriate SPL queries were crafted to filter and extract data points such as IAM users, API call event IDs, bucket names, file uploads, hostnames, and OS details.
- **Verification**: Results were cross-checked against multiple log sources for accuracy and completeness.
---

## 📊 Key Learnings
- Practical experience with **SIEM (Splunk) for threat detection**  
- Improved knowledge of **AWS security monitoring**  
- Detection of **cryptomining activity** via log analysis  
- Hands-on exposure to **log correlation and investigation workflows**  

---

## 📝 Project Q&A
Check the document below for the list of investigation questions and answers:

📄 [Download Project Q&A PDF](https://github.com/Mimsmuhd-stack/Security-Monitoring-with-Splunk/blob/main/project-qa.pdf.pdf)

**_This project was a valuable learning experience, and I look forward to building on these skills in future security challenges._**

## 🤝 Contributing
This is a personal learning project, but suggestions and improvements are welcome. Feel free to open an issue or submit a pull request.

---

