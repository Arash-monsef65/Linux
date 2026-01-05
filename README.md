# BIND Admin Panel

A modern, web-based management console for **BIND9 DNS Server** developed in **Golang**. This tool simplifies complex DNS configurations, provides real-time monitoring, and supports modern DNS protocols like DoH and DoT.

## 🚀 Features
* **Dashboard:** Real-time service status and quick actions like service restart and cache flushing.
* **ACL Management:** Easily manage access control lists in `named.conf.acls`.
* **Zone Management:** Create and manage Forward Zones via a user-friendly interface.
* **Global Settings:** Configure global forwarders and system-wide options.
* **Live Monitor:** Real-time DNS query logging and visualization.
* **DNS Tools:** Built-in Dig and Kdig tools supporting UDP, DoT (Port 853), and DoH (Port 443).
* **Security:** Supports DNS over TLS and DNS over HTTPS with easy certificate integration.
* **Multi-language:** Supports both Persian (RTL) and English (LTR) interfaces.

## 📋 System Requirements
* **OS:** Ubuntu 24.04 (Recommended).
* **Permissions:** Root or Sudo access is required.
* **Ports:** 80 (Web Panel), 53 (DNS), 853 (DoT), 443 (DoH).

## 🛠️ Installation
To install the BIND Admin Panel, clone the repository and run the installation script:
chmod +x bind-admin
sudo ./bind-admin
