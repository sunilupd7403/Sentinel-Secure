# Sentinel Secure: Safeguarding Networks with Wazuh Guard

This project demonstrates how to secure and monitor computer networks using **Wazuh**, an open-source Security Information and Event Management (SIEM) tool. The goal is to provide real-time threat detection, file integrity monitoring, and compliance enforcement in a centralized environment.

## 📌 Objective

To implement a practical and scalable cybersecurity solution using Wazuh for detecting intrusions, monitoring log files, enforcing system compliance, and securing endpoint activity.

## 🔒 Key Features

- ✅ **Real-Time Threat Detection** – Monitor suspicious activities across systems.
- 📁 **File Integrity Monitoring (FIM)** – Detect unauthorized file modifications.
- 📜 **Log Analysis** – Collect and parse logs from various sources (e.g., syslog, Linux logs).
- 📊 **Compliance Management** – Align with standards like PCI DSS, HIPAA, and GDPR.
- 🛡️ **Security Alerting** – Get alerts for potential security breaches.
- 🧠 **Centralized Dashboard** – Use the Wazuh dashboard with ELK Stack for visualization and analysis.

## 🛠️ Technologies Used

- **Wazuh** – Core SIEM platform
- **Elastic Stack (ELK)** – Elasticsearch, Logstash, and Kibana for data visualization
- **Linux** – Endpoint systems and Wazuh server environment
- **Sysmon** – For enhanced logging on endpoints

## 🚀 How It Works

1. Wazuh agents are installed on client machines to monitor system logs and activities.
2. The Wazuh manager collects data and applies detection rules.
3. Alerts are generated for suspicious events and sent to the Wazuh dashboard.
4. Logs are stored and visualized using Kibana from the ELK stack.

## 📈 Benefits

- Improved visibility into system activities and potential threats.
- Easier compliance with security regulations.
- Faster incident response through real-time alerting.

## 📚 Use Cases

- University or corporate environments needing endpoint monitoring.
- Security teams managing multiple servers and workstations.
- IT professionals learning SIEM and open-source security solutions.

## 🔗 References

- [Wazuh Documentation](https://documentation.wazuh.com/)

## 📃 License

This project is licensed under the MIT License.

---
