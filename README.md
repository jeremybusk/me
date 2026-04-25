# Jeremy Busk
**Address:** Lehi, Utah USA 84048
**Mobile:** On Request | **Email:** jeremybusk@gmail.com
**GitHub Resume:** [jeremybusk/me](https://github.com/jeremybusk/me)

---

## Online Profiles & Repositories

* **Personal Git Repositories (Sandboxing & Ideas):**
    * [github.com/jeremybusk](https://github.com/jeremybusk)
    * [github.com/uvoo](https://github.com/uvoo)
* **Container Code:** [github.com/uvoo/containers](https://github.com/uvoo/containers)

### Example Personal Projects
* **[certctl](https://github.com/jeremybusk/certctl):** Simple yet extremely funcitonal X.509 CLI public/private certificate management tool.
* **[uvoo/containers](https://github.com/uvoo/containers):** Random containers built over the years for different functions, from authenticated email relays to custom PostgreSQL containers.

---

## Current Focus

I like to build highly performant, secure & available data systems. In my over 25-year career, I’ve done the nuts and bolts of many core functions in the information industry, especially around open-source projects and Linux. As such, I can see the forest and the trees. I’m primarily looking for difficult new projects as head/lead/senior architect/developer for new tools that could service internal needs or even be customer-facing. 

I like to control and deliver outcome-based solutions. I’m fine working in large teams but prefer smaller teams as it’s faster to get work done with a tendency for less waste. If it’s two people or just myself, that’s fine. If you want an intense, highly motivated employee that can self-manage, I’m your man. I hit the ground running. Just ask any of my past co-workers and managers. I’m passionate about work and solving difficult problems to improve the efficiency of the product. The harder, the better.

I am excellent at using best-of-breed tools for the task or application. Currently, I’m primarily focused on full-stack architecture and development for network-related software. I can build with or without AI, just a lot faster with it. I’ve been a fan of open source and Linux for over 25 years. I prefer to work with tools within the [CNCF umbrella](https://www.cncf.io/projects/) and write my own custom code when it doesn’t fit. In my home datacenter, I run a Kubeadm bootstrapped/managed Kubernetes cluster on Debian, which runs on top of VMs in an [LXD cluster](https://canonical.com/lxd). I try to avoid public clouds for obvious cost and security reasons; it’s quite easy and cheap to build your own. I feel the mindless march to the public cloud was a mistake for many, except for smaller shops where it definitely makes sense. If I do use the public cloud, I prefer to whitebox and avoid proprietary systems as much as possible. Kubernetes in any public cloud form is a great remedy for this.

My primary focus now is architecting and developing network applications using PostgreSQL (often PostgREST for a drop-in REST API), Go, and React, running in Docker containers on Kubernetes using Ingress NGINX/Envoy. I understand BGP and use [MetalLB](https://github.com/metallb/metallb) to interact with [FRRouting](https://github.com/frrouting/frr) running on a Linux firewall in my home datacenter using nftables to dynamically expose services. I’ve even written custom code for firewall and intrusion prevention using eBPF with XDP (eXpress Data Path) Traffic Control (TC), so I’m familiar with it and Cilium.

I’m a unicorn and a renaissance man. I think these are rare in the industry and as such I feel I am extremely valuable for solving all sorts of chronic pain points in a companies information systems. I usually build with AI (typically ChatGPT, Codex, Gemini in VS Code (at WTW I did use CoPilot when I had to) but can build using the old Google/Online docs way too. I feel this again makes me stand out from the crowd of other applicants as often I feel with AI people don't understand what AI is writing for them. I can design, understand the code created, and fix bugs/design flaws as needed. For specific needs, especially when rapid resolution of a difficult problem is necessary, I can be a tall glass of cold water on a hot summer day.

---

## Core Tools & Projects

### Monitoring & Logging
* **[Alloy](https://github.com/grafana/alloy):** Built an auth proxy in Go for Mimir running in k8s for this.
* **[Loki](https://github.com/grafana/loki):** Used to monitor Kubernetes and endpoints cost-effectively using blob storage. Used persistent volumes in k8s clusters to collect and ship to blob storage for the long term.
* **[Mimir](https://github.com/grafana/mimir):** Excellent for k8s via the Prometheus ecosystem. Used Kubernetes to store data on cheap blob storage like S3, MinIO, Azure Blob, and Ceph Object Gateway.
* **[Tempo](https://github.com/grafana/tempo):** Have not used this as much; usually rely on Azure Monitor & Application Insights, Wireshark, Azure tools, or custom code.
* **[OpenSearch](https://github.com/opensearch-project/opensearch) / [Elasticsearch](https://github.com/elastic/elasticsearch):** Prefer this or Loki over Sumo Logic or Splunk.
* **[Beats](https://github.com/elastic/beats)**
* **[Kafka](https://github.com/apache/kafka):** Or similar Go-based alternatives. Built an archiver tool for Sumo Logic to store extensive data (3+ years) to blob storage in time-partitioned zstd formats for cheap, long-term audit storage.
* **[Fluent Bit](https://github.com/fluent/fluent-bit):** Used for generic SNMP log collection (v2, v3) and shipped to Sumo Logic collectors.

### Networking & Security Utilities
* **[Wireshark](https://github.com/wireshark/wireshark):** GUI or scripted tshark to collect off firewalls or port mirrors (like Cisco SPAN) to send data to a Linux host. Lately, I've been building custom tools using eBPF, libpcap, and Go.
* **[osquery](https://github.com/osquery/osquery):** Used standalone or in applications to allow common SQL interfacing to query host system data.

---

## Skills

* **Application Delivery Controller:** NGINX, Envoy, HAProxy, F5 BIG-IP
  * Used LUA/TCL Customizing load balancing logic, parsing HTTP headers/content, modifying payloads, and directing traffic based on complex conditions.
* **Centralized Authentication:** OpenLDAP, Active Directory, Custom datastores (PostgreSQL, MySQL, MSSQL, Redis), OAuth 2.0, JWT, Social Media APIs/SDKs, Azure Microsoft Entra ID other IAMs.
* **CI/CD:** GitHub Actions, GitLab, Custom frameworks
* **Cloud:** Azure, AWS, GCP (Prefer building custom, scalable platforms, but adaptable to public cloud when required).
* **Containerization:** Kubernetes (Kubeadm), Docker, Linux Containers / LXC (LXD) containerd & cri-o
* **Database:** PostgreSQL (preferred, with TimescaleDB), MySQL, SQLite, TiKV / Redis, MongoDB, InfluxDB, Memcached
* **DHCP / DNS:** ISC DHCP, Dnsmasq, PowerDNS, CoreDNS, ISC BIND, F5 GTM, Azure DNS, Route53
* **File Systems:** ZFS, LVM, EXT, Ceph Block Device (RBD), Ceph Object Gateway (RGW) on Rook Ceph
* **Firewall:** Netfilter (nftables/iptables), pfSense, Checkpoint, Palo Alto, Cisco (Prefer Linux ecosystem tools. Proficient with eBPF/XDP/TC).
* **Front End:** JavaScript, ReactJS, Ant Design, HTML/CSS, jQuery, Bootstrap, Font Awesome, Highcharts.js
* **HTTP Server:** NGINX, Apache, Python, Tomcat, Jetty, IIS
* **IDS/IPS:** Suricata, Snort, Custom solutions
* **IPAM:** NOC Project, NetBox, ipplan
* **Key/Value Store:** Redis, RocksDB
* **Log Collection:** Sumo Logic, Splunk, ELK Stash, Clickbase, rsyslog
* **Message Broker:** Kafka (prefered), RabbitMQ, Custom brokers (PostgreSQL/NoSQL)
* **MTA/Email:** Zimbra, Postfix, qmail
* **Monitoring/Management:** Grafana, Prometheus, Alloy, Blackbox, Zabbix, ManageEngine, Nagios, OpenNMS, InfluxDB v1 & v2, Nagios, nfdump, custom
* **Network Configuration Management:** RANCID, NOC Project, SaltStack, Ansible/AWX, Custom (Python, BASH, NetBox)
* **NOS:** Cisco IOS, Arista EOS, Juniper, Brocade
* **OS:** Linux (Redhat/CentOS with SELinux/facls/auditd, Ubuntu/Debian AppAmor), Windows
* **OSI Model:** Deep understanding of IP-based communication protocols and applications.
* **ORM:** GORM, Bun, Ent, SQLAlchemy
* **Packet Analyzer Tools:** Wireshark, tshark, tcpdump, ngrep, Custom Go (pcap modules) & eBPG/XDP/TC on Linux, Azure Network Watcher
* **Programming Languages:**
    * *Applications:* Golang, Python
    * *Scripting:* BASH, SH, Python, PowerShell, TCL (Expect and F5), LUA
    * *Front-End:* JavaScript
* **Restful API:** PostgREST, JSON, XML SOAP, GraphQL
* **Version Control:** Git, GitHub, GitLab
* **Virtualization:** LXD, Proxmox VE, QEMU/KVM/libvirt, VMWare ESXi/vSphere, UCS, VirtualBox, Azure VMs
* **Vulnerability Assessment:** OpenVAS, Nessus, Nmap, Kali Linux, Custom Go scripts
* **Loadtesting: ** K6 & other custom built as needed.
* **Kubernetes: ** CRDS/Operators

Tech I'm looking into in the near future. Talso Linux for nodes in K8S clusters, OpenShift ecosystem, jaeger, cortex, NATS, Spark, Cassandra, Argo CI/CD for K8s

---

## Career History

### Willis Towers Watson
**Site Reliability / Infrastructure Engineer / Insights Technical Lead**
*Sept 2019 – Aug 2026 | South Jordan, UT*
* **Stack:** Azure, Kubernetes, Docker, VMware, Prometheus, Fluentd, Sumo Logic, Grafana, GitHub Actions, Terraform, BASH, Python, Go, Linux/Windows, PagerDuty, IAM.'
* Migrated primary platform monitoring from Sensu, to Zabbix, to Grafana Stack & Azure.
* I was a primary escalation point for mulitple teams, especially when a lot left in covid due to demand and helped mentor newer hires.
* Example Projects
  * Built an secure data exchange using SFTP on RHEL 7 for clients & carriers to securely exchange data in order to sunset Global Scape. State enforcement of app was applied on host through saltstack repo
  * I built Dell RHEL firewall cluster to Frontend & LB for NetApp Object Store.
  * I built many pipelines, often with short notice, for rapid migrations of services due to shifts in company business & technical strategies.
  * Create repo CI/CD for most used Azure Kubernetes Services cluster in our group for various hypbrid monitoring purposes including building a Terraform module for AKS usage with internal security complinance settings

### Pyrofex Corporation
**Site Reliability Engineer**
*Nov 2017 – Aug 2019 | Utah*
* CI/CD architect for GitHub repositories and automation.

### Veracity Networks
**Software Engineer / Full Stack Developer**
*2015 – 2017 | Utah*
* Used Python, PHP, JavaScript, HTML, and PostgreSQL to create website functions.
* Built Fiber Ticketing Tracking system
* Built custom DNS/BIND DHCP services for hyperscale
* Served as an escalation point for systems infrastructure and applications.

### Veracity Networks (was Broadweave)
**Network / Systems Architect / Engineer – Architecture & Automation Developer**
*2005 – 2015 | Utah*
* Designed and enforced monitoring over all services in a fast-paced start-up environment.
* Managed systems infrastructure, software applications, provisioning, and automation functions (Layer 1 through 7).
* Built highly available, cost-effective solutions using whitebox hardware, Linux and open-source software to control costs in multiple many data centers we owned.

### Defense Information Systems Agency (DISA)
**Information Systems Security Manager TS & SCIF Datacenters**
*2003 – 2005 | Hill Air Force Base, UT*
* Managed security of HP-UX, Solaris, RHEL(Linux) and Windows systems in a highly secure environment as a system engineer.
* ISS Internet Scanner, Nessus, Symantec Enterprise Security Manager for 

### Defense Information Systems Agency (DISA)
**Network Security Engineer**
*2000 – 2003 | Hill Air Force Base, UT*
* Lead engineer in designing, deploying, and managing firewall clusters and core network architecture Layers 1-7.
* Primary packet capture technology Ducle, Ethereal, tcpdump to troubleshoot applications and ran internal vulnerability assessment scans.

---

## Secondary Education

**Utah State University**
Bachelor of Science, Business Information Systems, Cum Laude 2000

## CURRENT CERTIFICATIONS

**Certified Kubernetes Administrator (CKA)** — 2025

---

## Previous Security Clearances
* **Top Secret with SCI Access:** Conducted in 2000. *(Expired 2007)*
