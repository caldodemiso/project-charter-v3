# 🧠 CIS 4860 — Managing Information Systems Projects

## HomeLab Implementation (Project Charter v3)

This repository hosts the project site and documentation for my **CIS 4860 – Managing Information Systems Projects** semester-long **HomeLab Implementation** at **California State University, Los Angeles**.

> 💡 This project provides a practical, low-cost framework that others can replicate to learn cybersecurity, smart-home integration, network monitoring, and containerized service management in a safe, self-hosted environment.

---

## 🚀 Project Overview

The **HomeLab Implementation Project** transforms a **Raspberry Pi 4B** into a miniature data-center environment to explore IT project execution from planning through delivery.  
It applies **PMI-based principles** of scope definition, scheduling, communication, and risk management to a hands-on technical system that simulates enterprise IT operations at a personal scale.

---

## 🎯 Project Objectives

- Apply structured **project-management methodology** to plan, execute, and monitor an IT implementation.
- Build a **segmented network** using Docker to isolate services for testing and security.
- Integrate **Apple HomeKit** via **Homebridge** for IoT automation and device control.
- Deploy a **self-hosted Minecraft server** to simulate multi-user network activity and remote access.
- Configure **Grafana + Prometheus** or **Uptime Kuma** dashboards for real-time performance monitoring.
- Implement a **NAS solution** for data storage and backup strategy.
- Document every stage and publish all configurations for others to replicate and learn from.

---

## 📦 Deliverables

### 🏠 Apple HomeKit Smart Home Integration

**Type:** Tangible  
**SMART Description:** Configure and control at least one Apple HomeKit device through Homebridge running in a Docker container on the Raspberry Pi by **Oct 8 2025**.  
**Definition of Done:** Device successfully paired with Homebridge; controllable via Apple Home app; screenshots and setup guide posted to GitHub.

---

### 🔐 Cybersecurity Practice – Segmented Test Environment

**Type:** Tangible  
**SMART Description:** Configure a segmented network using Docker networks and at least two containers (**firewall + client**) by **Oct 15 2025**.  
**Definition of Done:** Containers deployed; network segmentation tested; firewall rules documented; traffic isolation validated.

---

### 🎮 Self-Hosted Minecraft Server

**Type:** Tangible  
**SMART Description:** Deploy a functioning Minecraft server with user access and backup plan by **Oct 22 2025**.  
**Definition of Done:** Server online; at least one external connection tested; configuration and troubleshooting documented.

---

### 📊 Monitoring & Dashboard

**Type:** Intangible  
**SMART Description:** Implement monitoring using **Grafana + Prometheus** or **Uptime Kuma** by **Nov 1 2025**.  
**Definition of Done:** Metrics collected; dashboards viewable; alerts configured; screenshots included.

---

### 💾 Network Attached Storage (NAS) Setup

**Type:** Tangible  
**SMART Description:** Configure NAS using **TrueNAS** or **OpenMediaVault** by **Nov 10 2025**.  
**Definition of Done:** NAS deployed and accessible; file sharing configured; backup strategy documented.

---

## 🧩 Project Methodology

- **Framework:** PMI-aligned hybrid methodology (predictive planning + iterative updates).
- **Tools:** Notion Kanban for task tracking, GitHub Pages for documentation, and Raspberry Pi for hardware execution.
- **Process:** Weekly status reports + charter revisions to track scope alignment and risk mitigation.

---

## 🖥️ Live Project Site

🔗 **[https://caldodemiso.github.io/project-charter-v3/](https://caldodemiso.github.io/project-charter-v3/)**

The site includes:

- Full **Project Charter v3**
- **Status Reports** (Weeks 6–current)
- **Project Plan Updates**
- **Embedded Notion Kanban** for live progress tracking

---

## ⚙️ Technical Stack

| Category               | Tools / Tech                                        |
| ---------------------- | --------------------------------------------------- |
| **Hardware**           | Raspberry Pi 4B (8 GB RAM)                          |
| **OS**                 | Raspberry Pi OS (Lite 64-bit)                       |
| **Containerization**   | Docker + Docker Compose                             |
| **IoT**                | Homebridge (Apple HomeKit)                          |
| **Monitoring**         | Grafana / Prometheus / Uptime Kuma                  |
| **Security & Network** | iptables, Docker network segmentation               |
| **Storage**            | TrueNAS / OpenMediaVault                            |
| **Documentation**      | HTML / CSS / JS (GitHub Pages) + Notion Integration |

---

## 🧾 Repository Structure

project-charter-v3/
├── index.html # Main project site (charter, reports, embeds)
├── assets/ # Images, CSS, JS, and UI elements
├── docs/ # Additional supporting files
├── README.md # Project documentation (this file)
└── .gitignore

---

## 🧠 Learning Outcomes

- Applied **project-management principles** (scope, schedule, risk, communication) to a real technical project.
- Practiced **adaptive planning and status reporting** through weekly deliverables.
- Strengthened hands-on skills in **containerization, IoT integration, monitoring, and network security**.
- Produced a **replicable HomeLab template** for educational and professional use.

---

## 👩‍💻 Author

**Wendy Buonavita**  
Computer Information Systems Student | California State University, Los Angeles  
📧 [buonawen@gmail.com](mailto:buonawen@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/buonawen/) | [GitHub](https://github.com/caldodemiso)

---

> 💬 _“Build → Break → Learn → Repeat — that’s how you grow as an engineer.”_
