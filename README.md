# Windows-Server-2022-HomeLab
A simulated **enterprise IT support environment** built using VirtualBox and Windows Server 2022.
This project replicates common Tier 1 / Tier 2 Help Desk tasks including **Active Directory, DNS, DHCP, Group Policy, and Powershell automation**.

---

## 🚀 Features
- Active Directory Domain Services (AD DS)
- DNS & DHCP configuration with scoped IP ranges
- Windows 10 client integration
- Group Policy Objects (GPO) for security & permissions
- User account management (password resets, group assignments)
- Printer & shared resource setup
- PowerShell automation for IT tasks

---

## 🛠️ Tools & Technologies
- **Virtualization:** Oracle VirtualBox  
- **Server OS:** Windows Server 2022  
- **Client OS:** Windows 10  
- **Scripting:** PowerShell

---

# Windows Server 2022 HomeLab - Visual Walkthrough

<p align="center">
  <b>1. Installed Windows Server 2022 in VirtualBox</b>
</p>

<p align="center">
  <img src="/HomeLab_Step1.webp" width="800">
</p>

---

<p align="center">
  <b>2. Promoted server to Domain Controller</b>
</p>

<p align="center">
  <img src="/HomeLab_Step2.webp" width="800">
</p>

---

<p align="center">
  <b>3. Configured DNS for domain resolution</b>
</p>

<p align="center">
  <img src="/HomeLab_Step3.webp" width="800">
</p>

---

<p align="center">
  <b>4. Set up DHCP scope for automatic IP assignments</b>
</p>

<p align="center">
  <img src="/HomeLab_Step4.webp" width="800">
</p>

---


<p align="center">
  <b>5. Joined Windows 10 clients to the domain</b>
</p>

<p align="center">
  <img src="/HomeLab_Step5.webp" width="800">
</p>

---


<p align="center">
  <b>6. Created and managed users & groups in Active Directory</b>
</p>

<p align="center">
  <img src="/HomeLab_Step6.webp" width="800">
</p>

---


<p align="center">
  <b>7. Applied Group Policies (GPOs) for password rules & permissions</b>
</p>

<p align="center">
  <img src="/HomeLab_Step7.webp" width="800">
</p>

---


<p align="center">
  <b>8. Tested user password resets and login policies</b>
</p>

<p align="center">
  <img src="/HomeLab_Step8_Pt1.webp" width="800">
  <img src="/HomeLab_Step8_Pt2.webp" width="800">
</p>

---



---

## 🔑 Key Learning Outcomes
- Gained hands-on experience with core IT infrastructure services
- Simulated real-world Help Desk troubleshooting workflows
- Practiced enterprise IT support concepts used in Tier 1/2 support roles

---

## 📌 Future Improvements
- Add Linux clients for cross-platform integration
- Implement remote management with RDP and Quick Assist
- Test backup & restore strategies
