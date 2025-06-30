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

Our trainer began by explaining the basic structure of a computer system, including the Central Processing Unit (CPU), Memory Units (RAM/ROM), Storage Devices, Input/Output Devices, Motherboard, and Power Supply Unit (PSU).

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
The Day 4 session significantly improved our understanding of the physical components of a computer system. This knowledge will serve as a solid foundation for more advanced topics in the coming days.

