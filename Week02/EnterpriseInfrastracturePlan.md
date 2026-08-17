 Enterprise Infrastructure Plan

ABC Startup Solutions

Course:ITEP 414 – System Administration and Maintenance
Program:Bachelor of Science in Information Technology
Student: Vianca Jill L. Ramos
Week: 2
Project Type: Individual Portfolio Project



PART 1 – Company Profile

Company Name

ABC Startup Solutions

 Nature of Business

ABC Startup Solutions is a startup software development company that provides web and mobile application development, IT solutions, and technical support services to small and medium-sized businesses.

Company Vision

To become a trusted technology partner for growing businesses by providing reliable, secure, and practical digital solutions.

Company Mission

To develop useful software, provide dependable IT services, and create a workplace where technology supports productivity, collaboration, and continuous learning.

Office Location

2nd Floor, Santa Rosa Business Center, Brgy. Balibago, Santa Rosa, Laguna

*Note: The location is fictional and is used only for academic purposes.*

Organizational Structure

text id="q0z6h1"
                    General Manager
                          │
        ┌─────────────────┼─────────────────┐
        │                 │                 │
       IT                HR              Finance
        │
        │
      Sales


The company has four main departments: Information Technology, Human Resources, Finance, and Sales.

The IT Department is responsible for maintaining the company's computers, network infrastructure, servers, software, security, backups, and technical support.

Employee Distribution

| Department             | Employees | Main Responsibilities                                   |
| ---------------------- | --------: | ------------------------------------------------------- |
| Information Technology |         5 | Software development, technical support, infrastructure |
| Human Resources        |         4 | Employee records, recruitment, administration           |
| Finance                |         5 | Accounting, financial records, budgeting                |
| Sales                  |         6 | Client communication, marketing, sales activities       |
| TOTAL                  |    20|                                                         |

PART 2 – Enterprise Hardware Inventory

The following hardware inventory was designed based on the company's 20 employees and its expected daily operations.

| Asset ID | Hardware                    | Quantity | Department             | Purpose                                       |
| -------- | --------------------------- | -------: | ---------------------- | --------------------------------------------- |
| HW-001   | Business Desktop PC         |       18 | HR, Finance, Sales, IT | Standard workstation for employees            |
| HW-002   | Business Laptop             |        2 | IT                     | Portable administration and technical support |
| HW-003   | Business Server             |        1 | IT                     | Internal services and server workloads        |
| HW-004   | Business Router             |        1 | IT                     | Routing, DHCP, VPN and gateway services       |
| HW-005   | 48-Port Managed Switch      |        1 | IT                     | Wired connectivity and VLAN management        |
| HW-006   | Multifunction Laser Printer |        2 | HR, Finance            | Printing and scanning                         |
| HW-007   | UPS                         |       22 | All Departments        | Protection from power interruptions           |
| HW-008   | Wi-Fi 6 Access Point        |        3 | All Departments        | Wireless network coverage                     |
| HW-009   | NAS Storage                 |        1 | IT                     | Backup and centralized storage                |
| HW-010   | External Backup Drive       |        2 | IT                     | Offline backup storage                        |
| HW-011   | 24-inch Monitor             |       20 | All Departments        | Primary display for employees                 |

 Hardware Justification

The company has 20 employees, so the plan provides 18 desktop computers and two laptops. Desktop computers are suitable for employees who normally work from the office, while laptops provide mobility for IT staff.

A 48-port managed switch was selected because the company needs enough network ports for computers, printers, servers, access points, and future devices. It also supports VLAN segmentation.

Three wireless access points are recommended to provide reliable Wi-Fi coverage across the office floor.

A UPS is recommended for every employee workstation, as well as the server and network equipment, to protect devices from unexpected power interruptions.

The NAS and external backup drives provide additional protection for important company data.

PART 3 – Enterprise Software Inventory

| Software                        | Version                   | License               | Purpose                                         |
| ------------------------------- | ------------------------- | --------------------- | ----------------------------------------------- |
| Windows 11 Pro                  | Current supported release | Commercial            | Primary operating system for employee computers |
| Ubuntu Server                   | 26.04 LTS                 | Open Source           | Server operating system                         |
| Microsoft 365 Business Standard | Current plan              | Subscription          | Office productivity and collaboration           |
| Visual Studio Code              | Current Stable            | Free                  | Software development and code editing           |
| Git                             | Current Stable            | Open Source           | Version control                                 |
| GitHub Desktop                  | Current Stable            | Free                  | Git repository management                       |
| VirtualBox                      | Current Stable            | Open Source           | Virtual machine testing                         |
| Google Chrome                   | Current Stable            | Free                  | Web browsing and application testing            |
| Microsoft Defender              | Built-in                  | Included with Windows | Endpoint protection                             |
| AnyDesk                         | Business Plan             | Commercial            | Authorized remote support                       |
| 7-Zip                           | Current Stable            | Open Source           | File compression and archive management         |

 Software Justification

 Windows 11 Pro

Windows 11 Pro is recommended for employee workstations because it provides business-oriented security and management features.

Ubuntu Server

Ubuntu Server provides a reliable Linux platform for internal services and server workloads.

Microsoft 365

Microsoft 365 provides productivity applications such as Word, Excel, PowerPoint, Outlook, and collaboration services.

 Visual Studio Code

Visual Studio Code is useful for the IT Department because employees can use it for programming, configuration files, scripts, and documentation.

Git

Git is important for version control, especially because the company develops software.

GitHub Desktop

GitHub Desktop provides a graphical interface that makes Git operations easier to manage.

### VirtualBox

VirtualBox allows IT personnel and developers to create virtual machines for testing.

### Google Chrome

Chrome is required for web browsing, web application testing, and cloud-based services.

Microsoft Defender

Microsoft Defender provides endpoint protection against malware and other common threats.

AnyDesk

AnyDesk can be used by authorized IT personnel for remote technical support. Access should be controlled and monitored.

7-Zip

7-Zip allows employees and IT personnel to compress and extract files efficiently.

PART 4 – Enterprise Network Inventory

| Network Equipment     | Quantity | Recommended Specification       | Purpose             |
| --------------------- | -------: | ------------------------------- | ------------------- |
| ISP Modem/ONT         |        1 | Business-grade fiber modem/ONT  | Internet connection |
| Business Router       |        1 | VLAN, DHCP, VPN and QoS support | Network routing     |
| Firewall              |        1 | Next-generation firewall        | Network security    |
| Managed Switch        |        1 | 48-port Gigabit, VLAN capable   | Wired connectivity  |
| Wireless Access Point |        3 | Wi-Fi 6 business AP             | Wireless access     |
| Patch Panel           |        1 | 48-port Cat6                    | Cable organization  |
| CAT6 Cable            |  2 boxes | 305 m per box                   | Network cabling     |
| RJ45 Connectors       |      100 | Cat6 compatible                 | Cable termination   |

Network Design Considerations

The network should use structured CAT6 cabling and a managed switch.

The router will handle network routing and DHCP services, while the firewall will enforce security rules.

The managed switch will separate departments using VLANs.

Wireless access points will provide separate staff and guest wireless networks.

PART 5 – Enterprise Network Diagram

Network Topology

<img width="1767" height="866" alt="network-draw io" src="https://github.com/user-attachments/assets/a52905e1-d703-4de6-9fa3-61ab7fa45b26" />


VLAN and IP Addressing Plan

|    VLAN | Network         | Department/Purpose         |
| ------: | --------------- | -------------------------- |
| VLAN 10 | 192.168.10.0/24 | IT                         |
| VLAN 20 | 192.168.20.0/24 | HR                         |
| VLAN 30 | 192.168.30.0/24 | Finance                    |
| VLAN 40 | 192.168.40.0/24 | Sales                      |
| VLAN 50 | 192.168.50.0/24 | Servers and Infrastructure |
| VLAN 60 | 192.168.60.0/24 | Guest Wi-Fi                |

Network Security

VLAN segmentation is used to reduce unnecessary communication between departments.

Finance and HR should have restricted access because they may handle sensitive company information.

The Guest Wi-Fi network should be isolated from internal company resources and should only provide internet access.

The firewall should control traffic between VLANs and allow only the services required by each department.

PART 6 – System Administration Roles

6.1 Helpdesk Technician

Responsibilities

A Helpdesk Technician provides first-level technical support to employees.

Responsibilities include:

* Troubleshooting computers
* Installing software
* Configuring workstations
* Assisting users with technical problems
* Managing support tickets
* Troubleshooting printers and peripherals
* Escalating complex problems

Skills

Important skills include:

* Customer service
* Communication
* Windows troubleshooting
* Basic networking
* Hardware troubleshooting
* Documentation
* Problem-solving

Common Tools

* Ticketing systems
* Remote support software
* Windows utilities
* Remote Desktop
* Basic network diagnostic tools
* Knowledge bases

### Certifications

A relevant entry-level certification is CompTIA A+.


6.2 Network Administrator

Responsibilities

A Network Administrator manages and maintains the company's network infrastructure.

Responsibilities include:

* Configuring routers
* Managing switches
* Configuring VLANs
* Managing IP addresses
* Maintaining Wi-Fi
* Configuring firewall rules
* Monitoring network performance
* Troubleshooting network problems

Skills

Important skills include:

* TCP/IP
* Subnetting
* Routing
* Switching
* VLANs
* Wireless networking
* Network security
* Troubleshooting

Common Tools

* Network device CLI
* Wireshark
* Network monitoring tools
* Ping
* Traceroute
* Configuration management tools

Certifications

A relevant certification is Cisco CCNA.


 6.3 Linux System Administrator

Responsibilities

A Linux System Administrator manages Linux-based servers and services.

Responsibilities include:

* Installing Linux
* Managing users
* Managing permissions
* Installing packages
* Managing services
* Managing storage
* Monitoring logs
* Performing backups
* Applying security updates

Skills

Important skills include:

* Linux command line
* Bash scripting
* Networking
* Storage management
* File permissions
* Service management
* Troubleshooting
* Security

Common Tools

* SSH
* Bash
* systemd
* journalctl
* apt
* cron
* firewall utilities
* monitoring tools

Certifications

A relevant certification is Linux Foundation Certified System Administrator (LFCS).

6.4 Cloud Administrator

Responsibilities

A Cloud Administrator manages cloud infrastructure and services.

Responsibilities include:

* Managing cloud servers
* Managing cloud storage
* Configuring cloud networks
* Managing user identities
* Monitoring cloud resources
* Managing cloud security
* Managing cloud backups

Skills

Important skills include:

* Cloud computing
* Cloud networking
* Identity and Access Management
* Virtualization
* Storage
* Monitoring
* Security
* Automation

Common Tools

* Cloud management portals
* Cloud CLI
* Infrastructure-as-Code tools
* Monitoring dashboards
* Identity management tools
* Cloud backup services

Certifications

A relevant certification is Microsoft Certified: Azure Administrator Associate (AZ-104).

---

 Collaboration Between the Four Roles

These four professionals work together to maintain a reliable IT environment.

The Helpdesk Technician handles user-facing technical problems and escalates complex issues. The Network Administrator manages network connectivity, VLANs, wireless infrastructure, and network security. The Linux System Administrator manages Linux servers and internal services. The Cloud Administrator manages cloud-based infrastructure and services.

They work together through incident escalation, documentation, monitoring, change management, and regular communication.

PART 7 – Infrastructure Recommendations

 7.1 Internet Provider

The company should subscribe to a business-grade fiber internet connection with an initial speed of approximately 300–500 Mbps.

This should be sufficient for 20 employees who use cloud applications, video meetings, software development tools, file sharing, and online services.

A static public IP can be considered if the company needs externally accessible services.

 7.2 Server Specifications

The recommended server should have:

* At least 8 CPU cores
* 32 GB ECC RAM
* SSD storage
* RAID 1
* Gigabit or faster network connection
* UPS protection
* Virtualization support

A business-class server provides better reliability and gives the company room to expand.

 7.3 Backup Strategy

The company should follow the 3-2-1 backup strategy.

This means:

* 3 copies of important data
* 2 different storage media
* 1 copy stored offline or offsite

The NAS can be used for regular backups.

External hard drives should be rotated and stored offline.

Important company data should also have an offsite or cloud backup.

Backup restoration should be tested regularly.

 7.4 Security Recommendations

The following security controls are recommended:

1. Next-generation firewall
2. VLAN segmentation
3. Multi-factor authentication
4. Strong password policy
5. Least-privilege access
6. Endpoint protection
7. Regular security updates
8. Secure Wi-Fi
9. Guest network isolation
10. Regular backups
11. Separate administrator accounts
12. Security awareness training

 7.5 Antivirus

Microsoft Defender should be enabled on all Windows computers.

Real-time protection, security intelligence updates, cloud protection, and Windows security updates should remain enabled.

As the company grows, a centrally managed Endpoint Detection and Response solution can be considered.

 7.6 Password Policy

Employees should:

* Use long and unique passwords.
* Avoid sharing passwords.
* Enable MFA whenever available.
* Use an approved password manager.
* Avoid reusing company passwords.
* Report suspected compromised accounts immediately.

Administrator accounts should be separated from normal user accounts.

7.7 Expansion Plan

The network should be designed with future growth in mind.

The 48-port managed switch provides additional ports for future employees and devices.

When the company approaches approximately 35–40 employees, the company should consider:

* Adding another managed switch
* Adding additional Wi-Fi access points
* Increasing server capacity
* Adding a second internet connection
* Improving centralized identity management
* Expanding cloud resources
* Increasing backup storage

 PART 8 – Personal Reflection

Working on this Enterprise Infrastructure Planning Project helped me understand that System Administration is not only about fixing computers or configuring networks. It also involves planning, documentation, decision-making, and understanding what a business needs before purchasing equipment.

One of the things I learned from this project was how to translate the needs of a 20-employee startup into actual hardware, software, and network requirements. I learned that every device included in an infrastructure plan should have a clear purpose and should support the company's daily operations.

The most challenging task for me was designing the network topology. I needed to think about where the router, firewall, switch, server, access points, printers, and department computers should be connected. Creating VLANs was also challenging because I needed to separate departments while still allowing them to access the services they need.

Planning is important before deployment because mistakes can become more difficult and expensive to fix after equipment has already been purchased and installed. A good infrastructure plan provides a clear guide for purchasing equipment, installing systems, configuring networks, protecting company data, and planning future upgrades.

This project will help me become a better System Administrator because I practiced technical documentation, inventory planning, network design, security planning, and infrastructure decision-making. It also taught me to think about the entire organization instead of focusing only on one computer or one technical problem.

Overall, this project showed me that a good System Administrator should be organized, careful, proactive, and willing to document technical decisions. I want to continue improving my knowledge in networking, Linux administration, cloud computing, cybersecurity, and automation so I can become more prepared for real-world IT environments.

 References

1. Microsoft – Windows 11 Security
   https://www.microsoft.com/en-us/windows/business/windows-11-security

2. Microsoft – Microsoft 365 Business Standard
   https://www.microsoft.com/en-us/microsoft-365/business/microsoft-365-business-standard

3. Cisco – CCNA
   https://www.cisco.com/site/us/en/learn/training-certifications/certifications/enterprise/ccna/

4. Linux Foundation – Linux Foundation Certified System Administrator
   https://training.linuxfoundation.org/certification/linux-foundation-certified-sysadmin-lfcs/

5. Microsoft Learn – Azure Administrator Associate
   https://learn.microsoft.com/en-us/credentials/certifications/azure-administrator/

6. Ubuntu Server Documentation
   https://ubuntu.com/server/docs/

