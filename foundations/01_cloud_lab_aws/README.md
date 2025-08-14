# 🏠 Cybersecurity Home Lab

[![Watch the video](https://img.youtube.com/vi/YOUR_VIDEO_ID/maxresdefault.jpg)](https://youtu.be/YOUR_VIDEO_ID)

---

## 📌 Overview
This project sets up a **personal cybersecurity home lab** designed for hands-on training, testing, and experimentation.  
It includes **AWS + Azure cloud resources**, a local virtualized network, and security tools to simulate real-world environments for penetration testing, monitoring, and incident response.

---

## 🖥 Architecture Diagram
![Architecture Diagram](path/to/architecture.png)  
*Diagram showing AWS, Azure, and local network integration.*

---

## 🛠 Technologies Used
**Cloud Providers**
- AWS (VPC, EC2, IAM, Security Groups)
- Azure (Virtual Network, VM, Network Security Groups)

**Virtualization**
- VirtualBox / VMware Workstation

**Security Tools**
- Wazuh SIEM
- Kali Linux
- Splunk Free

**Networking**
- pfSense firewall
- Hardened DNS (Quad9 / Cloudflare)

---

## ⚙️ Setup & Deployment

### 1️⃣ AWS Setup
1. Create a new **VPC** with private/public subnets.
2. Launch an **EC2 instance** (Ubuntu Server).
3. Configure **IAM roles** and **security groups**.

### 2️⃣ Azure Setup
1. Create a **Resource Group** and **Virtual Network**.
2. Launch a **VM** (Windows Server / Linux).
3. Set up **NSGs** with restricted inbound rules.

### 3️⃣ Local Lab
1. Install **VirtualBox** or **VMware Workstation**.
2. Create a **pfSense firewall VM**.
3. Deploy **Kali Linux** and **Windows 10** VMs.

### 4️⃣ Security Tooling
1. Deploy **Wazuh SIEM** for log collection.
2. Integrate with AWS CloudWatch and Azure Monitor.
3. Test detection with simulated attacks.

---

## 📸 Screenshots

| Description | Image |
|-------------|-------|
| AWS VPC Setup | ![AWS VPC](path/to/aws-vpc.png) |
| Azure VM Deployment | ![Azure VM](path/to/azure-vm.png) |
| Wazuh Dashboard | ![Wazuh SIEM](path/to/wazuh.png) |
| pfSense Firewall Rules | ![pfSense](path/to/pfsense.png) |

---

## 🎯 Learning Outcomes
- Deployed a multi-cloud cybersecurity lab.
- Configured firewalls and SIEM for monitoring.
- Practiced integrating AWS, Azure, and local virtualization.
- Hardened network using secure DNS.

---

## 📚 References
- [AWS Documentation](https://docs.aws.amazon.com/)
- [Azure Documentation](https://learn.microsoft.com/azure/)
- [Wazuh SIEM Docs](https://documentation.wazuh.com/)
- [pfSense Docs](https://docs.netgate.com/pfsense/en/latest/)

---

## 📅 Project Status
✅ Completed — **See video demo above**
