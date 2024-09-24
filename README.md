# Hagital-Project-01--Group-A
Group A Project 01
Project Title: *Secure Remote Access Setup and Configuration for Virtual Machines
Duration: 3 weeks
*Objective:*
The objective of this project is to enable you to understand, configure, and secure remote access to virtual machines (VMs) running Linux operating systems. This group will be responsible for setting up a VM, ensuring it is securely accessible from a physical computer, and documenting the process and security measures.
*Project Tasks:*

*Group A: Linux VM Configuration and Access*
1. *Virtual Machine Setup:*
   - Create a Linux-based virtual machine using your Azure portal 
   - Configure the network settings of the VM to ensure it is accessible from the network.

2. *User Account Management:*
   - Create user accounts on the Linux VM for each group member.
   - Assign appropriate permissions and configure sudo privileges as necessary.

3. *Enable Secure Shell (SSH):*
   - Ensure SSH is installed and running on the Linux VM.
   - Configure the firewall to allow SSH connections (default port TCP/22).
4. *Generate and Deploy SSH Keys:*
   - Generate SSH key pairs for each group member.
   - Deploy the public keys to the ~/.ssh/authorized_keys file on the Linux VM.

5. *Secure the Connection:*
   - Set up a Virtual Private Network (VPN) or Network Security Group (NSG) to restrict access to the VM to specific IP addresses.
   - Implement SSH key-based authentication and disable password-based logins for SSH.
   - Document the steps taken to secure the VM and the SSH connection.

6. *Test Remote Access:*
   - Each group member should test remote access to the Linux VM using SSH.
   - Troubleshoot and resolve any connection issues.

7. *Monitoring and Logging:*
   - Enable and configure logging on the Linux VM to track remote access attempts (syslog or other logging service).
   - Monitor the logs for any unauthorized access attempts and document the findings.

8. *Documentation:*
   - Prepare a comprehensive report detailing the setup, security measures, and testing process.
   - Include screenshots and command outputs where applicable.
*Deliverables:*
1. *Group Report:*
   - Each person in this group should submit a detailed report of their work, including the following:
     - VM setup process.
     - User account creation and management.
     - Security measures implemented.
     - Remote access testing procedures and results.
     - Monitoring and logging configuration.
     - Any issues encountered and how they were resolved.

2. *Presentation:*
   - This group should prepare a presentation summarizing their findings and demonstrating how they configured and secured the VM.
   - The presentation should include a live demo or video showing the remote access process.

3. *Peer Review:*
   - You are to peer-review each other's work, providing feedback on the setup, security measures, and documentation.
