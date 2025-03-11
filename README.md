# ConDef: Enterprise-Level Defensive Security Lab

![Project Status](https://img.shields.io/badge/status-in%20progress-yellow)

A comprehensive defensive security lab simulating a full-scale enterprise network, integrating Windows, Linux, Kubernetes, and cloud services (AWS & Azure) to develop cybersecurity defense strategies.

## 📋 Overview

This project was created to simulate a complete corporate environment with a focus on defensive security strategies. The architecture implements multiple domains, services, and technologies to create a realistic environment for SOC analysis, incident response, and cyber threat investigation.

## 🏗️ Architecture

The environment includes:

- **Windows Server Environment** with Active Directory, DNS, and security monitoring
- **Linux Systems** with audit and monitoring configurations
- **Kubernetes Clusters** instrumented for security telemetry
- **Cloud Integration** via AWS and Azure for hybrid security solutions
- **SIEM Solutions** for centralized log collection and real-time security monitoring

## 🛠️ Implemented Technologies

- Active Directory and Windows Server
- Sysmon for advanced Windows endpoint monitoring
- Laurel/AuditD for Linux system auditing
- Kubernetes telemetry for container observability
- AWS and Azure service integration
- PCAP analysis for network monitoring
- Incident response workflows

## 📊 Simulation Scenarios

The lab includes pre-configured scenarios for:

- Persistence and lateral movement detection
- Real-time threat analysis
- Cross-platform incident response
- Forensic investigation in hybrid environments

## 🚀 Getting Started

See the [installation documentation](docs/installation.md) to set up your own ConDef environment.

## 📝 Documentation

- [Detailed Architecture](docs/architecture.md)
- [Installation Guide](docs/installation.md)
- [Monitoring Setup](docs/monitoring-setup.md)

## 📅 Development Roadmap

- [x] Windows Server environment with AD configuration
- [x] SIEM solutions implementation
- [x] Incident response workflow development
- [x] PCAP analysis and log monitoring
- [ ] Cloud integrations expansion
- [ ] Full detection and response automation

## 🔒 Security

This project is for educational and training purposes in controlled environments only.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
