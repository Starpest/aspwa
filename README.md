# 🛠️ Automated Server Provisioning with Ansible

This project automates the provisioning and configuration of a secure Ubuntu server using [**Ansible**](https://www.ansible.com/). It sets up [**Nginx**](https://nginx.org/), [**Docker**](https://www.docker.com/), [**UFW**](https://wiki.ubuntu.com/UncomplicatedFirewall), [**Fail2Ban**](https://www.fail2ban.org/), and common packages—all with one command.

---

## 📌 Features

- ⚙️ Installs and configures:
  - [Nginx](https://nginx.org/)
  - [Docker & Docker Compose](https://docs.docker.com/)
  - [UFW (Uncomplicated Firewall)](https://wiki.ubuntu.com/UncomplicatedFirewall)
  - [Fail2Ban](https://www.fail2ban.org/wiki/index.php/Main_Page)
  - Essential packages and system updates
- 🔐 Enforces basic server hardening
- 📦 Modular [Ansible roles](https://docs.ansible.com/ansible/latest/user_guide/playbooks_reuse_roles.html)
- 🧪 Easy to test locally with [Vagrant](https://www.vagrantup.com/) or deploy to remote VPS/cloud

---

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/your-username/automated-server-provisioning.git
cd automated-server-provisioning
