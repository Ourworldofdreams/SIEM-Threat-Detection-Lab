# **SIEM Threat Detection Lab**

---

## **Welcome! 🚀**  

In this project, I demonstrate my ability to deploy a cybersecurity solution, simulate real-world threats, and analyze security events using Elastic SIEM and Kali Linux. This hands-on lab highlights my technical skills in threat detection, log analysis, and cybersecurity practices.  

---

## **Lab Overview**  

- **Objective**: Configure Elastic SIEM, simulate network threats using Kali Linux, and analyze security events.  
- **Key Takeaways**:  
  - Setting up a SIEM solution for monitoring and analysis.  
  - Simulating and detecting network threats.  
  - Interpreting security logs to identify adversarial activity.  

> This lab reflects my passion for cybersecurity and readiness for real-world challenges.  

---

## **Lab Environment**  

| **Component**       | **Purpose**                                |  
|----------------------|--------------------------------------------|  
| **Elastic SIEM**     | Central platform for log collection and threat analysis. |  
| **Kali Linux**       | Simulated attack scenarios like Nmap scans. |  
| **Beats**            | Data shippers for forwarding logs to Elastic Stack. |  

---

## **Process and Key Steps**  

### **1. Setting Up Elastic SIEM**  

Elastic SIEM, part of the Elastic Stack, provides powerful tools for detecting and analyzing threats in real time. I configured it to ingest logs and display them in an intuitive interface:  

- **Installed Components**:  
  - Elasticsearch: Log storage and indexing.  
  - Kibana: Visualization and SIEM dashboard.  

- **Key Configuration**:  
  - Installed and configured Filebeat to forward logs.  
  - Secured the environment with authentication.  

![Screenshot 2024-11-18 at 1 40 29 PM](https://github.com/user-attachments/assets/e9e8bf96-c636-4c8c-bab8-bab98ff3823b)
![Scr![Screenshot 2024-11-18 at 2 43 51 PM](https://github.com/user-attachments/assets/fc450157-8927-435e-acd0-63a7fe4702b8)
![Screenshot 2024-11-18 at 2 50 54 PM](https://github.com/user-attachments/assets/ea043230-6b87-49d5-9b16-8924ea3f4946) 

---

### **2. Simulating Threats with Kali Linux**  

To test the SIEM’s detection capabilities, I simulated network reconnaissance and attacks using Kali Linux:  

#### **Network Scanning (Nmap)**  
- **Objective**: Simulate an attacker identifying open ports and services.  
- **Commands**:  
  ![Screenshot 2024-11-18 at 4 41 06 PM](https://github.com/user-attachments/assets/8ce5d654-daef-4cdc-947f-f530aefde36f)
![Screenshot 2024-11-18 at 2 46 09 PM](https://github.com/user-attachments/assets/cb6f75bc-0532-4738-a9c6-035b0b99832c)

- **Outcome**: Elastic SIEM captured logs of the scanning activity.  
![Screenshot 2024-11-18 at 5 43 02 PM](https://github.com/user-attachments/assets/6d268c66-aac3-4c35-9b85-decb2de32547)

![Screenshot: Nmap Logs in SIEM](path/to/nmap_logs.png)  

**Why It Matters**: Early detection of reconnaissance can prevent full-scale cyberattacks.  

---

### **3. Detecting and Analyzing Threats in Elastic SIEM**  

The logs from the Nmap scans were visualized and analyzed in Kibana’s SIEM dashboard. Highlights include:  

- Detailed records of IP activity, port scans, and service discovery.  
- Real-time visualizations that help prioritize security alerts.  

![Screenshot 2024-11-19 at 4 23 55 PM](https://github.com/user-attachments/assets/fc185432-054b-4e68-85f0-7c68fdc365a3)
  ![Screenshot 2024-11-18 at 4 50 06 PM](https://github.com/user-attachments/assets/25f9abc9-a5e4-4026-8e71-e85c732b0004)
![Screenshot 2024-11-18 at 4 51 21 PM](https://github.com/user-attachments/assets/22335594-52ca-4c7a-942b-1fe09cd87368)
![IMG_430B2DDA5D33-1](https://github.com/user-attachments/assets/70e974b5-6e7a-401e-ab2d-3392f50b145a)

**Takeaway**: This process demonstrated how SIEM tools enhance visibility into potential threats.  

---

## **Results & Takeaways**  

- **Accomplishments**:  
  - Deployed and configured Elastic SIEM for threat monitoring.  
  - Simulated network threats and verified detection.  
  - Used dashboards to interpret and analyze attack data.  

**Professional Relevance**: This project showcases my ability to work with cutting-edge security tools, think critically, and contribute to proactive threat management.  

---

## **Closing Thoughts**  

This lab highlights my hands-on experience with security solutions and threat detection. It reflects my eagerness to learn, experiment, and apply my skills to real-world challenges.  

I’d love to discuss this project further and share how I can bring these skills to your team. Feel free to reach out!  

---
