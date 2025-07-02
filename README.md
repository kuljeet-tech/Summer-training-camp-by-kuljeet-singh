# Summer-training-camp-by-kuljeet-singh
In this repository i will share my experience of summer training camp at gndec,ludhiana
# Day 1
On the first day of our summer training there was an orientation program where we were introduced to our core department (CSE) and we were told about our syllabus.
After the orientation program we proceed to our respective labs according to our group.In the lab, we were introduced to the Linux operating system by our lab professor (ma'am). She explained the basics of Linux, its history, and why it is widely used in the fields of programming, networking, and system administration.

We learned that Linux is a free, open-source operating system known for its security, stability, and performance. The professor discussed the advantages of Linux over other operating systems and its importance in real-world applications like servers, cloud computing, and software development.

As part of our practical learning, the professor instructed us to install a Linux ( Ubuntu ) on our laptops or lab computers. She guided us through the basic steps to install the Linux using virtual machine.
# Day 2
On the second day of our summer training, our lab professor introduced us to fundamental concepts of Linux including the booting process,kernel and the shell. The session was highly informative and was conducted using a visual presentation, which greatly enhanced our understanding of the topics.
#The session began with an explanation of the booting process, which is the sequence of events that occurs from powering on the computer to getting the operating system ready for use.Booting is of two types 
Cold booting- it refers to the process of starting the computer from completely powered-off state.
Warm booting- it refers to the restarting of computer while its already powered on ,without cutting off the power supply.  
#The kernel was described as the core component of the operating system that manages hardware resources and allows communication between hardware and software.
    Our professor explained how the kernel loads into memory during boot and starts necessary system processes.
#The shell was introduced as a command-line interface that allows users to interact with the operating system.
    We discussed different types of shells, with a focus on the **Bash shell**, which is most commonly used in Linux.
    ![IMG_20250628_175921](https://github.com/user-attachments/assets/7119bdc7-4ee3-4e07-9d00-9d2399aece5f)
  All these things were explained with the help of suitable examples so that they were easy to understand for us. 
#Our professor demonstrated the use of several basic Linux commands. These included:

     1.`ls` – to list directory contents
     2.`pwd` – to display the current working directory
     3.`date` – to show the current system date and time
     4.`mkdir` – to create new directories
     5.`cat` – to display the contents of files
     6.`touch` – to create new empty files
     7.`cp` – to copy files and directories
     8.`cd` – to change the current directory
   * Each command was explained clearly with practical examples shown in the presentation to ensure everyone could follow along visually and conceptually.
     I practiced the commands in linux terminal for better understanding
     ![IMG_20250628_121657](https://github.com/user-attachments/assets/a21ce1cf-80a6-461f-83d8-f37d183d5486)
# Day 3
On the third day of our summer training program, we delved deeper into the foundational aspects of Linux systems. The session was conducted by our lab professor, who guided us through several important topics crucial for understanding system-level operations.

The day began with an insightful introduction to bare metal installation. We learned how to install an operating system directly onto the hardware without any pre-installed OS or virtualization layer. Our instructor explained the process step-by-step, including how to prepare bootable media and configure BIOS settings for installation.

Following this, we explored MBR (Master Boot Record) and GPT (GUID Partition Table) — two methods used for disk partitioning. The differences between the two were clearly outlined, especially in terms of compatibility, partition limits, and structure. We learned that while MBR supports up to four primary partitions and is compatible with older systems, GPT is more modern, supports larger disks, and allows for unlimited partitions (with practical limits based on OS).

Next, we were introduced to the concept of dual booting. Our lab professor demonstrated how two operating systems can be installed on the same machine and booted independently using a boot loader like GRUB. This session was particularly engaging, as we discussed the advantages and risks of dual boot configurations.

In the second half of the session, we covered file and directory permissions in Linux. We learned about user roles (owner, group, others) and permission types (read, write, execute). Using commands like chmod, chown, and ls -l, we practiced modifying and checking file permissions to enhance security and access control.!![IMG_20250630_171329](https://github.com/user-attachments/assets/963dd723-67ba-4ee4-ab4d-5ccf32a0ee3a)
![IMG_20250630_171249](https://github.com/user-attachments/assets/2cc39c01-403b-45cb-ac03-bcaa2d40921d)


Lastly, we were introduced to pipes (|) — a powerful feature in the Linux shell that allows the output of one command to be used as the input of another. Through hands-on examples, we understood how pipes help in chaining commands efficiently to perform complex tasks with simple syntax.

Overall, Day 3 was packed with essential concepts and practical knowledge, significantly improving our understanding of Linux system operations. The hands-on approach and real-time demonstrations helped solidify these concepts and sparked a greater interest in exploring Linux further.

# Day 4
On the fourth day of our summer training, we delved into the hardware aspect of computers. The session was both theoretical and practical, giving us hands-on exposure to physical components and their configurations.

Our lab proffesor began by explaining the basic structure of a computer system, including the Central Processing Unit (CPU), Memory Units (RAM/ROM), Storage Devices, Input/Output Devices, Motherboard, and Power Supply Unit (PSU).

Key topics discussed included:

Motherboard: The main circuit board that connects all components together. The motherboard have its various parts-
1. CPU Socket: This is where the central processing unit (CPU) is installed. It's a critical component as the CPU is the "brain" of the computer. 
2. RAM Slots: These slots are where Random Access Memory (RAM) modules are inserted. RAM is used for temporary data storage and is essential for smooth multitasking. 
3. Expansion Slots: These slots (like PCI, PCIe, and AGP) allow users to add expansion cards for various functionalities like graphics cards, sound cards, or network cards. 
4. Chipset: The chipset is a set of chips that manage communication between the CPU, memory, and other components. It often includes the Northbridge and Southbridge. 
5. BIOS Chip: The Basic Input/Output System (BIOS) is a chip that contains firmware instructions for starting up the computer and managing basic hardware operations. 
6. CMOS Battery: This small battery powers the CMOS chip, which stores the BIOS settings and system configuration even when the computer is off. 
7. Connectors: These include SATA connectors for storage devices (SSDs and hard drives), USB ports, and power connectors for supplying power to the motherboard and its components. 
8. Northbridge and Southbridge: The northbridge and southbridge handles the communication between cpu,ram and graphic card.  
![640px-Computer-motherboard](https://github.com/user-attachments/assets/b8cddd19-6b19-444a-bc21-ce0a642de076)

CPU (Processor): Its role as the brain of the computer, how it processes instructions, and differences in cores and threads.

RAM (Random Access Memory): Temporary memory used for quick data access. We were explained its importance in multitasking.

Storage Devices: Comparison between HDDs, SSDs, and newer NVMe drives.

Power Supply Unit (PSU): How it distributes power to all parts of the computer.

Peripheral Devices: Understanding how input (keyboard, mouse) and output devices (monitor, printer) interface with the system.

We also learned how to assemble and disassemble a PC, identify different ports and connectors (USB, HDMI, SATA), and handle components safely to prevent static damage.

Hands-On Activities:
Identifying different hardware parts from a dismantled CPU.

Observing the installation of RAM and CPU on the motherboard.

Viewing internal connections and power distribution.

Learning Outcomes:
Gained practical knowledge of major computer hardware components.

Understood the interconnection between different parts.

Learned the basics of PC assembly and troubleshooting.

Conclusion:
The Day 4 session significantly improved our understanding of the physical components of a computer system. This knowledge will serve as a solid foundation for more advanced topics in the comm
# Day5
The fifth day of my summer training was mainly based on the troubleshooting.
# 🔧 1. PC Troubleshooting (Hardware)
This type of troubleshooting means that to deal with the problems in hardware of the system.
-Symptoms of hardware issues: such as a system not starting, no display, beeping sounds, overheating, or slow performance.
-Basic diagnostic steps: including checking power connections, RAM seating, cleaning dust from fans, and verifying the hard drive.
-BIOS usage: Understanding how to access and use BIOS to check whether the system is detecting the hardware properly.


# 2. Network Troubleshooting
The next segment focused on resolving network-related issues. We learned how a proper network setup works and how to handle problems when:
-There’s no internet access
-A device is connected but can’t browse
-IP conflicts occur
-DNS or gateway issues arise

Key tools and commands introduced:
-ipconfig – to view IP settings
-ping – to test connectivity
-tracert – to check route to a server
-etstat – to view active connections

# 3. Software Troubleshooting
In the final part of the day, we focused on software issues, which are the most frequent problems faced by users. These include:
-Application crashes
-System freezes
-Slow boot-up
-Unresponsive programs
-Virus/malware issues

Troubleshooting techniques covered:
-Using Task Manager to monitor performance and kill unresponsive applications
-Managing startup programs to reduce boot time
-Performing System Restore to roll back changes
-Reinstalling and updating faulty applications
-Running antivirus scans and using Windows Security tools

# Conclusion:
Day 5 of the summer training was highly practical, informative, and skill-oriented. The balance between theory and real-world application made the learning process engaging and effective. I now feel more confident in handling basic troubleshooting tasks for PCs, networks, and software — essential skills for anyone in the IT field

# Day 6
On the sixth day of our training we were taught about the following things:  
# 1. BSOD (Blue Screen of Death):
We began by discussing BSOD, one of the most serious errors encountered in Windows systems. It usually indicates a critical system failure, often related to hardware, drivers, or kernel errors.
Key learnings:
-Common causes: Faulty RAM, corrupted drivers, overheating, disk errors, or malware.
-Reading error codes and stop messages.
-using the tool “WhoCrashed” or Windows Event Viewer to analyze crash reports.
-Steps to prevent BSOD: Updating drivers, checking hardware, and scanning for malware.
![BSOD](https://github.com/user-attachments/assets/038cc9d2-ed78-4d57-ae5b-fc57ddfc33ec)


# 2. Safe Mode:
We learned about Safe Mode, a diagnostic boot mode in Windows that starts the system with minimal drivers and services.
Key uses:
-Uninstalling problematic software or drivers.
-Running antivirus scans without interference.
-Performing system restores or edits when normal boot fails.

# Types of safe mode
-Safe Mode
-Safe Mode with Networking
-Safe Mode with Command Prompt

# 3. Recovery Tools:
Windows provides several built-in recovery tools for restoring system stability. We explored:
-Startup Repair – fixes boot-related issues.
-System Restore – rolls back Windows to a previous working state.
-System Image Recovery – restores the PC from a backup image.
-Command Prompt – for advanced recovery commands.
-Reset This PC – to reset or refresh Windows while keeping or removing files.

# 4. OS Repair Techniques:
We discussed how to repair a corrupt operating system using:
-SFC (System File Checker) and DISM (Deployment Imaging Service and Management Tool) commands.
-Windows installation media for repairing or reinstalling the OS.
-Performing in-place upgrades to fix system files without losing data.
-We practiced running these commands and understanding when each is used.

# 5. Where and How to Store Windows Backups:
The instructor stressed the importance of backing up important data and system configurations.

# Backup types discussed:
-File History (for personal files)
-System Image Backups (for full system recovery)
-OneDrive or external drives for automatic backups

# Recommended locations:
-External hard drives or SSDs
-Network drives or cloud storage
-A separate disk partition (not the one where Windows is installed)

# 6. RJ-45 Connector:
We concluded with a hardware component – RJ-45, a standard connector used for Ethernet networking.

Key highlights:
Structure and pin configuration (8P8C format)
Types of Ethernet cables (Straight-through vs. Crossover)
Usage in LAN setup for routers, switches, and PCs
Crimping demo: how to attach RJ-45 to an Ethernet cable using a crimping tool
We also observed color-coding standards (T568A and T568B) and checked for proper signal transmission using a cable tester.

Conclusion:
Day 6 was one of the most technically insightful days of our training. We not only learned how to handle critical Windows errors but also explored how to prevent data loss and maintain system stability. The combination of system-level knowledge and networking basics made this session especially valuable for anyone pursuing IT or system administration.







