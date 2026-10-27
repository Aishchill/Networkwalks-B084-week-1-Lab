# Networkwalks-B084-week-1-Lab

# Kali Linux Lab Setup Using Oracle VirtualBox

##  Overview

This project documents the setup of a Kali Linux virtual machine using Oracle VirtualBox. It covers the initial virtual machine configuration, network adapter settings, and internet connectivity verification.

A short video demonstration is included in the GitHub repository to show Kali Linux running with a working internet connection.

##  Objectives

- Install and run Kali Linux in Oracle VirtualBox.
- Configure virtual machine hardware and network settings.
- Verify network connectivity from the Kali Linux terminal.
- Test internet access using a web browser.
- Document the setup process for future cybersecurity lab activities.

## Tools and Technologies

- **Virtualization:** Oracle VirtualBox
- **Operating System:** Kali Linux
- **Networking:** NAT (Network Address Translation), if configured
- **Terminal Tools:** `ip`, `ping`, `ip route`
- **Version Control:** Git and GitHub

## Lab Configuration

The virtual machine was configured with appropriate system resources and an enabled virtual network adapter.

| Component | Configuration |
|---|---|
| Host OS | Windows |
| Virtualization Platform | Oracle VirtualBox |
| Guest OS | Kali Linux |
| Network Adapter | VirtualBox virtual network adapter |
| Network Mode | NAT, if used |
| Connectivity | Internet access tested |

*Note: Update the network mode and other settings if your actual configuration differs.*

## Setup Procedure

### 1. Create the Virtual Machine

- Open Oracle VirtualBox.
- Create a new virtual machine or import a Kali Linux virtual machine image.
- Allocate suitable RAM, CPU cores, and virtual disk space.
- Attach the Kali Linux ISO if performing a fresh installation.

### 2. Install Kali Linux

- Start the virtual machine.
- Follow the Kali Linux installation instructions.
- Complete the initial operating system and user configuration.
- Restart the virtual machine and log in.

### 3. Configure Network Settings

- Open the virtual machine's **Settings → Network**.
- Enable the network adapter.
- Select NAT if internet access through the host connection is required.
- Save the settings and start Kali Linux.

### 4. Verify Network Connectivity

Open the Kali Linux terminal and execute the following commands.

**Test website access**

Open the browser in Kali Linux and visit a website to confirm that internet access is working.

**Test in Terminal**
ping google.com

## Results

The lab setup and connectivity verification were demonstrated in a short video uploaded to this repository.

The verification process covers:

- Successful Kali Linux startup.
- Network interface inspection.
- IP connectivity testing.
- DNS resolution testing.
- Browser-based internet access.

## Video Demonstration

Watch the video demonstrating Kali Linux internet connectivity:

**[View the Lab Demonstration](https://drive.google.com/file/d/1Nk6LfYHzhsu5iUtoTLelP3GyrG4OEN1a/view?usp=drive_link)**

Replace the placeholder with your GitHub video path or the link to your hosted video.

## Skills Practiced

- Linux fundamentals
- Virtual machine configuration
- Basic networking
- IP addressing and routing
- DNS troubleshooting
- Internet connectivity testing
- Technical documentation using GitHub

## Future Improvements

- Configure an isolated cybersecurity lab.
- Explore NAT, bridged, and host-only networking.
- Practice packet analysis using Wireshark.
- Perform authorized network scanning using Nmap.
- Document additional troubleshooting scenarios.

## References

- [Kali Linux Documentation](https://www.kali.org/docs/)
- [Kali Linux VirtualBox Installation Guide](https://www.kali.org/docs/virtualization/install-virtualbox-guest-vm/)
- [Oracle VirtualBox Documentation](https://www.virtualbox.org/manual/)

## Author

**Aishwarya**

---

*This project is part of my cybersecurity learning journey, focusing on Linux administration, virtualization, and networking fundamentals.*
