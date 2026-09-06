# Alec Biddinger

## 👋 About Me

![profile view count](https://komarev.com/ghpvc/?username=alecbiddinger&abbreviated=true&style=plastic)

I am a Cybersecurity Management student at Northwood University graduating in May 2027. As an Information Technology Intern with the City of Traverse City, I have gained hands-on experience with CrowdStrike Falcon alert triage, Windows endpoint deployment, asset inventory, shadow-IT discovery, Microsoft 365, Google Workspace, and technical documentation.

I am building deeper security operations, detection engineering, and automation skills through Python, Linux, SQL, TryHackMe, Boot.dev, and independent security projects.

## Current Focus

- Expanding a virtual SOC lab for security monitoring, detection engineering, and incident investigation
- Validating Windows and Linux telemetry with Wazuh, Sysmon, and OpenSSH
- Developing Python tools for log analysis and security automation
- Strengthening practical Linux, networking, and SQL skills
- Preparing for the CompTIA Security+ exam

## Featured Projects

### [Virtual Home SOC Lab](https://github.com/alecbiddinger/Home-SOC-Lab)

I built the infrastructure for a virtual security operations environment hosted in Oracle VirtualBox. The project remains a work in progress and currently includes:

- A Wazuh all-in-one server for centralized security monitoring
- A Windows 11 Pro endpoint with the Wazuh Agent and Microsoft Sysmon
- An Ubuntu Server endpoint with the Wazuh Agent and OpenSSH
- A host-only lab network for VM communication, with separate NAT adapters for outbound updates
- Architecture, setup, troubleshooting, and security and privacy documentation

The infrastructure and endpoint enrollment phase is complete, with both monitored endpoints connected to the Wazuh dashboard. Building it required virtual network design, Windows and Linux administration, endpoint agent deployment, manual Wazuh client key enrollment, package installation troubleshooting, and clear technical documentation.

The next phase will validate telemetry from source to dashboard, generate controlled security events, develop repeatable detections, map observed behavior to MITRE ATT&CK, and document incident investigations. The goal is to demonstrate the complete analyst workflow: generate activity, collect evidence, detect, investigate, and improve.

### [Authentication Log Parser](https://github.com/alecbiddinger/Python-SIEM-Log-Parser)

A Python-based Linux authentication-log parser that:

- Parses Linux SSH authentication events
- Tracks failed logins by source IP address
- Detects possible brute-force behavior
- Identifies successful authentication following repeated failures
- Writes security alerts for analyst review

Planned improvements include structured output, timestamp extraction, IPv6 support, severity classifications, unit tests, and integration with the home SOC project.

## Technical Toolbox

### Security

- CrowdStrike Falcon
- Alert Triage
- Log Analysis
- Endpoint Security
- Asset Inventory
- Wazuh
- Microsoft Sysmon
- Security Monitoring

### Systems

- Windows
- Linux
- macOS
- Oracle VirtualBox
- Virtual Networking
- Microsoft 365
- Google Workspace

### Programming

- Python
- SQL
- Regular Expressions
- Git
- GitHub

### Certifications & Training

- Google Cybersecurity Professional Certification, Aug 2026
- TryHackMe SEC0, May 2026
- Boot.dev

## Education

### Northwood University

- Bachelor of Business Administration in Cybersecurity Management
- Minor in Management Information Systems
- Expected May 2027

## Connect

<a href="https://www.linkedin.com/in/alec-biddinger-4373502ab/">
  <img alt="LinkedIn" title="See More About My Professional Experiences at LinkedIn" src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white"/></a>

<a href="https://northwood.joinhandshake.com/profiles/am4yek">
  <img alt="Handshake" title="See More About My College Courses at Handshake" src="https://img.shields.io/badge/Handshake-D3FB52.svg?style=for-the-badge&logo=Handshake&logoColor=black"/></a>
