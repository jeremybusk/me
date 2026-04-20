# Jeremy Busk


Lehi, UT 84048 - USA • Mobile on Request • [jeremybusk@gmail.com](mailto:jeremybusk@gmail.com)
GitHub: /jeremybusk • /uvoo

---

# SENIOR ARCHITECT / ENGINEER / DEVELOPER

**Observability • Performance • Security • Distributed Systems • Open Source Platforms**

My current focus is **architecting, engineering, and developing systems that support observability, performance, and security** using **white-box hardware, open-source software, Linux-based platforms, projects under the Linux Foundation and Cloud Native Computing Foundation ecosystems, plus custom code/scripts when needed.**

Strong hands-on background spanning architecture, backend engineering, frontend development, networking, automation, Kubernetes platforms, Linux systems, telemetry pipelines, and operational excellence. Proven ability to rapidly solve difficult problems and deliver production-ready systems independently or in lean teams.

---

# CURRENT TECHNICAL FOCUS

### Languages / Development

* Go
* Python
* React
* JavaScript / TypeScript
* Bash / Shell scripting

### Databases / Data Platforms

* PostgreSQL/cloudnative-pg
* Common PG extensions: TimescaleDB, plpython3u, PostGIS, cstore_fdw, pg_cron)
* PostgREST
* Redis/Dragonfly
* ClickHouse
* SQLite

### Observability / Monitoring

* Prometheus
* Grafana Labs stack
* Loki
* Mimir
* Tempo
* Alloy
* OpenTelemetry
* Fluent Bit
* Packet capture / analytics tooling
* Custom tooling, primarily using Go & SQL stores, as needed.

### Distributed Event Streaming Pub/Sub

Apache Kafka or the lighter non-Java using NATS - You can use cloud like Azure Event Hubs & others but Kafka ecosystem is tough to beat.

### Infrastructure / Platforms

* Linux (Debian / Ubuntu / RHEL)
* Kubernetes (kubeadm)
* Docker
* LXD / LXC
* QEMU
* KVM
* VMware (migrations to new platforms)
* Proxmox
* OKD/OpenShift, Podman - Note, I only played with it a long time ago when it still was OpenShift Origin but this is a great security focused platform that should be considered.

### Networking / Security

* BGP
* FRRouting
* MetalLB
* Netfilter / nftables / iptables
* eBPF / XDP / TC
* Wireshark / tshark / tcpdump
* IDS / IPS
* IAM / OAuth2 / OIDC / JWT / LDAP / AD
* CNI: Cilium, Calico, and Kubenet but mostly Cilium now unless reason not to
* Container runtimes: Containerd and CRI-O (CRI-O on K8s)

### Service Proxy

* NGINX
* HAProxy
* Envoy

### Storage / Distributed Systems

* ZFS
* Ceph (RBD / RGW) usually using Rook Ceph in Kubernetes.
* Blob/Object Storage (S3 / Azure / MinIO compatible)
* Distributed systems design

### Public Cloud

* For cost & security reasons I usually recommend only using public cloud for small to medium shops.
* I also try and be selective of technology when architecting information systems in order to avoid cloud computing platform lock-in.
* Azure(most hands-on experience), GCP, AWS. Understanding how technologies work under the hood makes it easier to jump between, especially with AI how-to summaries.

### AI
Primarily Codex/ChatGPT but open to whatever is best for the task at hand. I do caution on becoming over reliant on agents.

---

# CORE EXPERTISE

* Distributed Systems Architecture & Design
* Observability Platforms for Performance & Security
* Full-Stack Engineering (Go + React + PostgreSQL)
* Kubernetes & Container Platforms
* Linux Infrastructure Engineering
* Network Architecture & Routing
* Security Engineering & Hardening
* Custom Tooling & Automation
* Cost-Efficient Self-Hosted Platforms
* Rapid Delivery of Complex Solutions

---

# RECENT SELECTED PROJECTS

These days, I usually use AI ChatGPT/codex or sometimes Gemini but can do it without it just takes me a lot longer.  

### unode (current primary project)

Go, PostgreSQL based server, agent that creates an automation, security, performance monitoring/management tool similar to Tanium/CrowdStrike Falcon for endpoints like Wndows, Linux & Darwin/MacOS. It uses custom shell commands, gopsutil, state enformacement using SaltStack/Ansisble yaml config templates to control the nodes.  Also can manage AntiVirus like Defender or ClamAV.

### certctl

X.509 certificate lifecycle management CLI for public/private PKI.
GitHub available upon request.

### Various Container Systems

Custom containerized services including PostgreSQL, mail relays, application platforms, and utility services.

### Custom Network Tooling

Developed eBPF/XDP-based firewall, intrusion prevention, tcp/http proxies, network metrics, packet capture, and traffic analysis systems.

### Observability Platform Design

Built cost-efficient logging / metrics / monitoring platforms using Grafana ecosystem tools running on AKS with blob/object storage backed retention.

### Long-Term Log Archiver

Created compressed, time-partitioned archival and query systems for large-scale telemetry retention.

### ucontrol

PostgreSQL/PostgREST first using plupythonu extention that provides automation platform that uses websockets/Postgres Pub/Sub to provide a secure simplistic REST API. Built yaml/json config files to easily add/update new table columns. React & Ant Design antd for front-end. Consists of postgres(cnpg), postgrest, ucontrol-ui, ucontrol-ws pods. Performs X.509/SSH certificate management with automation like updating different keystores like PKCS12 stores. It's also enables internal ticketing, mintoring, wiki other useful internal tools.

---

# PROFESSIONAL EXPERIENCE

## Willis Towers Watson — Utah

### Site Reliability / Infrastructure Engineer / Technical Lead

**2019 – 2026**

* Led infrastructure, reliability, and observability initiatives across Kubernetes and Azure environments
* Built custom automation and internal tooling using Go, Python, and Bash
* Designed logging, metrics, and monitoring systems using Grafana, Loki, Mimir, Prometheus
* Worked across IAM, Terraform, CI/CD, GitHub Actions, enterprise services

---

## Pyrofex Corporation — Utah

### Site Reliability Engineer

**2017 – 2019**

* Architected CI/CD pipelines and automation systems
* Built on-premise and colocation infrastructure using white-box hardware and Linux
* Managed security controls, firewalling, and deployment platforms

---

## Veracity Networks — Utah

### Software Engineer / Full Stack Developer

**2015 – 2017**

* Developed internal and customer-facing systems using Python, PHP, JavaScript, and PostgreSQL
* Senior escalation point for infrastructure and software issues

### Network / Systems Architect & Automation Developer

**2005 – 2015**

* Designed and operated geographically distributed infrastructure using open source and white-box hardware
* Built provisioning, monitoring, observability, and automation systems
* Supported thousands of network devices (Cisco, Juniper, MikroTik, others)
* Top escalation engineer for datacenter systems and software platforms

---

## Defense Information Systems Agency — Hill Air Force Base, Utah

### Information Systems Security Manager

**2003 – 2005**

* Managed security for Unix and Windows systems in secure environments
* Conducted compliance and vulnerability assessments

### Network Security Engineer

**2000 – 2003**

* Designed firewall clusters and secure network architectures
* Performed packet-level troubleshooting and security assessments

---

# EDUCATION

## Utah State University

Bachelor of Science, Business Information Systems (Cum Laude) 2000

---

# CURRENT CERTIFICATIONS

* Certified Kubernetes Administrator (CKA) – 2025

---

# ADDITIONAL

* Former Top Secret / SCI Clearance (expired)
* 25+ years Linux and open-source experience
* Strong preference for practical, cost-efficient, platform-independent systems
* Comfortable leading initiatives, working in/with small or large teams or executing independently
* Passion for solving difficult engineering problems quickly
