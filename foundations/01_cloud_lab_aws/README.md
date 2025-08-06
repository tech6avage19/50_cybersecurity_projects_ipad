# ☁️ Project 1: Build a Cloud Cybersecurity Lab on AWS (iPad)

> **Category:** Foundations  
> **Project #:** 1 of 50+  
> **Tags:** `cloud`, `aws`, `ec2`, `ipad`, `lab`

---

## 🧠 Objective

Deploy and configure a cloud-based cybersecurity lab environment using only an iPad and AWS EC2. This forms the base of all future hands-on projects.

---

## 🧰 Tools Used

- AWS EC2 (Ubuntu 20.04)
- Termius (for SSH from iPad)
- Chrome/Browser

---

## 🛠️ Steps

1. Create AWS Account  
2. Generate SSH key in Termius  
3. Launch EC2 instance with Ubuntu  
4. Configure Security Group:
   - Port: `22`
   - Protocol: `TCP`
   - Source: `My IP only`
5. Connect from Termius using private key
6. Update the server:
   ```bash
   sudo apt update && sudo apt upgrade -y
