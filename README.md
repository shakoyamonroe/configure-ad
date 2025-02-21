<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

# On-premises Active Directory Deployed in the Cloud (Azure)
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.

## 🎥 Video Demonstration
- **[YouTube: How to Deploy on-premises Active Directory within Azure Compute]
- https://youtu.be/cwlVz4tD8pk?si=xaauLzk1VpqO7d8G

## 🌍 Environments and Technologies Used
- **Microsoft Azure** (Virtual Machines/Compute)
- **Remote Desktop**
- **Active Directory Domain Services**
- **PowerShell**

## 🖥️ Operating Systems Used
- **Windows Server 2022**
- **Windows 10 (21H2)**

## 🔄 High-Level Deployment and Configuration Steps
1. **Set up Azure Virtual Machines**
2. **Install and Configure Active Directory Domain Services (AD DS)**
3. **Create and Manage User Accounts & Organizational Units (OUs)**
4. **Configure Group Policies and Access Control**

## ⚙️ Deployment and Configuration Steps

### 1️⃣ Set Up Azure Virtual Machines
- Deploy **Windows Server 2022** as the Domain Controller.
- Deploy **Windows 10 (21H2)** as a client machine.
- Connect both machines via **Remote Desktop**.

### 2️⃣ Install and Configure Active Directory Domain Services
- Open **Server Manager** → **Add Roles and Features**.
- Select **Active Directory Domain Services (AD DS)** and install it.
- Promote the server to a **Domain Controller**.

### 3️⃣ Create and Manage User Accounts & OUs
- Open **Active Directory Users and Computers (ADUC)**.
- Create **Organizational Units (OUs)** and **User Accounts**.
- Assign **user roles and permissions**.

### 4️⃣ Configure Group Policies and Access Control
- Open **Group Policy Management**.
- Create and apply **security policies** for user and device management.
- Verify domain-wide access control configurations.
