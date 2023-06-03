<h1>Kali Linux - Initial Setup & Troubleshooting Guide (Windows 10)</h1>

<h2>Description</h2>
The Cyber Security Project involves the initial setup and troubleshooting of a Kali Linux virtual machine (VM) using Oracle VM VirtualBox. Kali Linux is a popular Linux distribution widely used for penetration testing, ethical hacking, and security auditing.

The project aims to provide a secure and isolated environment for conducting various security-related activities, such as vulnerability scanning, network analysis, and penetration testing. By setting up a Kali Linux VM, participants can gain hands-on experience with tools and techniques commonly employed by cybersecurity professionals.

The project involves the following steps:

----------------------------------------------------------------------------------------------------------------------------------------------------------------------

Installation of Oracle VM VirtualBox: Participants install the Oracle VM VirtualBox software on their host machine, ensuring compatibility with their operating system. This step may require system configuration adjustments to enable virtualization.

Obtaining Kali Linux: Participants download the Kali Linux ISO image from the official website. The ISO file contains the complete operating system and tools necessary for conducting security assessments.

Creating a Kali Linux VM: Using Oracle VM VirtualBox, participants create a new virtual machine and configure its settings. This includes allocating system resources such as CPU, RAM, and storage for optimal performance.

Installing Kali Linux: Participants mount the Kali Linux ISO image in the virtual machine and proceed with the installation. They follow the installation wizard to set up the operating system, create user accounts, and configure network settings.

Post-installation setup: After installing Kali Linux, participants update the system packages and repositories to ensure they have the latest versions of security tools. They may also customize the VM settings, install additional packages, or configure network adapters based on their project requirements.

Troubleshooting and Issue Resolution: Participants troubleshoot common issues that may arise during the setup process. This includes addressing network connectivity problems, resolving hardware conflicts, or resolving compatibility issues between the host machine and the virtual environment.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------

Throughout the project, participants gain practical knowledge of virtualization technologies, operating system installation and configuration, and troubleshooting techniques. They also become familiar with the Kali Linux ecosystem and its wide range of cybersecurity tools.

By successfully setting up and troubleshooting the Kali Linux VM, participants lay the foundation for performing various cybersecurity tasks within a secure and controlled environment. This project serves as an essential step towards developing practical skills in the field of cyber security and ethical hacking.
<br />

<h2>Minimum Hardware Requirements</h2>

- <b>Processor: A dual-core processor or higher is recommended. However, a single-core processor can suffice for basic usage.</b> 
- <b>RAM: At least 2 GB of RAM is required for running Kali Linux smoothly. However, it is recommended to have 4 GB or more for better performance, especially when running resource-intensive security tools.</b>
- <b>Storage: A minimum of 20 GB of free disk space is required to install Kali Linux. However, it is advisable to allocate more space (at least 40 GB or higher) to accommodate additional software packages, tools, and data.</b>
- <b>Graphics: Any graphics card that supports the host operating system is sufficient for running Kali Linux in a virtual machine.</b>
- <b>Network: A network interface card (NIC) is required for network connectivity within the Kali Linux VM. Oracle VM VirtualBox allows you to configure network adapters, including NAT, Bridged, or Host-only networking, based on your requirements.</b>
- <b>Host Machine: The host machine should meet the minimum requirements for running Oracle VM VirtualBox itself. Refer to the VirtualBox documentation for specific details regarding the host machine's operating system, processor, RAM, and storage requirements.</b>

<i>It is important to note that the above specifications represent the minimum requirements, and for a better experience, it is recommended to have higher specifications, especially when working with resource-intensive tasks or running multiple virtual machines simultaneously. </i>

<h2>Languages and Utilities Used</h2>

- <b>VirtualBox 7.0.8 Platform Packages</b> (Windows hosts)
- <b>VirtualBox 7.0.8 Oracle VM VirtualBox Extension Pack</b> (All supported platforms)
- <b>Kali Linux - Installer Images</b> (64-bit Installer)
- <b>Bash</b>
- <b>BIOS</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (22H2 / OS Build 19045.2965)
- <b>Kali Linux</b> (2023.2)


<h2>Program walk-through:</h2>

<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
