# Computer-Network-and-Security
# Virtualization & Networking Assignment

## 📋 Project Overview
A hands-on virtualisation and networking project using Windows Server 
and Windows 10 clients. Covers DHCP, DNS, file sharing, and system 
configuration within an isolated internal network.

## 🎯 Objectives
- Set up a virtualisation environment (Windows Server + 2× Windows 10)
- Configure internal networking between VMs
- Partition disks and enable System Protection
- Configure DHCP server
- Demonstrate DNS break-and-fix
- Set up shared folders with mapped drives
- Evaluate internet connection options
- Compare DHCP vs static IP addressing

## 🛠️ Technologies Used
- *Hypervisor:* (e.g., VirtualBox / VMware)
- *OS:* Windows Server, Windows 10
- *Services:* DHCP, DNS, File Sharing (SMB)

## 📁 Repository Structure
| Folder | Description |
|--------|-------------|
| docs/ | Written deliverables and explanations |
| evidence/ | Screenshots and configuration outputs |
| scripts/ | PowerShell setup scripts |

## 👥 Contributors
| Name | Contribution |
|------|--------------|
| Zandile Cele | Deliverable 4 setup, bulk of evidence (screenshots, config outputs) |
| Siyamthanda | Section 4.6 – Internet connection options evaluation |
| Mvuzo | Section 4.5 – DHCP vs static IP explanation with examples |

## 📄 Deliverables
- [Deliverable 4](./docs/deliverable-4.md)
- [Deliverable 5](./docs/deliverable-5.md)

## 🚀 How to Reproduce
1. Install a hypervisor (VirtualBox/VMware)
2. Create 3 VMs: 1× Windows Server, 2× Windows 10
3. Configure an internal network (no NAT)
4. Follow scripts/ in order
5. See evidence/ for expected outputs

## 📝 License
See [LICENSE](./LICENSE)
