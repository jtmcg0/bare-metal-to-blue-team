![Title Image](images/BareMetalToBlueTeam.png)
# BM2BT Phase 1 - Initial Setup
The purpose of this project is to develop and demonstrate practical skills in: 
- Virtualization
- Windows and Linux Administration
- Networking
- Identity Management
- Security Monitoring
- Automation
- Infrastructure Troubleshooting.
## A Hands-on Systems Administration And Cybersecurity Lab Built On Proxmox VE
### <u>Initial Hardware Specs</u>
- Refurbished Dell Precision T5810
- Intel Xeon E5-2680 v3 Processor
- 12 cores / 24 threads
- 64 GB DDR4 ECC RAM
- 480 GB SSD
- Proxmox VE hypervisor

The refurbished Dell server was chosen for its balance between price and power. At a very reasonable cost, the machine provides enough RAM and processing power to run several virtual machines at the same time without any significant lag or delays.
### Initial VM Installation
Proxmox Virtual Environment V9.2, based on Debian Linux, is used as the hypervisor to manage all virtual machine instances.\
Three virtual machines are created with the following names and operating systems:

- LAB-LNX01: Ubuntu Server 26.04.1 LTS
- LAB-WIN01: Windows 11 Enterprise
- LAB-DC01: Windows Server 2K25

