<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

# On-premises Active Directory Deployed in the Cloud (Azure)
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.

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
  
<img width="616" alt="Screenshot 2025-03-09 at 8 43 11 PM" src="https://github.com/user-attachments/assets/cbf8e16b-132d-486a-9839-2c6742f247cc" />

<img width="881" alt="Screenshot 2025-03-11 at 12 49 53 PM" src="https://github.com/user-attachments/assets/04ac3408-65b9-4891-b75f-00bfb1e695f0" />

<img width="601" alt="Screenshot 2025-03-11 at 12 55 53 PM" src="https://github.com/user-attachments/assets/def5ec49-241d-4177-b65c-0cf67961cab6" />

<img width="581" alt="Screenshot 2025-03-11 at 12 55 14 PM" src="https://github.com/user-attachments/assets/daf382c6-ba43-4427-8b0d-a28d471eaf7e" />

<img width="453" alt="Screenshot 2025-03-11 at 12 57 56 PM" src="https://github.com/user-attachments/assets/95149036-94a5-4d49-89cb-023c5d11b244" />


### 2️⃣ Install and Configure Active Directory Domain Services
- Open **Server Manager** → **Add Roles and Features**.
- Select **Active Directory Domain Services (AD DS)** and install it.
- Promote the server to a **Domain Controller**.

<img width="578" alt="Screenshot 2025-03-11 at 12 53 28 PM" src="https://github.com/user-attachments/assets/c6eceb8b-80e3-46b3-a017-6fc62fe549f8" />

<img width="472" alt="Screenshot 2025-03-11 at 1 01 01 PM" src="https://github.com/user-attachments/assets/3ef51fab-8766-4a95-8f6e-4e2f9d38e3af" />

<img width="367" alt="Screenshot 2025-03-11 at 1 04 20 PM" src="https://github.com/user-attachments/assets/ec836e2d-bf48-414e-bd95-885df4f02681" />

<img width="201" alt="Screenshot 2025-03-11 at 1 06 33 PM" src="https://github.com/user-attachments/assets/691a913d-c34c-4b13-96a3-17384a80423f" />

<img width="448" alt="Screenshot 2025-03-11 at 1 08 14 PM" src="https://github.com/user-attachments/assets/474da5f4-f6f9-4c92-a72a-afebc4af9f15" />

<img width="342" alt="Screenshot 2025-03-11 at 1 10 09 PM" src="https://github.com/user-attachments/assets/78d06cbb-04ea-4a17-bbca-3a1883b9e2f5" />



### 3️⃣ Create and Manage User Accounts & OUs
- Open **Active Directory Users and Computers (ADUC)**.
- Create **Organizational Units (OUs)** and **User Accounts**.
- Assign **user roles and permissions**.

<img width="467" alt="Screenshot 2025-03-11 at 1 13 36 PM" src="https://github.com/user-attachments/assets/6f1b93c9-d417-43f9-b560-5ff476371cab" />

<img width="468" alt="Screenshot 2025-03-11 at 1 15 48 PM" src="https://github.com/user-attachments/assets/9f54d4db-ad25-4afe-aad0-83fe26790ae1" />

<img width="266" alt="Screenshot 2025-03-11 at 1 18 08 PM" src="https://github.com/user-attachments/assets/f3704b15-8a4f-4667-aa79-7b6eebd80cb4" />

<img width="257" alt="Screenshot 2025-03-11 at 1 19 20 PM" src="https://github.com/user-attachments/assets/2df17102-4fc5-4c10-b41b-abb7a84b0b89" />

<img width="247" alt="Screenshot 2025-03-11 at 1 22 21 PM" src="https://github.com/user-attachments/assets/4d768591-8fa2-4445-b1b1-2c9460ce8cf3" />


### 4️⃣ Configure Group Policies and Access Control
- Open **Group Policy Management**.
- Create and apply **security policies** for user and device management.
- Verify domain-wide access control configurations.

  <img width="418" alt="Screenshot 2025-03-11 at 1 30 47 PM" src="https://github.com/user-attachments/assets/3401abca-3e9a-4b04-b049-eb0018fc8445" />

  <img width="416" alt="Screenshot 2025-03-11 at 1 33 53 PM" src="https://github.com/user-attachments/assets/ac904a95-218c-4748-a4d3-02ef390ad005" />

<img width="429" alt="Screenshot 2025-03-11 at 1 34 50 PM" src="https://github.com/user-attachments/assets/f1c62187-3946-4196-a05b-46a14c556c71" />

<img width="358" alt="Screenshot 2025-03-11 at 1 36 59 PM" src="https://github.com/user-attachments/assets/313fc60b-542a-4667-8a28-d844f885eb74" />



