# 🖥️ SysAdmin Home Lab Portfolio

This repo documents my hands-on Linux system administration projects built using a home lab environment with AlmaLinux and VirtualBox. The labs are aligned with Red Hat Certified System Administrator (RHCSA) objectives, and are designed to show practical skill in real-world tasks such as user management, storage setup, automation, and web service deployment.

---

## 📁 Projects Breakdown

### ✅ Week 1: Basic Web Server Deployment
**Skills Practiced:** 
- NGINX installation and service management 
- Basic HTML hosting 
- Systemctl usage 
- Firewall rule configuration

**Highlights:** 
- Installed and started NGINX using `dnf` and `systemctl`
- Created a custom HTML page served from `/var/www/html/tylersite`
- Verified browser access to web server via VM IP
- Opened firewall port 80 using `firewall-cmd`

📷 *Screenshots included:* NGINX status, HTML content, browser result, firewall settings

---

### ✅ Week 2: LVM, User Management & Backup
**Skills Practiced:** 
- Adding and partitioning disks 
- LVM creation (`pvcreate`, `vgcreate`, `lvcreate`) 
- Mounting and formatting volumes 
- Creating users and groups 
- Permission management 
- Backup with `tar`

**Highlights:** 
- Created an LVM partition and mounted it to `/mnt/data`
- Created users `alice` and `bob`, assigned to a `devops` group
- Restricted directory access with proper group permissions
- Performed a system backup of `/etc` and verified it

📷 *Screenshots included:* LVM setup, users/groups, directory permissions, backup tarball

---

### ✅ Week 3: Bash Automation (in progress)
**Skills Practiced:** 
- Bash scripting
- Ansible playbook development
- Remote Host configuration using inventory files
- Password based SSH access
- Service and file deployment automation

**Highlights:** 
- Created `nginx_setup.sh` to automate full NGINX setup
- Wrote and executed a Bash Script to install ad configure an NGINX web server 
- Script configures and serves a custom HTML page
- Built an Ansible playbook that replicated the Bash script functionality
- Used a dynamic inventory file with Ansible to SSH into a remote VM and automate deployment
- Final page displayed: 'Deployed by Ansible Playbook' 
- Verified success via terminal and browser

📷 *Screenshots included:* Script execution, HTML output, browser deployment

---

## 🚀 Tech Stack

- AlmaLinux 9 (RHEL-based)
- VirtualBox
- Bash
- systemd (`systemctl`)
- firewalld
- tar
- chmod/chown
- nano
- LVM
- Ansible (planned)

---

## 📌 About This Lab

This lab is a self-directed initiative to deepen my Linux administration skills and prepare for the RHCSA exam. Every task was executed in a VM to simulate real-world sysadmin responsibilities like provisioning, automation, backup, and troubleshooting.

---

## 📬 Contact

**Tyler Jackson** 
GitHub: [@tjackson0801](https://github.com/tjackson0801) 
Email: tylerjackson1114@gmail.com 

---

> 💡 *This repo will continue growing as I add more RHCSA-aligned projects and explore tools like Ansible, cron jobs, system logging, SELinux, and networking.*
