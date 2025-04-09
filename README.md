# 🛡️ Cybersecurity Controls & Compliance Checklist

This project outlines key cybersecurity controls categorized into **Administrative**, **Technical**, and **Physical** domains, with associated **Control Types** (Preventative, Detective, Corrective, Deterrent). It also features a detailed compliance assessment for a fictional company, **Botium Toys**, based on standards such as **PCI DSS**, **GDPR**, and **SOC 1 & 2**.

![ChatGPT Image Apr 9, 2025 at 03_48_30 PM](https://github.com/user-attachments/assets/18011344-2f30-4f0f-8ab0-c457514fb0bc)

---

## 🔍 Control Categories Overview

| **Category**     | **Purpose**                                                                 |
|------------------|------------------------------------------------------------------------------|
| Administrative   | Policy-driven controls to manage data, employee access, and operations.      |
| Technical        | Systems and software like firewalls, IDS/IPS, antivirus, encryption.         |
| Physical         | Locks, CCTV, fire prevention – anything to restrict physical access.         |

---

## 🧩 Control Types

| **Type**       | **Function**                                                                 |
|----------------|--------------------------------------------------------------------------------|
| Preventative   | Stop incidents before they occur.                                             |
| Corrective     | Restore systems after an incident.                                            |
| Detective      | Identify if/when an incident has occurred.                                    |
| Deterrent      | Discourage potential threats from happening.                                  |

---

## 📋 Controls Implementation Status: *Botium Toys*

### 🔐 Administrative Controls

| Control                     | Type         | Status | Notes                                                                 |
|----------------------------|--------------|--------|-----------------------------------------------------------------------|
| Least Privilege            | Preventative | ❌     | All employees have full access to customer data.                      |
| Disaster Recovery Plans    | Corrective   | ❌     | No plan in place yet.                                                 |
| Password Policies          | Preventative | ❌     | Current password strength is minimal.                                 |
| Separation of Duties       | Preventative | ❌     | CEO manages too many critical functions.                              |

### 💻 Technical Controls

| Control                        | Type         | Status | Notes                                                                 |
|-------------------------------|--------------|--------|-----------------------------------------------------------------------|
| Firewall                      | Preventative | ✅     | Rules are well-defined.                                               |
| Intrusion Detection System    | Detective    | ❌     | Needs implementation.                                                 |
| Encryption                    | Deterrent    | ❌     | No encryption used for sensitive data.                                |
| Antivirus Software            | Corrective   | ✅     | Installed and regularly updated.                                      |
| Backups                       | Corrective   | ❌     | No regular backups for critical data.                                 |
| Password Management System    | Preventative | ❌     | Not implemented yet.                                                  |
| Legacy System Monitoring      | Preventative | ⚠️     | Monitoring exists but not regularly scheduled.                        |

### 🏢 Physical Controls

| Control                        | Type                     | Status | Notes                                                                 |
|-------------------------------|--------------------------|--------|-----------------------------------------------------------------------|
| Locks (office/store/warehouse)| Deterrent/Preventative   | ✅     | All locations are properly secured.                                   |
| CCTV                          | Preventative/Detective   | ✅     | Fully functional surveillance in place.                               |
| Fire Detection/Prevention     | Detective/Preventative   | ✅     | Proper alarms and sprinklers are installed.                           |

---

## 📜 Compliance Checklist Summary

### 💳 PCI DSS

- ❌ Encryption and password management lacking  
- ❌ All employees have full access to credit card data  

### 🇪🇺 GDPR

- ❌ Sensitive EU customer data not encrypted  
- ✅ Breach notification plan exists  
- ❌ Data not properly classified  

### 🔒 SOC (Type I & II)

- ❌ Least privilege and separation of duties missing  
- ❌ Sensitive data not encrypted  
- ✅ Data integrity ensured  
- ❌ Access control needs enforcement  

---

## ✅ Recommendations

- Implement **Least Privilege**, **Disaster Recovery**, **IDS**, **Encryption**, and **Password Management**
- Classify assets to better identify and apply relevant controls
- Enforce secure access controls and update compliance procedures

---

> **Note**: This project is for educational and demonstration purposes based on a fictional company.
