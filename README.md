# Borntoberoot
oral-defence

* what is a virtual machine?
  
Speak in briefly, it is just making another computer inside of your original computer by sharing its hardware resources. 

A virtual machine (VM) is a software emulation of a physical computer. It allows multiple operating systems to run on a single physical machine, by creating a virtual environment that simulates the hardware of a physical computer.


So what is computer, there is a hardware resources including : 
-CPU, 
-Ram, 
-storage, 
-GPU(Graphics processing unit : a specialized processor originally designed to accelerate graphics rendering. GPUs can process many pieces of data simultaneously, making them useful for machine learning, video editing, and gaming applications.), 
-NIC (Network Interface Controller : which support computer to connect and communicate to network.)
********************
To use that resourses; like we use computer normally, we need a software in which is operating systems. For examples, the most used Windows, Mac, Linux etc. Normally for the computer device we use can only store one O.S. 

To use other O.S, then you need a new hardware resources, another computer. Whereas using "Hypervisor" can allow you to create how many of small computers inside of your device you want, unless it is at its capacity. Hypervisor is an application you installs on your operating system, such as Google Chrome, call of duty(Gaming APP), or this Virtual box.

Virtual box is an application that can help you to make a fake(virtual) computer sharing your original computer's hardware resources. But they are independent of physical hardware.
***************
There is two types of Hypervisor;

-Type 2 is something that like Vitual machine(Guest O.S)in which can be built on top of your own O.S (Host O.S). 
-Type 1 is like "vmware or exsi" which can be installed staight on top of hardware. so, you should erase your previous O.S to install this. Normally and typically type 1 is used for enterprises or companies and installed in big servers such as dell servers, hp servers. 
***************
Purpose of using the VM.......are;

Firstly, if you want to learn Hacking, to perform your hacking duties safe and most secure way, this is recommended by infamous platfrom 'hack me' 'hack the box'... 

Secondly, when you want to learn different O.S, this will be very helpful to use to wide up your skills. From companies perspectives, this is cutting the cost less and for those who starts their business will no more to strain of the cost burden as there is no many servers needed. 

Thirdly, you can break staff. For examples, you can try many things without worring and concerns of breakdown of hardwares as you built your new(fake=virtual) independent computer on host O.S. It doesn't effect your Host O.S at all. Whenever it broke,, then you can just delete it and rebuilt again. So the VM is the greatest environment to practice and experience.
*********
Debian is a Linux-based operating system. 

*********
Protocols :
It is a set of rules that need to be followed by the communicating parties in order to have successful and reliable data communication, regarless of any differences in their internal processes, structures or design = how data is transmitted between different devices in the same network. There is three main types of network; network management protocols, network communication protocols and network security protocol. For examples, there is HTTP and TCP/ip.

*what is API?
API stands for "Application Programming Interface." It is a set of rules and protocols that allows different software applications to communicate with each other.

APIs allow developers to access the functionality of another application or service in a controlled and predictable way. For example, an API can allow a developer to retrieve data from a database, or send a command to a device to perform a specific action.

APIs are commonly used to connect different components of a system, or to expose the functionality of one system to other systems. This allows for greater flexibility and integration of different software systems, and allows developers to build new applications and services by leveraging existing functionality.

APIs can be used to access a wide range of services and data, such as social media platforms, weather information, financial data, and more. This allows developers to easily access and use this data in their own applications, without having to build the functionality from scratch.

In summary, An API (Application Programming Interface) is a set of rules and protocols that allows different software applications to communicate with each other, it allows developers to access the functionality of another application or service in a controlled and predictable way, it is commonly used to connect different components of a system, or to expose the functionality of one system to other systems and it can be used to access a wide range of services and data, such as social media platforms, weather information, financial data, and more.

***********
What is IP?

An IP address (Internet Protocol address) is a numerical label assigned to each device connected to a computer network that uses the Internet Protocol for communication. It serves two main functions: identifying the host or network interface, and providing the location of the host in the network.

************
what is apt and aptitude in Debian.

apt and aptitude are both package management tools for Debian-based Linux distributions, but they have some differences in how they function and how they are used.

apt (Advanced Package Tool) is a command-line tool that is used to manage the installation and removal of software packages on a Debian-based system. It is the default package manager for Debian and Ubuntu, and it is widely used and well-documented. apt has a simple and straightforward command syntax, and it is easy to use for basic package management tasks. It also supports many advanced features like package versioning, automatic dependency resolution, and multi-architecture support.

aptitude, on the other hand, is a more advanced package management tool that is built on top of the apt system. It is also a command-line tool, but it has a more powerful and sophisticated user interface than apt. aptitude allows users to perform more complex and advanced package management tasks, such as resolving package dependencies, managing package states, and searching for packages based on various criteria. It also has a built-in ncurses interface which is more user friendly and allow to navigate, select and perform actions on packages and groups of packages in a more efficient way.

In summary, apt and aptitude are both package management tools for Debian-based Linux distributions, but apt is the default package manager for Debian and Ubuntu, it's simple and easy to use while aptitude is more advanced and provide more complex and advanced package management tasks and a more sophisticated user interface.

****************************
What is SSH?

SSH stands for Secure Shell, it is a protocol used to securely log into a remote machine, it allows users to remotely access and control a computer over a network using a secure and encrypted connection. SSH encrypts all data exchanged between the remote machine and the client, including login information and the entire session, protecting it from eavesdropping and tampering.

With SSH, users can access the command line of a remote machine, transfer files, and tunnel network connections. It is commonly used to log into a remote machine and execute commands, but it also supports tunneling, forwarding TCP ports and X11 connections.

SSH is typically used to log into a Unix-based server, but it can also be used to log into other types of systems such as Windows and macOS systems.

SSH uses a set of keys to encrypt the communication between the client and the server, the keys are a pair of public and private keys, the public key is sent to the server and the private key is kept by the client, when the client connects to the server, the server sends a challenge message that is encrypted with the public key, the client then uses the private key to decrypt the challenge message and sends back the decrypted message to the server, if the message is correct the server grants the access.

In summary, SSH (Secure Shell) is a protocol used to securely log into a remote machine, it allows users to remotely access and control a computer over a network using a secure and encrypted connection, it encrypts all data exchanged between the remote machine and the client, including login information and the entire session, protecting it from eavesdropping and tampering, it is commonly used to log into a remote machine and execute commands, but it also supports tunneling, forwarding TCP ports and X11 connections, and it uses a set of keys to encrypt the communication between the client and the server.

********************

what is APPArmor
AppArmor (Application Armor) is a Linux security module that allows administrators to restrict the capabilities of individual programs and applications. It is a mandatory access control system, which means that it enforces a set of predefined rules that dictate what a program is allowed to do. This is in contrast to discretionary access control systems, which allow users to set their own permissions for programs and files.

AppArmor provides a way to confine programs to a limited set of resources, reducing the attack surface of the system and limiting the potential damage that can be caused by a compromised program. This can be useful for preventing malicious or buggy software from causing harm to the system or other programs.

AppArmor is built into the Linux kernel and uses a simple text-based policy language to define the rules that a program is allowed to follow. The rules are defined in the form of profiles, which can be applied to specific programs or groups of programs. Administrators can create custom profiles or use predefined profiles that come with the system.

AppArmor is not enabled by default on most Linux distributions, but it can be installed and configured on most systems. It can be used in conjunction with other security measures, such as firewalls and intrusion detection systems, to provide a more comprehensive security solution.

In summary, AppArmor (Application Armor) is a Linux security module that allows administrators to restrict the capabilities of individual programs and applications, it is a mandatory access control system that enforces a set of predefined rules that dictate what a program is allowed to do, this can be useful for preventing malicious or buggy software from causing harm to the system or other programs. It is built into the Linux kernel and uses a simple text-based policy language to define the rules that a program is allowed to follow. AppArmor is not enabled by default on most Linux distributions, but it can be installed and configured on most systems and can be used in conjunction with other security measures, such as firewalls and intrusion detection systems, to provide a more comprehensive security solution.

*******************

what is sudo?

sudo is a command in Linux and other Unix-like operating systems that allows users to run commands with the privileges of another user, typically the superuser or root. The superuser, also known as the root user, has the highest level of access and permissions on a Linux system, and is able to perform any action, including modifying system files and installing software.

The sudo command is used to execute a single command with superuser privileges. It prompts the user for their own password, rather than the password of the superuser, before running the command. This allows regular users to perform tasks that require superuser permissions, without giving them access to the superuser's password.

sudo can also be configured to allow certain users or groups to execute specific commands without entering a password, or to run commands as a specific user other than the superuser. This is useful for delegating administrative tasks to specific users, or for automating tasks that require superuser permissions.

It is considered as best practice to use sudo when performing tasks that require superuser permissions, rather than logging in as the superuser directly. This allows for better accountability and security, as it is easier to track which user performed a specific action and to limit the potential damage that can be caused by a compromised account.

In summary, sudo is a command in Linux and other Unix-like operating systems that allows users to run commands with the privileges of another user, typically the superuser or root. It is used to execute a single command with superuser privileges and prompts the user for their own password before running the command. sudo can also be configured to allow certain users or groups to execute specific commands without entering a password, or to run commands as a specific user other than the superuser. It is considered as best practice to use sudo when performing tasks that require superuser permissions, rather than logging in as the superuser directly for better accountability and security.

******************
what is partition in virtual machine system?

In a virtual machine (VM) system, a partition refers to a section of the virtual machine's virtual storage space that is dedicated to a specific purpose or use.

In a virtual machine, the virtual storage space is typically represented by a virtual hard disk file, also known as a virtual disk or vdisk. The virtual hard disk file is a file that resides on the host machine's physical storage, and it emulates a physical hard disk that the virtual machine can use as its own storage.

A partition on a virtual machine can be used to separate the virtual machine's operating system, applications, and data from one another, similar to how partitions are used on a physical machine. For example, one partition can be used to install the operating system, another partition can be used for user data and another partition can be used for backups.

Partitions can also be used to create multiple virtual hard disks for a virtual machine, each with its own file system and mount point. This allows for better organization and management of the virtual machine's storage, as well as the ability to use different file systems for different purposes.

Partitioning can also be used to increase the security of the virtual machine by isolating the system files and user data and also to improve performance by separating the frequently accessed files from less frequently accessed files.

In summary, In a virtual machine (VM) system, a partition refers to a section of the virtual machine's virtual storage space that is dedicated to a specific purpose or use. It can be used to separate the virtual machine's operating system, applications, and data from one another, similar to how partitions are used on a physical machine. It can also be used to create multiple virtual hard disks for a virtual machine, each with its own file system and mount point, this allows for better organization and management of the virtual machine's storage, as well as the ability to use different file systems for different purposes. Partitioning can also be used to increase the security of the virtual machine and to improve performance.

***************
what is UFW?

UFW stands for Uncomplicated Firewall. It is a command-line tool for managing a Linux firewall, it is an easy-to-use front-end for the iptables firewall that is included with most Linux distributions.

UFW is designed to be simple and user-friendly, it enables the user to quickly and easily configure the firewall using a set of predefined rules, without needing to know the details of the underlying iptables system.

UFW provides a set of commands that allow the user to enable or disable the firewall, add or remove firewall rules, and check the current firewall status. The rules can be defined to allow or deny specific types of network traffic, based on factors such as the source and destination IP address, port number, and protocol.

By default, UFW is set to deny all incoming traffic and allow all outgoing traffic, this is considered as a secure setup, but it can be customized to allow certain traffic through the firewall. For example, it can be configured to allow incoming traffic on port 22 for SSH, port 80 for HTTP and port 443 for HTTPS.

UFW is not enabled by default on most Linux distributions, but it can be installed and configured on most systems. It can be used in conjunction with other security measures, such as AppArmor, to provide a more comprehensive security solution.




