---
title: "Operating Systems"
teaching: 30
exercises: 
questions:
- "What are the functions of an operating system?"
- "What are the most popular operating systems?"
- "What are the main differences between operating systems?"
objectives:
- "Learn what is an operating system"
- "Learn about main differences between operting systems?"
keypoints:
- "Windows, MacOS, and Linux are three of the most popular operating systems."
- "For desktop and laptop computers, Windows is the most used OS."
- "For HPC computers and servers the most used OS in Linux."
---

## Choosing an Operating System 
We have learned what computers are made of, so let's move on to how to use a real one. In this section I will give you a quick overview of the operating systems and compare the three major operating systems that are currently available to help you decide which one is best for you.

In order to interact with your computer, you'll use software called an "operating system". Essentially, an OS is a program that stands between your computer and anything else you run on it. Among its essential functions are file management, memory management, process management, input-output management, and peripheral device control. Nowadays, a program can only concern itself with executing its core functions and let the operating system handle all basic system functionality.

Windows, MacOS, and Linux are three of the most popular operating systems used on desktops and laptops today.

### The usage share of operating systems 
For desktop and laptop computers, Windows is the most used at 76%, followed by Apple's macOS at 16%, and Linux-based operating systems at 5%.

Linux has completely dominated the supercomputer field since 2017, with all of the top 500 most powerful supercomputers in the world running a Linux distribution. Linux is also most used for (web) servers. Today, there are over 600 active Linux distros. The most widely used linux distributions are Ubuntu, Debian and CentOS

Having used all three OSs, I don't think the differences between them are THAT great.

Let's briefly review each of them individually and then look at some differences between these operating systems in terms of their design, features, and user interfaces.

### The three most widely used operating systems.
#### Windows
Windows is just the default OS for most people. It's the first one they get to know and it allows the user to easily run daily tasks such as internet browsing, gaming, office work. Windows is a private piece of software, meaning its source code isn't publicly available. Only Microsoft has access to it. At first, users had to pay if they wanted to buy a copy of Windows OS or upgrade their Windows version.  But with their latest releases users can access most of the software functionalities for free and only need to pay to access some particular features. Another thing to keep in mind is that Windows shows advertisements within the operating system. So it can be thought as an advertising platform as well.

#### MAC OS.
MacOS is built on top of a UNIX-like OS, which is why it shares many common characteristics with Linux. Unlike Microsoft, whose idea is to make the product as widely available and easy to get to as possible, Apple aims to make their products top quality but pricey and incompatible with other hardware. You can't run any software you want in their hardware, and you can't install their software anywhere else than a Mac machine.

#### Linux
Linux is the base of many open-source OSs. Unlike Windows and MAC OS, Linux isn't a full operating system, but a collection of programs, utilities and a kernel that many open-source OSs share.

The kernel is the heart of any OS. It's the piece of software that interacts the closest with the hardware and the rest of the OS sits on top of it. The Kernel is responsible for low-level tasks such as disk management, memory management, task management, and so on.

Making Linux free was was also an excellent choice from the software quality point of view. This is because it makes easy for thousands of developers and companies around the world to collaborate in order to improve the system.

Some of the Linux distributions are known to be the most secure and stable OSs out there. They're used in key spheres such as banking, finance, government, and military.

As I mentioned above, Linux runs on most servers. It's used on most supercomputers and also on most cellphones (as mentioned above, Android uses the Linux kernel).

On the desktop/laptop side of things, Linux usage isn't nearly as widespread. Back in the day, the learning curve necessary to use Linux was considerably higher than for the other two OS options. This situation has been changing lately. Linux distributions put more focus on user-friendliness and it becomes easier to get computers with Linux installed by default.

### Comparison of operating systems
#### File Systems.
Unlike MacOS and Linux, Windows organizes files differently. Windows uses "drives".

![](../fig/windows_fs.png)

Linux and Mac share a similar file system derived from UNIX. In these operating systems, there are no drives - everything is a file, and all files are arranged in directories that descend from a root directory. An organized directory structure is essentially a tree with a unique root.

![](../fig/linux-filesystem.png)

While it doesn't make much of a difference to the end user, it's something to keep in mind if you're used to navigating one type of file system.

#### Command-Line Shells.
Linux and macOS fall into the family of Unix-like systems that are designed as multitasking, multi-user operating systems. Furthermore, these systems are POSIX-compliant. The POSIX standard establishes compatibility between operating systems. As a result, all these systems offer standard UNIX facilities, and you can interact with them using the same commands.

Both Linux and Mac have bash or zsh as their default shells, while Windows has its own shell that uses a different syntax (Command Prompt and Powershell). Learning Bash is probably the best option, since this knowledge can be applied to most operating systems. Especially taking into account that Linux runs on most HPC clusters and you'd need to use the terminal to interact with these powerful computers. 

#### Package managers

Linux comes with a package manager installed by default. A package manager is a piece of software that allows you to install, update, and uninstall programs from the terminal, just by entering a few commands. They're super helpful, especially when you're installing and uninstalling things constantly, as it's much more efficient to install programs through package managers than manually. Linux comes in many flavors

depending on your needs, there are many different flavors of Linux you can use.
Ubuntu uses dpkg and apt

Two package formats: RPM and DEB. RPM is the installation package format for Red Hat Enterprise Linux (RHEL), SUSE Linux Enterprise Server (SLES) distributions. DEB is the package format for the Ubuntu distribution.

### Red Hat Enterprise Linux (RHEL)
#### RHEL 
-  A distribution developed for the commercial market. The source code is open, but binary distribution is commercial. Focused on efficiency, security, and stability. 

#### Fedora 
- More user focused than Red Hat. Focused on innovation, integrating new technologies early. It is considered to be on the leading edge of open-source technologies. Short life cycle. It servers as a testing environment for RHEL.

#### CentOS Stream 
- positioned as a midstream between Fedora Linux and RHEL. 

#### Rocky Linux and AlmaLinux
- A complete binary-compatible distros using the RHEL operating system source code. Since both operating systems are built from RHEL source code, there aren't many differences in compatibility, supported architecture, or purpose. The main differences lie in the project funding, which is based on different sponsors, and security.

Package manager dnf (a fork of yum) 

#### Debian
Ubuntu
Mint

Package manager apt

#### OpenSUSE

Package manager zypper, rpm-based


Mac's package manager is called homebrew. On GNU/Linux, the default package manager depends on the distro. For example, Ubuntu comes with APT, Arch comes with Pacman, and so on.

All package managers function in a similar way, but there are some differences in the syntax used for each. It's also important to mention that you can install and run a different package manager than the default.

Windows doesn't come with a default package manager. If you want one, you need to install it first. One of the package managers available for Windows is Chocolatey.

HomeBrew, MacPorts

Chocolatey


#### Software compatibility
Windows is the most widely used OS, and thanks to that most software is adapted to it. Even though less popular, MacOS is similar to Windows in this regard.

Back in the day, Linux wasn't compatible with many programs out there, but this has started to change recently, especially with the most popular distros like Ubuntu.

#### Security and stability
Some GNU/Linux distros are considered the most secure and stable ones nowadays. The fact that the code is available to everyone isn't a security threat as you may think at first – but rather it's an advantage. Bugs can be identified and worked on quicker, and when a security breach is identified lots of people can work on it and propose fixes.

Windows, on the other hand, is considered the least secure and stable of the three. Given that it's the most popular OS, most malware is developed to attack Windows OS too.

#### Windows Registry
A feature that sets Windows apart from other operating systems is its registry. The Windows registry is a database that contains all application settings. This is often referred to as a 'single point of failure' - a part of a system that, if it fails, will stop the entire system from working. Registry is susceptible to corruption from viruses, faulty hard drives, or even improper application uninstallation. Because it is a single global database, it affects the entire operating system. As you install applications, the registry grows and registry searches take longer, slowing down your computer as a result. As you remove applications, pointers to deleted files often remain in the registry, slowing down your computer.

#### Which OS is the "best"?
Like I said before, the operating system doesn't matter much for most people these days. There is no such thing as the "best" OS, so you're better off using the one you're most comfortable with. Even so, each OS is still unique. There are some scientific applications that aren't available on all platforms, and some that don't work well on all operating systems. You may be in a situation where it's a good idea to use several OSes at the same time. For example, you may use Linux working on HPC clusters coding and Windows for Office applications.

#### Exploring OS in a virtual machine 
Using a virtual machine may be a good option if you are undecided between different operating systems or want to try another OS. VirtualBox lets you run multiple operating systems simultaneously on the same machine. It is important to note, however, that the virtualized OS is significantly slower than the native.

### WSL - get the best of two systems 
Windows Subsystem for Linux lets you run Linux directly on Windows, without the overhead of traditional virtual machines. With the latest release of WSL2, even Linux GUI applications can now be run on Windows in a fully integrated desktop environment. 

The bottom line is that whatever operating system you choose is fine as long as it allows you to do what you want.

### Useful Links.
#### [VirtualBox](https://www.virtualbox.org) 
VirtualBox is a powerful virtualization solution. VirtualBox runs on Windows, Linux, macOS, and Solaris hosts and supports a large number of guest operating systems

