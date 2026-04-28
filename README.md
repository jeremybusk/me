# **JEREMY BUSK**
Lehi, Utah | jeremybusk@gmail.com | Mobile available on request  
LinkedIn: [https://www.linkedin.com/in/jeremy-busk/](https://www.linkedin.com/in/jeremy-busk/)  
GitHub (Personal): [https://github.com/jeremybusk](https://github.com/jeremybusk) | GitHub (Uvoo): [https://github.com/uvoo](https://github.com/uvoo)  
Tech Wiki / Scratchpad: [https://tech.uvoo.io/](https://tech.uvoo.io/) | Resume Repo: [https://github.com/jeremybusk/me](https://github.com/jeremybusk/me)

## **PROFESSIONAL SUMMARY**
Senior infrastructure, systems, network, security, and software engineer with deep experience designing and building secure, scalable, cost-effective information systems. Strong background across Linux, networking, observability, automation, CI/CD, virtualization, containers, databases, application delivery, and security-focused architecture.

I like to model, architect, build, and operate systems that are stable, performant, manageable, secure, and useful. I prefer open source and open projects whenever possible because of the flexibility, transparency, scale, and security benefits they can provide. I do not avoid commercial software when it is the right tool, but I prefer systems that remain understandable, controllable, and cost-effective. Five nines (99.999% availability) approach from my first day out of university.

My work is usually hands-on from research and architecture through implementation, automation, deployment, monitoring, and long-term operations. I have a strong bias toward getting things done, avoiding vaporware, using proven methods when they work, and building solutions that can scale beyond their initial use case. I like choosing best of breed & hate vendor lock-in so always have an alternative solution.

I have a deep security background, so I tend to build with security in mind from the beginning. I also have broad experience across all layers of the OSI model, from packet-level troubleshooting and firewall design to application-layer reverse proxies, APIs, databases, monitoring platforms, and full-stack internal tools.

## **TECHNICAL SKILLS & QUALIFICATIONS**
* **Core Strengths:** Deep experience with IP-based systems, networked applications, complex infrastructure environments, all seven layers of the OSI model, and packet-level troubleshooting (Wireshark, tcpdump, tshark).
* **Architecture & Engineering:** Distributed systems architecture, Linux infrastructure design, Network architecture, Systems engineering, Security-focused architecture, Datacenter and colocation infrastructure, Hybrid cloud and on-premises systems, Cost optimization, White-box hardware, Linux-based platforms.
* **Linux, Systems & Virtualization:** Linux (Red Hat, CentOS, Ubuntu, Debian, Alpine), Windows Server, Active Directory, CephFS, ZFS, LVM, EXT filesystems, QEMU/KVM/libvirt, Proxmox VE, VMware ESXi/vSphere/UCS, VirtualBox, LXD/LXC, Docker, Kubernetes, Shell operations, troubleshooting, logs, system services, patching, and hardening.
* **Networking & Protocols:** Routing and switching, Cisco, Brocade, Juniper, Linux networking, OSPF, BGP, BFD, RIP, HSRP, VRRP, IGMP, PIM, IPv4, IPv6, TCP, UDP, ICMP, SNMP, sFlow, NetFlow, syslog, IPMI, DNS, DHCP, NTP, TFTP, FTP, FTPS, SSH, SFTP, NFS, CIFS, iSCSI, SIP, SMTP, SMTPS, HTTP, HTTPS, SSL/TLS, IPsec, RADIUS, TACACS+, AAA.
* **Security:** Firewall architecture and operations, nftables, iptables, pfSense, Palo Alto, Check Point, Sidewinder, IDS/IPS (Suricata, Snort), Vulnerability assessment (OpenVAS, Nessus, nmap, Kali Linux), SELinux, Web filtering and DNS filtering, Host and network hardening, Security compliance and audit support, Secure architecture and access-control design.
* **Application Delivery L4/L7 & Web Infrastructure:** NGINX with Lua, HAProxy, F5 BIG-IP Tcl, Apache, IIS, Tomcat, Jetty, Reverse proxy design, HTTP header/body transformation, Application-layer access control, Load balancing and failover, TLS termination and certificate handling.
* **Databases, APIs & Data Modeling:** PostgreSQL, MySQL, SQLite, Redis, Microsoft SQL Server, InfluxDB, MongoDB, memcached, SQLAlchemy, PostgREST, JSON, XML, SOAP, Relational data modeling, Database-backed applications.
* **Automation, CI/CD & Configuration Management:** Bash, Python, Go / Golang, PowerShell, Lua, Tcl Expect, GitHub Actions, GitLab CI/CD, SaltStack, Ansible, Terraform.
* **Observability, Monitoring & Logging:** Zabbix, Prometheus, Grafana, Grafana Mimir, Loki, Alloy, InfluxDB v1/v2, Sumo Logic (Splunk/Elastic), Sensu Go, SolarWinds NPM, rsyslog, OpenSearch, Fluent Bit / Fluentd, OpenTelemetry, nfdump, SNMP polling and traps.
* **Identity, Authentication & Access:** Active Directory, LDAP / OpenLDAP, Entra ID, Keycloak, OAuth 2.0, OpenID Connect, FreeRADIUS, Custom identity datastores (PostgreSQL, MySQL, MSSQL, Redis).
* **Cloud & Platform Experience:** Azure (Kubernetes Service, Firewall, Load Balancer, Application Gateway, DNS, Monitor, Application Insights, Blob Storage, Disk Storage, Virtual Machines, App Services, IAM / Entra), AWS, Google Compute Engine, DigitalOcean, Hybrid VMware and Azure environments.
* **Web, UI & Internal Tooling:** Vite, React, Antd, npm, PostgREST, Postgres/plpythonu, SQLite, Go/Python. AI integration (OpenAI codex, Anthropic Claude, Gemini, GitHub CoPilot). Past Stacks: Python Flask, Python Pyramid, PHP, HTML5, JavaScript, TypeScript, jQuery, DataTables, Bootstrap, MDBootstrap, Ractive.js, Highcharts, C3.js / D3, Node.js, webpack, WordPress/Joomla.
* **Documentation & Project Tools:** Git, Markdown, mermaid, GitHub, GitLab, Jira, Confluence, MediaWiki, Vim, Visual Studio Code, nano.

## **PROFESSIONAL EXPERIENCE**

**Willis Towers Watson** | Draper, Utah  
**Site Reliability Engineer** | September 2019 – August 2025
* Role Overview: Managed infrastructure and systems with a team of SREs. Responsibilities included infrastructure operations, automation, monitoring, application delivery, scripting, systems management, and support for enterprise infrastructure environments.
* Created and managed Azure Kubernetes Service (AKS/K8S) multi-zone cluster CI/CD pipeline using GithubActions for Insights/Observability platform running Fluentbit, Grafana, Mimir, Loki, InfluxDB, miscellaneous monitoring related health cronjobs.
* Supported hybrid VMWare and Azure VMs/Containers as well as Intranet health checks for customer data exchanges (firewalled SFTP instances) and support apps like AWX for Ansible.
* Served as primary engineer on all L4/L7 Loadbalancers including F5 Big IP, HaProxy, NGINX, and Azure Application Gateway.
* Performed all design and administrative functions on F5 BIG-IP application delivery controllers and led repo creation/migration to Azure AGW.
* Implemented a multi-datacenter Zabbix monitoring system integrated with GitHub and Nexmo/PagerDuty for alerts.
* Created HAProxy loadbalancing Front-End for NetApp Object/Blob Storage using SaltStack state, saving hundreds of thousands of dollars compared to using F5 BIG-IP for the same purpose.
* Used existing monitoring templates and created new templates for performance tracking, security tracking, and notifications.
* Wrote extensive code and automation to complete infrastructure work using Bash, Python, and Go.
* Created and managed an SFTP data exchange app with GHA/SaltStack/Python on RHEL 7 to sunset Globalscape EFT as the primary secure data exchange for clients/carriers.
* Created dynamic filtering for simple IPS and enabled SMB tied into Active Directory for file management workflows.
* Executed migrations from multiple monitoring/observability platforms: Sensu to Zabbix, Zabbix to Grafana/Prometheus, and Grafana to Azure Monitor.
* Served as technical lead/support on private cloud to public cloud (Azure) migrations for multiple applications due to deep understanding of tech stack. Worked closely with Architects to do so.

**Pyrofex Corporation** | Utah  
**Site Reliability Engineer** | November 2017 – September 2019
* Converted to full-time permanent status following a successful contract-to-hire period via ConsultNet.
* Role Overview: Played the role of systems engineer, network engineer, SRE, and occasional full-stack developer to support hosted applications. Built and managed rack infrastructure from the ground up in an Agile environment. (Note: Still manage a full rack for them as needed).
* Used multiple virtualization and container technologies including QEMU/KVM/libvirt, VirtualBox, Docker, and LXD/LXC containers.
* Performed Terraform work using the libvirt provider and included cloud-init in VM automation work.
* Returned to classic Cisco IOS switch configuration and performed CI/CD automation with nftables.
* Utilized Prometheus, Grafana, and Zabbix for monitoring.
* Built an automated web repository for package deployment and customer downloads from CI/CD builds.
* Built a customer portal using Python Flask, PostgreSQL, LXD, and NGINX, connected with LXD for hosted containers (automated proxy port mapping, SSH key updates, authentication, 2FA).
* Used the customer portal and NGINX to control HTTP methods and requests to JSON-RPC interfaces on Bitcoin and Ethereum nodes.
* Contract Project Overview (via ConsultNet): Contracted for an international open-source blockchain project (rchain) using Scala. Supported development for 20-30 internal developers, handling CI/CD, releases, monitoring, automation, and infrastructure.
* Supported GitHub, Travis CI, and parallel GitLab.com CI/CD.
* Created and managed CI runners using Docker CE and VirtualBox.
* Handled releases, signing, and related processes.
* Wrote numerous DevOps scripts in Bash and Python (utilizing pylxd and docker-py).
* Managed infrastructure including Docker, LXD, KVM, AWS, DigitalOcean, Proxmox VE Cluster, and VirtualBox within a datacenter rack.
* Used SaltStack for mass management.
* Implemented Prometheus for metric collection and Zabbix for monitoring.

**Veracity Networks** | Utah  
**Software Engineer / Full Stack Developer** | October 2015 – September 2017
* Role Overview: Built web applications, portals, DNS-based filtering systems, notification systems, management tools, reports, and supporting infrastructure.
* Built an external trouble ticketing portal hooking into the existing database using PHP, Python, HTML5, jQuery DataTables, MDBootstrap, and PostgreSQL.
* Rewrote ticketing notifications using PostgreSQL notify functions and Python listeners.
* Built a fast DNS-driven web filtering solution for large college housing projects using PowerDNS Recursors, Lua, and Redis (similar to Cisco OpenDNS).
* Designed and built a management portal using PostgreSQL, PostgREST, OpenResty (NGINX + LuaJIT), Redis, Python, Bootstrap 3, HTML5, and Ractive.js.
* Used Redis with OpenResty for a fast session store and front-door access control.
* Built REST-style micro applications using Python Flask/Pyramid for provisioning email, automated replies, and Excel report generation (via Pandas).
* Maintained existing custom CRM heavily using Python Pyramid, SQLAlchemy, and PostgreSQL.
* Worked with Docker and LXD for development environments.

**Veracity Networks** | Utah  
**Network / Systems Architect / Engineer** | September 2005 – October 2015
* Role Overview: Designed, deployed, managed, automated, secured, and monitored large-scale network and systems infrastructure. 
* Installed and maintained 150+ active production physical/virtual hosts (CentOS, Red Hat, Ubuntu, Debian, FreeBSD) and numerous development hosts.
* Managed databases (PostgreSQL, MySQL, Redis, memcached, TimesTen, Informix, Oracle).
* Managed email systems for 10,000+ users and VOIP via BroadSoft BroadWorks.
* Secured host applications using netfilter, iptables, pfSense, and Palo Alto.
* Worked heavily with KVM, VMware, and Proxmox VE.
* Managed IPAM and DNS via customized NOC Project.
* Designed and deployed a Zabbix monitoring solution covering 15,000+ nodes and 1M+ active items across Linux systems, routers, and switches. Built custom scripts with low-level discovery.
* Performed extensive packet capture/analysis for troubleshooting.
* Created provisioning apps for L2/L3 switches, ATAs, and STBs using LAMP, Python, and Bash.
* Utilized SELinux access control on many systems.
* Designed customer inline web-filtering for FTTH communities using iptables, Squid, and DansGuardian. Created a spam mitigation system using Snort, iptables, and Python.
* Automated Cisco IOS, Brocade FOS, Adtran AOS, and Alcatel SROS devices.
* Served as primary network architect for Provo Municipal Fiber & Traverse Mountain FTTH redesigns, implementing Layer 3 networking and dynamic routing protocols (OSPF, RIP) to stabilize and scale the network.

**Defense Information Systems Agency (DISA)** | Hill Air Force Base, Utah  
**Information Systems Security Manager** | September 2003 – September 2005
* Served as Information Systems Security Manager for Microsoft Windows Top Secret systems and Unix HP-UX SCIF systems.
* Hardened systems, monitored security adherence, and assisted administrators with compliance.
* Managed security compliance using Symantec Enterprise Security Manager and custom DoD tools.
* Installed and managed Internet Security Systems Intrusion Detection System including database/sensor deployment, CSO training, and policy management.
* Managed Windows Server Update Services and created patching policies.
* Wrote custom Windows and *nix scripts for security tasks and data collection.

**Defense Information Systems Agency (DISA)** | Hill Air Force Base, Utah  
**Network Security Engineer** | August 2000 – September 2003
* Worked in a five-nines high-availability classified hosting datacenter.
* Served cross-discipline rotations in IBM Mainframe, Unix (Solaris, HP-UX, AIX), Windows, Security, and Unisys.
* Acted as primary protocol analyzer using Network Associates Distributed Sniffer, Sniffer Pro, Ethereal, and TCPDUMP.
* Installed and managed redundant Cisco PIX 535 firewall sets and Secure Computing Sidewinder application-layer firewalls.
* Installed Intel SSL Accelerator Appliance high-availability sets.
* Configured core network routers and L3 switches (Juniper M20, Cisco 7200/6500/5500/2900, Foundry FastIron).
* Designed and deployed a FIPS-compliant Cisco Aironet 802.11b wireless solution with AD integration.
* Headed external network scans, managed SurfControl Web Filter, and performed intrusion detection countermeasures.

## **EDUCATION**

**Utah State University** | Logan, Utah  
Master of Management Information Systems (Partial Program) | 2001 – 2002  
* Completed part of the program with a 3.5 GPA before putting it on hold to focus on professional projects.

**Utah State University** | Logan, Utah  
Bachelor of Science — Business Information Systems | 1994 – 1995, 1998 – 2000  
* Graduated Cum Laude with a 3.5 GPA. Took Engineering math/physics.

## **CERTIFICATIONS**
* Certified Kubernetes Administrator (CKA)

## **PROJECTS**
* **ClickHouse / HAProxy / Fluent Bit / MinIO Example:** Docker Compose example for log/data collection and storage patterns. ([https://github.com/jeremybusk/example-clickhouse/tree/main/docker-compose-clickhouse-minio-fluentbit-agg-haproxy](https://github.com/jeremybusk/example-clickhouse/tree/main/docker-compose-clickhouse-minio-fluentbit-agg-haproxy))
* **certctl:** X.509 public/private certificate management CLI. Designed to show architecture, security, and practical implementation ability around problems that often become overly complex. ([https://github.com/jeremybusk/certctl](https://github.com/jeremybusk/certctl))
* **email-relay:** Simple authenticated and IP-whitelisted SMTP relay for cases where SendGrid or other cloud platforms are not preferred. ([https://github.com/uvoo/containers/tree/main/uvoo/email-relay](https://github.com/uvoo/containers/tree/main/uvoo/email-relay))
* **mimirproxy:** Authentication proxy that injects X-Scope-OrgID for Grafana Mimir multi-tenancy and adds an org_id label. ([https://github.com/uvoo/containers/tree/main/uvoo/mimirproxy](https://github.com/uvoo/containers/tree/main/uvoo/mimirproxy))
* **demobox:** Containerized Ubuntu-based lab environment for learning Linux and basic services using LXD/Docker. ([https://github.com/jeremybusk/demobox](https://github.com/jeremybusk/demobox))
* **Open Source Project Contribution:** numifex ([https://gitlab.com/pyrofex/numifex](https://gitlab.com/pyrofex/numifex))
* Other examples available on request. Ask me for a current chronic problem you have and I'll build you a solution. I've done this through my career and actually love doing it.

## **ADDITIONAL INFORMATION & PREFERRED WORKING STYLE**
* **Working Style:** I prefer to work close to the system, usually from a terminal, and I value simple, understandable, secure, and maintainable designs. I like to compare technologies before choosing a direction and avoid lock-in when better options exist. I enjoy brainstorming, challenging assumptions, and building practical systems that work in production. I like taking lead and have continuously done so in my career. I'm extremely self-driven. No PM needed just ask my past PMs. I am comfortable working independently, but I also enjoy collaborating with strong teams where ideas are tested and improved. I prefer automation over repeated manual work and try to apply DRY principles wherever practical. I have been a primary lead in every company I've been with.
* **Values:** Ethics and values matter to me. I prefer to build technology that has positive value for the people who use it and the people affected by it. I view the ISC2 Code of Ethics as a good starting point (isc2.org/Ethics). I really like building solutions for difficult problems. The harder the better. If politics & posturing for personal gain (money/power) is your primary focus please don't ask me to be on your team.
* **Volunteer Experience:** Missionary for The Church of Jesus Christ of Latter-Day Saints (1996 – 1998).
* **Security Clearances:** Previously held Top Secret clearance with SCI access. (Investigation: 2000, Expired: 2007).

## **REFERENCES**
*(Happy to provide as many career and character references as requested. These are some of the more recent references.)*
* **Jens Christiansen** – Developer / Co-worker ([https://www.linkedin.com/in/jens-christiansen-23aa94101/](https://www.linkedin.com/in/jens-christiansen-23aa94101/))
* **David Thorne** – Manager ([https://www.linkedin.com/in/david-thorne-4866245/](https://www.linkedin.com/in/david-thorne-4866245/))
* **Justin Meiners** – Developer / Co-worker ([https://www.linkedin.com/in/justin-m-a1a234188/](https://www.linkedin.com/in/justin-m-a1a234188/))
* **Nash Foster** – CEO / Direct Report ([https://www.linkedin.com/in/nashef/](https://www.linkedin.com/in/nashef/))
