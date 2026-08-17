Week 02 – Enterprise Infrastructure Planning
ABC Startup Solutions

Course: ITEP 414 – System Administration and Maintenance
Program: Bachelor of Science in Information Technology
Student: Vianca Jill L. Ramos
Project Type: Individual Portfolio Project

Project Overview

This project presents an initial IT Infrastructure Plan for ABC Startup Solutions, a fictional software development company with 20 employees working in a single office floor.

The company is starting from scratch with no computers, server, network, internet infrastructure, or security policies.

As a Junior System Administrator, I was tasked to plan the company's IT infrastructure before equipment and services are purchased.

The project includes hardware and software inventories, network equipment, network topology, system administration roles, infrastructure recommendations, security planning, backup strategy, and future expansion.

Learning Objectives

Through this project, I learned how to:

Analyze the IT requirements of a startup company.
Identify appropriate hardware and software requirements.
Prepare professional IT inventories.
Design a basic enterprise network topology.
Create a VLAN and IP addressing plan.
Understand different System Administration roles.
Recommend appropriate security and backup strategies.
Create professional technical documentation using Markdown.
Organize an IT infrastructure project using GitHub.
Company Scenario
Company Profile

Company Name: ABC Startup Solutions

Nature of Business:
ABC Startup Solutions is a software development company that provides web and mobile application development, IT solutions, and technical support services.

Vision:
To become a trusted technology partner for growing businesses by providing reliable, secure, and practical digital solutions.

Mission:
To develop useful software, provide dependable IT services, and create a workplace where technology supports productivity, collaboration, and continuous learning.

Office Location:
2nd Floor, Santa Rosa Business Center, Brgy. Balibago, Santa Rosa, Laguna.

Note: The location is fictional and used only for academic purposes.

Employee Distribution
Department	Employees
Information Technology	5
Human Resources	4
Finance	5
Sales	6
TOTAL	20
Hardware Inventory Summary
Hardware	Quantity	Purpose
Business Desktop PC	18	Standard employee workstations
Business Laptop	2	IT administration and mobility
Business Server	1	Internal services and server workloads
Business Router	1	Routing, DHCP and VPN
48-Port Managed Switch	1	Wired connectivity and VLANs
Multifunction Printer	2	Printing and scanning
UPS	22	Power protection
Wi-Fi 6 Access Point	3	Wireless network coverage
NAS Storage	1	Backup and file storage
External Backup Drive	2	Offline backup
24-inch Monitor	20	Employee displays
Software Inventory Summary
Software	Purpose
Windows 11 Pro	Primary desktop operating system
Ubuntu Server	Server operating system
Microsoft 365	Productivity and collaboration
Visual Studio Code	Software development
Git	Version control
GitHub Desktop	Git repository management
VirtualBox	Virtual machine testing
Google Chrome	Web browsing and application testing
Microsoft Defender	Endpoint security
AnyDesk	Authorized remote IT support
7-Zip	File compression and archive management
Network Inventory
Equipment	Quantity	Purpose
ISP Modem/ONT	1	Internet connection
Business Router	1	Routing and network services
Firewall	1	Network security
Managed Switch	1	VLAN and wired connectivity
Wireless Access Point	3	Wireless connectivity
Patch Panel	1	Structured cable organization
CAT6 Cable	2 boxes	Network cabling
RJ45 Connectors	100	Cable termination
Network Design
Proposed Network Flow
Internet
   │
   ▼
ISP Modem / ONT
   │
   ▼
Business Router
   │
   ▼
Firewall
   │
   ▼
48-Port Managed Switch
   │
   ├── IT Department
   ├── HR Department
   ├── Finance Department
   ├── Sales Department
   ├── Server
   ├── NAS Storage
   ├── Printers
   └── Wi-Fi Access Points
VLAN Plan
VLAN	Network	Department / Purpose
10	192.168.10.0/24	IT
20	192.168.20.0/24	HR
30	192.168.30.0/24	Finance
40	192.168.40.0/24	Sales
50	192.168.50.0/24	Servers and Infrastructure
60	192.168.60.0/24	Guest Wi-Fi

VLAN segmentation helps separate departments and reduces unnecessary access between different parts of the network.

For example, Finance and HR should have restricted access because they handle sensitive company information. Guest Wi-Fi should also be isolated from internal company resources.

System Administration Roles
Helpdesk Technician

A Helpdesk Technician provides first-level technical support to employees. Responsibilities include troubleshooting computers, installing software, assisting users, handling tickets, and escalating complex problems.

Important skills include communication, customer service, Windows troubleshooting, basic networking, and documentation.

Common tools include ticketing systems, remote support software, Windows utilities, and basic network troubleshooting tools.

A relevant certification is CompTIA A+.

Network Administrator

A Network Administrator manages the organization's network infrastructure.

Responsibilities include configuring routers, switches, firewalls, VLANs, wireless networks, IP addressing, monitoring, and troubleshooting.

Important skills include TCP/IP, subnetting, routing, switching, wireless networking, network security, and documentation.

A relevant certification is Cisco CCNA.

Linux System Administrator

A Linux System Administrator manages Linux-based servers and services.

Responsibilities include managing users, permissions, packages, storage, services, logs, backups, security, and automation.

Important skills include Linux command-line administration, Bash scripting, networking, storage management, troubleshooting, and security.

A relevant certification is Linux Foundation Certified System Administrator (LFCS).

Cloud Administrator

A Cloud Administrator manages cloud-based infrastructure and services.

Responsibilities include managing cloud servers, storage, networking, identity, monitoring, security, backups, and cloud resources.

Important skills include cloud networking, IAM, virtualization, storage, monitoring, security, and automation.

A relevant certification is Microsoft Certified: Azure Administrator Associate (AZ-104).

How They Work Together

The four professionals work together to maintain a reliable IT environment.

The Helpdesk Technician handles user issues and escalates problems that require deeper technical support. The Network Administrator manages network connectivity and security. The Linux System Administrator maintains Linux servers and internal services. The Cloud Administrator manages cloud-based resources and services.

They work together by sharing documentation, incident information, monitoring results, and change records. This cooperation helps prevent technical problems from affecting the entire organization.

Infrastructure Recommendations
Internet Provider

I recommend using a business-grade fiber internet connection with an initial speed of around 300–500 Mbps.

This should provide enough capacity for 20 employees using cloud applications, video meetings, software development tools, file transfers, and online services.

A static public IP can also be considered if the company needs externally accessible services.

Server Specifications

The company should use a business-class server with:

At least 8 CPU cores
32 GB ECC RAM
SSD storage
RAID 1 for important system storage
Gigabit or faster network connectivity
UPS protection
Virtualization support

A business-class server provides better reliability and makes future expansion easier.

Backup Strategy

The company should follow the 3-2-1 backup strategy.

This means:

At least 3 copies of important data
Stored using 2 different types of storage
At least 1 copy stored offline or offsite

The NAS can be used for regular backups, while external drives can be rotated for offline backup. Important business data should also have an offsite or cloud copy.

Backup restoration should be tested regularly.

Security Recommendations

The company should implement:

Firewall protection
VLAN segmentation
Multi-factor authentication
Strong passwords
Least-privilege access
Endpoint protection
Regular security updates
Secure Wi-Fi configuration
Guest network isolation
Regular backups
Separate administrator accounts
Security awareness training
Antivirus

Windows computers should use Microsoft Defender with real-time protection enabled.

Security intelligence and Windows updates should also be kept current.

As the company grows, it can consider a centrally managed Endpoint Detection and Response solution.

Password Policy

Employees should:

Use long and unique passwords.
Avoid sharing passwords.
Enable MFA whenever available.
Use a company-approved password manager.
Never reuse company passwords on personal websites.
Immediately report suspected compromised accounts.

Administrator accounts should be separated from normal user accounts.

Expansion Plan

The infrastructure should be designed for future growth.

The 48-port managed switch provides additional ports for future employees and devices.

When the company reaches approximately 35–40 employees, the company should consider:

Adding another managed switch
Adding more wireless access points
Upgrading server capacity
Adding another internet connection
Improving centralized identity management
Increasing cloud resources
Expanding backup storage
Technologies Used
Windows 11 Pro
Ubuntu Server
Microsoft 365
Visual Studio Code
Git
GitHub
GitHub Desktop
VirtualBox
Google Chrome
Microsoft Defender
VLAN
IPv4
CAT6 Ethernet
Wi-Fi 6
Firewall
NAS
Draw.io / diagrams.net
Challenges Encountered

The most challenging part of this project was designing the network topology and deciding how the departments should be separated.

I needed to consider the number of employees, required equipment, network connections, security, and future expansion.

Creating VLANs was also challenging because I needed to make sure that departments such as Finance and HR had appropriate separation while still allowing necessary communication with shared services.

Personal Reflection

Working on this Enterprise Infrastructure Planning Project helped me understand that System Administration is not only about fixing computers or configuring networks. It also involves planning, documentation, decision-making, and understanding what a business needs before purchasing equipment.

One of the things I learned from this project was how to translate the needs of a 20-employee startup into actual hardware, software, and network requirements. I also learned that every device included in an infrastructure plan should have a clear purpose.

The most challenging task for me was designing the network topology. I needed to think about where the router, firewall, switch, server, access points, printers, and department computers should be connected. Creating VLANs also helped me understand how network design can improve security by separating departments and limiting unnecessary access.

Planning is important before deployment because mistakes can become more difficult and expensive to fix after equipment has already been purchased and installed. A good infrastructure plan helps the organization understand what equipment is needed, how the network should be configured, how data should be protected, and how the infrastructure can grow in the future.

This project will help me become a better System Administrator because I practiced technical documentation, inventory planning, network design, security planning, and infrastructure decision-making. It also taught me to think about the entire organization instead of focusing on only one computer or one problem.

Overall, this project showed me that a good System Administrator should be organized, careful, proactive, and willing to document technical decisions. I believe these skills will help me as I continue developing my knowledge in networking, Linux administration, cloud computing, cybersecurity, and system administration.

References
Microsoft – Windows 11 Security
https://www.microsoft.com/en-us/windows/business/windows-11-security
Microsoft – Microsoft 365 Business Standard
https://www.microsoft.com/en-us/microsoft-365/business/microsoft-365-business-standard
Cisco – CCNA
https://www.cisco.com/site/us/en/learn/training-certifications/certifications/enterprise/ccna/
Linux Foundation – LFCS
https://training.linuxfoundation.org/certification/linux-foundation-certified-sysadmin-lfcs/
Microsoft Learn – Azure Administrator Associate
https://learn.microsoft.com/en-us/credentials/certifications/azure-administrator/
Ubuntu Server Documentation
https://ubuntu.com/server/docs/
