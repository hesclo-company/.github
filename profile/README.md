# HESCLO 
> ⚙️ UNDER CONSTRUCTION

**Regional. Secured. HESCLO.**  
Welcome to **HESCLO**, your European cloud provider with an uncompromising focus on **data protection**, **security**, and **complete data control**.

Our solution is designed for organizations that demand the highest levels of **data security**, **tenant isolation**, and **legally compliant data hosting**, with flexible deployment options: **Managed Private Cloud** or **Self-Hosted Infrastructure**.

---

## 🔐 Security Architecture

**HESCLO provides isolated, private clouds – no shared environments.**

- Each client receives a **dedicated, fully isolated VM** on our Proxmox infrastructure
- **No containerization, no shared environments**, minimizing risk of data leaks
- Access only via **highly secured VPNs**, **YubiKey-based authentication**, and **restricted east-west communication**
- Internal infrastructure such as database servers, control services & registry systems reside in **separate, isolated networks**
- Complete **end-to-end encryption** for storage and transmission

---

## ☁️ Managed Private Cloud

**Let HESCLO host and manage your cloud – with full control and scalability.**

- Pay a **monthly fee** to use your own private cloud environment
- Scale your infrastructure by adding **more servers** as needed
- Fully managed by HESCLO: software updates, backups, monitoring
- Ideal for organizations that want **turnkey cloud hosting** without maintaining hardware
- Includes access to all HESCLO services and modules

---

## 🖥️ Self-Hosted Option

**Run your own cloud infrastructure while keeping HESCLO tools.**

- Install and manage your own servers using **Proxmox VE**
- Full control over scaling, networking, and server management
- Benefit from HESCLO’s software stack, including monitoring, caching, and data management
- Suitable for organizations with **existing hardware** or **strict compliance requirements**

---

## ⚙️ Technology Stack

### 🖥️ Virtualization
- **Hypervisor:** Proxmox VE with KVM support
- **Tenant model:** 1 VM = 1 client (fully isolated)
- **Management:** HESCLO platform for secure cluster management, compatible with self-hosted setups

### 📊 Monitoring & Logging
- Zabbix for system monitoring
- Centralized audit and log management – segregated per tenant

### 🔒 Authentication & Access
- Mandatory YubiKey authentication for all logins
- Zero-trust network architecture
- Strict firewall rules between all internal components

---

## 📜 Data Protection & Compliance

- Fully **GDPR-compliant**
- Tenant data is **never aggregated, analyzed, or shared**
- Hosting takes place **exclusively in European data centers**
- Full transparency for both managed and self-hosted deployments

---

## 📥 Contact

📧 info@hesclo.com  
🌐 https://www.hesclo.com  
🏢 Headquarters: Germany  

---

<!-- > **© 2025 Hesclo Cloud Provider GmbH**  
> *Your Cloud. Your Control. Your Security.* -->
