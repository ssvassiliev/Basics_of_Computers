---
title: "Using a computer"
teaching: 30
exercises: 
questions:
- "How to choose a computer?"
- "How to maintain a computer?"
- "How to protect your computer?"
- "Is it better to repair or replace a computer?"
objectives:
- "Understand what are the most important factors to consider when buying a PC."
- "Learn how to keep your computer safe."
keypoints:
- "Use a different password for each account and beef up security using MFA if possible."
---

## 17. How to choose the right computer
Choosing a computer is always about making trade-off decisions. Unless money is absolutely no issue for you, you will have to make some trade-offs such as:

- Powerful desktop or portable laptop.
- Faster CPU or longer battery life
- Lighter weight or less expensive
- Bigger and better display or less cost

The trade-offs really depend on how you plan to use the system.  The point is, before you choose your platform, it's important for you to identify your needs.  It may be that you have a limited budget or that you have a specific pressing need. Unless your first priority is to get your job done as soon as possible, there is little need to spend a great deal of money.

In my opinion, there are quite a few differences in the criteria for selecting a desktop computer or laptop. My choice of a laptop computer will be dictated by my preferences. My laptop must be lightweight and small, but I also need a reasonable-sized keyboard and high-definition screen. The size, weight, and screen quality are more important to me than any other factor, including price.  Remember that identifying your needs is the first step in choosing the right platform. 

## 18. Tradeoffs in Buying a Computer
It is also important to balance price and performance. Don't be obsessed with getting the fastest available hardware components, it is not necessary. With components  that are not top-of-the-line, you can get excellent performance for less money. I will briefly point out a few other things to consider when purchasing a computer. 

- Desktops are powerful, upgradable, repairable, flexible price, but not portable. Full-sized parts make hardware reliable and replaceable. Desktops are way more flexible, and you can buy exactly what you need without having to buy unnecessary components. 

- Laptop even the most expensive will not be suitable for serious computations for extended periods of time. 

- As the system drive, use SSD, and as extra storage, HDD. Install all applications on SSDs and use HDDs for long-term storage or backups only. M2.NVMe SSDs are much faster than regular SSDs and provide the best performance. With NVMe SSD, applications will load much faster and the overall system will be more responsive. 

- Choose the right memory
 - Going from 3000MHz to 3600MHz RAM makes very little difference to real-life performance (less than 1% in most cases). 
 - Don???t pay for RAM speeds your system doesn???t support. 
 - Speed of RAM depends on two factors, not just the MHz clock speed. In order to determine how fast your RAM is, you must take into account both the CAS (Column Access Strobe) latency and clock speed.
 -If you are in a position where you are unsure to go for 8GB of faster RAM or 16GB, you should always opt for the 16GB especially if you are price-conscious. Sure, if you can afford it then grabbing a 16GB+ kit with fast speeds will have some benefits it is only really relevant when small performance gains are important for you.

- Laptops are less powerful than desktops but portable. They are expensive and tough to upgrade, maintain, or repair due to miniaturized parts. Only a limited set of features can be customized.

- Mobile are very portable, but limited in power and impossible to repair. Same issues as laptops, but less power and I/O options.

It is likely that at some point you will realize that one PC, even the fastest one, won't suffice to do the work you require. As an example, if the analysis of one sample takes a day and you have thousands of samples to analyze, it will take several years! Using HPC clusters provided by Digital Alliance of Canada might be an option in this case. It would take just a few days to complete all analyses with a thousand of CPUs. Such computational resources are available and free for academic researchers. I encourage you to attend our ACENET basics sessions next week where we will introduce these resources and explain how to use them.


## 19. Keeping your computer in good shape (Maintain your equipment)
In the past computers required to be regularly powered down or rebooted. New computers can go without power cycling for months. However, if computer becomes unusually sluggish, or some programs do not behave as they should even if they are restarted then rebooting your computer is the first thing you should do before trying to solve the problem..

- Cleanup storage. You can free up disk space on your hard drive by running a disk cleanup. This will clean out temporary files as well as delete big attachments and other types of files.

- Organize similar files into folders. Keeping multiple files on your desktop can slow down your machine. Instead, organize similar files into folders where you can easily find them. This will also help streamline the cleaning process when it comes time to delete unnecessary items.

- Delete unused programs. Delete unnecessary programs from your computer to free up storage space. 

- If you have mechanical HDD defragment it to restore performance when needed.

- An important factor in maintaining your computer is installing latest security updates to keep your operating system up-to-date with the latest patches.

- Keep your anti-virus software up-to-date and frequently scan your computer for viruses.

# Security
## 20. Security: Malware and Viruses 
Do you need an Antivirus? It depends on the operating system. Windows and macOS include protection against viruses, in one way or another.

Microsoft Defender Antivirus in addition to providing antivirus protection, also manages other security features such as Windows Firewall. However it was reported that is has some significant limitations and you can improve your protection by installing a third-party antivirus such as BitDefender, Avast, AVG.

MacOS Includes Security by Design. The operating system resides on a read-only drive partition, separate from all other programs. To infect another program, a virus needs to modify that program, and that???s not allowed in macOS. To steal private data, a banking Trojan must read memory belonging to your browser, which is likewise not allowed. In the macOS environment, apps are isolated, and limited to accessing their own resources. macOS includes a technology called Gatekeeper, that's designed to ensure that only trusted software runs on your Mac. While Macs aren???t as vulnerable as Windows boxes they still can get malware. 

## 21. Security: Passwords
Use a different password for each account, never use same password for several sites. When breaches expose credentials, all accounts that share a password are exposed. 

Of course it is impossible to remember all passwords, so get a password manager like DashLane, BitWarden or 1Password.  With a password manager, you don't have to remember strong, unique passwords for all your accounts. The password manager stores them for you and even helps you generate new, random ones. A password manager is like a digital keyring, it keeps everything in one secure place for easier access.

Generate a strong master password at least 8 chars lond with 3 types of characters. Never use a dictionary word or even a part of a word for passwords. These are very easy to crack. Alternatively you can use passphrases. Passphrase is easy to remember because it uses a combination of dictionary words but provide a good level of security.

## 22. Security: MFA
For accounts that require enhanced security, enable multifactor authentication if it is supported.
There are many ways to enable MFA, such as Authenticator Apps, USB Security Keys, Email or SMS login confirmations, Biometrics.

You just need to pick a method that works for your services. With two-factor authentication, it is impossible for someone to break into your account with a stolen password.

## 23. Security: Phishing
Always be suspicious of any unexpected email or unusual request ??? especially if it concerns finances, log-in credentials, or clicking a file or link. Don???t open attachments from unknown users, poorly written/vague emails. Think twice before clicking on any links!  Phishing emails today are the result of well-organized criminal businesses, and they are very inventive in crafting messages that get opened. When in doubt look at the email header to see where it actually came from and check if the domain it came from is black listed.
Never give your password to anyone. You will not be asked for your password by the admin, they shouldn't have access to it, and they don't need it for anything.

## 24. Backups

## 25. Where to look to fix it.
If something does not work as expected ..

When it comes to specific error codes and very detailed problems, Google can be a great resource. It is less useful for questions like "my PC is running slowly". In your search for a solution to your problem, remember to include all the relevant details.

Locate the developer or manufacturer's official support forums. Search for things like model number or program name/version and what you want to do with it. You may find there's a particular fix available or advice from other users. For smaller freeware programs, you may even find posts from the developer.

Windows have built-in roll-back feature "System Restore". It will undo recent changes to the registry and hardware and software setup of your computer, without affecting your personal files and holiday photos. It's a good place to start if something has very recently gone wrong.

Safe Mode can be used to uninstall programs or devices, or run fixes, if you can't get into Windows normally. Tap F8 during boot-up to access the boot menu. Choose Safe Mode to launch a special stripped-down version of Windows that keeps drivers and background utilities to a minimum. 

You can find written instructions and video tutorials on how to do most tech related things.

## 26. Task Manager

The Windows Task Manager is a powerful tool, allowing to manage tasks and startup programs as well as monitor system. Using it, you can find out how your computer is performing and what programs are running. This program reports the CPU load, GPU load, logged-in users, and details of I/O processes.

The Task Manager can be launched by pressing Control+Shift+Escape and clicking Start Task Manager.
Alternatively, you can open it by right-clicking on the Windows taskbar and selecting Task Manager, or by typing taskmgr into the File Explorer address bar.

Using Task Manager you can observe what programs your computer can handle at the same time without overloading the CPU. You might be surprised at how difficult some common tasks are for your computer.

If you want to force close offending tasks, highlight them and press the delete key or click "end task".


## 27. When to repair your computer and when to replace it.
It's tempting to look for a new computer when a computer slows down or shows other signs of trouble.
But in order to get the most out of your investment, you probably want to extend its lifespan as long as you can.

There is a lot to consider when you???re deciding whether to repair or upgrade a PC. Eventually any computer will get too old to maintain. 3 to 7 years is a reasonable lifespan, depending on build quality (and progress in new technologies). Computers can be too old or flawed to be worth fixing, don???t waste time fixing a 10-year old machine.

If a computer is new but slow, you should figure out what???s actually causing the slowdown. Slowdowns or other problems may be caused by any of the components in your computer. In order to make sure you spend your money wisely, you need to diagnose the problem. By doing this, you can determine whether you need a replacement or if an incremental repair or upgrade would get you more time.

First, make sure it isn???t a software issue.
- Test your computer for viruses and malware, and ensure there are no infections.
- Use Activity Monitor in Task Manager. If you see a single program consuming all your CPU or RAM, uninstalling it and replacing it with an alternative may speed things up.
- Operating system could be corrupted somewhere. Wiping out and reinstalling operating system may help to fix the problem.

If this doesn't work, you might need to upgrade your hardware.
You can check your CPU and memory usage in Task Manager's Performance Tab. In case CPU or memory usage is particularly high, you'll know which component needs to be upgraded.

It???s also possible that one of your components is failing entirely. A program like HD Tune, CrystalDiskInfo or a vendor's HD utility can be used to test your hard drive and determine if it is failing.

Check your RAM as well. RAM failure could slow your computer down, but it could also make it impossible to turn it on, or it might cause it to shut down randomly. Run a RAM test like Memtest, which will check each stick and see if it???s good or not. If computer does not turn on removing all memory sticks except one will help to find a faulty one.

To determine whether an upgrade is worth your money, look at how much it will cost. I would not recommend fixing an old (> 5-7 yr) computer if its repair costs more than 25 percent of the cost of a new computer. A simple upgrade to one component can usually extend the lifespan of your computer by a couple of years if it is causing a slowdown. 

<-----------------> 1h 50min

## Package managers
All the operating systems depend on a set of software applications to carry out user intended tasks. In the early days, applications were tested against bugs before release to provide a better user experience. Now the software application is released with the intent to apply bug fixes in new versions. Moreover, each application has its updater, or the user has had to figure out how to obtain the upgraded software release.

Linux adopted the timely software management practice by creating packaging formats, software packages, and unique installation tools. This article discusses how the software package installation process upgraded from tarball package installation to DEB and RPM package management.


Linux comes with a package manager installed by default. A package manager is a piece of software that allows you to install, update, and uninstall programs from the terminal, just by entering a few commands.

They're super helpful, especially when you're installing and uninstalling things constantly, as it's much more efficient to install programs through package managers than manually.


Mac's package managers are called (HomeBrew, MacPorts). Not installed by default. [HomeBrew](https://brew.sh) is the most widely used package manager.

On GNU/Linux, the default package manager depends on the distro. For example, Ubuntu comes with APT, Arch comes with Pacman, and so on.

All package managers function in a similar way, but there are some differences in the syntax used for each. It's also important to mention that you can install and run a different package manager than the default.

Windows Package Manager winget command-line tool is bundled with Windows 11 and modern versions of Windows 10 by default as the App Installer.




Chocolatey




## 28. Keyboard

Keyboards come in many styles or layouts. The various models differ from shape, size and feel. The most common keyboard layout is the standardized 104-key US keyboard. This layout has seven groups of keys.

### Overview of keyboard sections

#### Typing keys 
Typing keys are the keys on the keyboard that look like typewriter keys. These keys are arranged in the same way in almost every keyboard. Along with the keys that produce letters and numbers, the typing keys include punctuation keys and 3 keys having specific functions, which are, TAB, CAPS LOCK and BACK SPACE. 
Modifier Keys

#### Modifier keys
The SHIFT, ALT and CTRL keys are called the modifier keys. Because these keys modify the default input of other keys when pressed together. For example, while the CTRL key and the alphanumeric key ???c??? are pressed together the input becomes a command sending termination signal to a program running in Linux terminal.

#### Numeric Keys in Numeric Keypad
Though the alphanumeric keys includes all the numeric keys, still in an standard keyboard there is a separate place of numeric keys, this section of the keyboard is called the Numeric Keypad. It is like calculator keypad. It contains number keys and mathematical operator keys

#### Function keys 
The function keys or F1 through F12 keys are used in programs as shortcut keys to execute frequently performed tasks. 

## 29. Function keys
The function keys are located in a row at the top of the keyboard. These keys allow you to input commands without typing long strings of characters. For example, if you press the F1 key, in most programs it will open the help document of the program.  

F1  In most programs opens the help document.
F2	Renames a selected item. 
F3	Opens the "Find All Files" dialog box. 
F4	Opens the drop-down list box on the toolbar, if there is one. 
F5	Refreshes the current window.  
F6	Switch Panes in Explorer  
F10	Activates Windows Menu Bar  

Hold F2 or F11 during boot up to enter BIOS
Hold F8 during boot up to enter boot menu 

## 30. Windows Key

Windows key is used to provide shortcuts around your system. 

Windows Key	Opens Start Menu
A combination of: 
WindowsKey + M	Minimizes all open windows.
WindowsKey + E	Opens Windows Explorer.
WindowsKey + F	Opens the Find All Files dialog box.
WindowsKey + R	Opens the Run dialog box.

## 31. Common keyboard shortcuts
One of the best methods of becoming more efficient with your computer is to learn and memorize as many keyboard shortcuts as possible. 

Here are some useful common keyboard shortcuts. Windows and Mac OS have virtually the same shortcuts, but Mac OS uses the command key instead of the Control key for the shortcuts.

### Useful Links.

#### [chocolatey](https://chocolatey.org)
Chocolatey is an open-source package manager for Windows. It builds on top of existing Windows technologies like PowerShell and NuGet. Chocolatey operates via command-line interface, which makes it easy to automate software installation and management.

