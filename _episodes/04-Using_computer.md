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
- "Choose optimal computer for your work"
- "Maintain your computer"
keypoints:
- "Use a different password for each account and beef up security using MFA if possible."
---

### 23. System requirements.
Now that we have discussed operating systems, let's discuss how to use them. When you want to use a piece of software that did not come with your compute you must install it. 

All computer software requires certain hardware components or other resources on a computer in order to function effectively. Most software vendors list minimal and recommended system requirements. The system requirements are usually viewed as guidelines rather than absolute rules.
Generally, system requirements indicate which computer configurations will be most suitable for a particular software. 

The most common requirements are the physical computer resources, such as Processor, Memory, GPU, Storage and Operating System

How to check if your computer meets a software's system requirements?
Windows:
- Task manager (Ctrl + Shift + Escape) or search for it. 
- "About" section
MAC: 
- Apple -> About this MAC, click "More info" if needed

### 24. File extensions.
A file extension is a suffix added to the name of a file to indicate what type of data is stored in the file. A file extension comes after the period in a filename and is typically made up of three or four characters, however there is no strict convention about the length of file extension. They can be as short as one character (.c, .m, .f). 3-4 character extensions are simply convenient. They are not too long, easy to recognize and remember. At the same time they permit to describe a variety of data types such as txt, doc, png, pdf, csv etc. A filename can include multiple periods.  In most cases, the extension includes only the characters after the final period. 

There are exceptions, however, such as the extension .tar.gz. This extension indicates that the file contains a "tape archive" .tar data file which is compressed with gzip.  So to read such a file you need first to unzip it and then unpack the archive. 

An operating system might rely solely on the file extension to determine which application to use to open it, or it might also rely on metadata stored inside a file. Each OS varies in terms of how it uses extensions when matching files to applications and the degree to which it uses them. Windows, for example, relies heavily on file extensions and windows programs cannot open files without them.  Linux and MAC rely on extensions when they're available, but they typically permit to open files without extensions as long as you are using the right program.

If you have a file with an extension that is not recognized by OS, you can manually associate it with a program. 

Example - .ent associate with VS Code.

- text files: doc, pdf, rtf, txt 
- system files: sys, cfg, dll, ini, tmp, ico
- video files: avi, mpg, wmf, flv, mp4, vob
- audio files: mp3, flac, alac, wav, pcm, ogg
- programming languages: c, f, R, py, java, m, jl
- internet-related files: html, css, cer

### 25. Identifying and resolving problems.

If something does not work as expected you need to identify and fix the problem. 
- When troubleshooting, the first step is gathering information on the issue, such as a behavior that is not desired or a lack of functionality expected. 
- Identify exactly what is it that your computer is not doing that you want, or what is it doing that you don't want?
- Think of possible causes for the problem and write them down.

- Identifying the source of your computer issue will make finding a solution easier. Make a list of things that could be causing the problem. The process of elimination may help you figure out what's wrong. One by one, test each item on the list starting with the most likely cause of the problem.

- Note any error messages you encounter. When your computer gives you an error message, make sure you write down as many details as you can. Using the Internet is a good place to start searching for a solution.  Other users may have encountered similar issues, and solutions are often posted online. Google's search engine is most effective when you search for specific error codes and very detailed problems. It is less useful for general questions like "my PC is running slowly". In your search for a solution to your problem, remember to include all the relevant details.

- Locate the developer or manufacturer's official support forums. Search for things like model number or program name/version and what you want to do with it. You may find there's a particular fix available or advice from other users. For smaller freeware programs, you may even find posts from the developer.

- Write down your steps: Once you start troubleshooting, you may want to take a note of each step you take. This way, you'll be able to remember exactly what you've done and can avoid repeating the same mistakes. 

- Restart the computer. Restarting the computer is a good thing to try. This can solve a lot of basic issues you may experience with your computer.

- Windows have built-in roll-back feature `System Restore`. It will undo recent changes to the registry and hardware and software setup of your computer, without affecting your personal files and holiday photos. It's a good place to start if something has very recently gone wrong.

- `Safe Mode` can be used to uninstall programs or devices, or run fixes, if you can't get into Windows normally. Tap F8 during boot-up to access the boot menu. Choose `Safe Mode` to launch a special stripped-down version of Windows that keeps drivers and background utilities to a minimum. 

- You can find written instructions and video tutorials on how to do most tech related things.

## 26. Keeping your computer in good shape 

- It is important to update your operating system and software on a regular basis. Why should you do this? The most important reason is security. Hackers discover new security flaws on a daily basis and exploit them to commit attacks. Upgrading to the latest version OS will patch known security flaws and make you computer more secure overall. 

Further, you will have access to the latest features, including increased stability and responsiveness. The latest version of your OS may make it easier for you to install new applications. 

- Keep your anti-virus software up-to-date and frequently scan your computer for viruses.

- Organize similar files into folders. Keeping multiple files on your desktop can slow down your machine. Instead, organize similar files into folders where you can easily find them. This will also help streamline the cleaning process when it comes time to delete unnecessary items.

- Delete unused programs. Delete unnecessary programs from your computer to free up storage space. 

- If you have mechanical HDD defragment it to restore performance when needed.

In the past computers required to be regularly powered down or rebooted. New computers can go without power cycling for months. However, if computer becomes unusually sluggish, or some programs do not behave as they should even if they are restarted then rebooting your computer is the first thing you should do before trying to solve the problem..

- Cleanup storage. You can free up disk space on your hard drive by running a disk cleanup. This will clean out temporary files as well as delete big attachments and other types of files.

Clear apt cache
~~~
sudo apt-get clean 
~~~

Remove no longer needed packages
~~~
sudo apt-get autoremove
~~~

# Security

## 27. Security: Passwords
Use a different password for each account, never use same password for several sites. When breaches expose credentials, all accounts that share a password are exposed. 

Of course it is impossible to remember all passwords, so get a password manager like DashLane, LastPass or RoboForm.  With a password manager, you don't have to remember strong, unique passwords for all your accounts. The password manager stores them for you and even helps you generate new, random ones. A password manager is like a digital keyring, it keeps everything in one secure place for easier access.

Generate a strong master password at least 8 chars lond with 3 types of characters. Never use a dictionary word or even a part of a word for passwords. These are very easy to crack. Alternatively you can use passphrases. Passphrase is easy to remember because it uses a combination of dictionary words but provide a good level of security.

Some password managers offering free options:
[Dashlane](https://www.dashlane.com)
[LastPass](https://www.lastpass.com/pricing)
[RoboForm](https://www.roboform.com)


## 28. Security: Malware and Viruses 
Do you need an Antivirus? It depends on the operating system. Windows and macOS include protection against viruses, in one way or another.

Microsoft Defender Antivirus in addition to providing antivirus protection, also manages other security features such as Windows Firewall. However it was reported that is has some significant limitations and you can improve your protection by installing a third-party antivirus such as BitDefender, Avast, AVG.

MacOS Includes Security by Design. The operating system resides on a read-only drive partition, separate from all other programs. To infect another program, a virus needs to modify that program, and that’s not allowed in macOS. To steal private data, a banking Trojan must read memory belonging to your browser, which is likewise not allowed. In the macOS environment, apps are isolated, and limited to accessing their own resources. macOS includes a technology called Gatekeeper, that's designed to ensure that only trusted software runs on your Mac. While Macs aren’t as vulnerable as Windows boxes they still can get malware. 


## 29. Security: Multifactor Authentication 
For accounts that require enhanced security, enable MFA if it is supported.
There are many ways to enable MFA, such as Authenticator Apps, [USB Security Keys](https://www.yubico.com/), Email or SMS login confirmations, Biometrics.

You just need to pick a method that works for your services. With two-factor authentication, it is impossible for someone to break into your account with a stolen password.

## 30. Security: Phishing 

Always be suspicious of any unexpected email or unusual request – especially if it concerns finances, log-in credentials, or clicking a file or link. Don’t open attachments from unknown users, poorly written/vague emails. Think twice before clicking on any links!  Phishing emails today are the result of well-organized criminal businesses, and they are very inventive in crafting messages that get opened. When in doubt look at the email header to see where it actually came from and check if the domain it came from is black listed.
Never give your password to anyone. You will not be asked for your password by the admin, they shouldn't have access to it, and they don't need it for anything.

## 31. Backups
There are many ways that data can be lost, such as hard drive failures, ransomware attacks, or even human error or theft. Don't let your important computer data disappear. Make a copy or archive of it regularly. Be sure to store backup copies separately from an original device.

It is recommended that you make two copies of your data: one local copy (on a different device) and one offsite copy. It typically means having a backup of your data on an external drive, a backup on a cloud service, and your original data on your computer.


## 32. Task Manager

The Windows Task Manager is a powerful tool, allowing to manage tasks and startup programs as well as monitor system. Using it, you can find out how your computer is performing and what programs are running. This program reports the CPU load, GPU load, logged-in users, and details of I/O processes.

The `Task Manager` can be launched by pressing `Control+Shift+Escape` and clicking `Start Task Manager`.
Alternatively, you can open it by right-clicking on the Windows taskbar and selecting `Task Manager`, or by typing taskmgr into the File Explorer address bar.

Using `Task Manager` you can observe what programs your computer can handle at the same time without overloading the CPU. You might be surprised at how difficult some common tasks are for your computer.

If you want to force close offending tasks, highlight them and press the delete key or click `end task`.

The equivalent of `Task Manager` on MacOS is `Activity Monitor`.


## 33. How to choose the right computer
Choosing a computer is always about making trade-off decisions. In most cases, you will have to make some sacrifices unless you don't care about cost. Depending on your needs, you can choose between:

- Powerful desktop or portable laptop.
- Faster CPU or longer battery life
- Lighter weight or less expensive
- Bigger and better display or less cost

The trade-offs really depend on how you plan to use the system.  The point is, before you choose your platform, it's important for you to identify your needs.  It may be that you have a limited budget or that you have a specific pressing need. Unless your first priority is to get your job done as soon as possible, there is little need to spend a great deal of money.

In my opinion, there are quite a few differences in the criteria for selecting a desktop computer or laptop. The size, weight, and screen quality are among the most important factors for me, but you may have different needs and you priorities will be different. A good starting point for choosing the right platform is identifying your needs. 


### 34. Desktop,  Laptop or Chromebook?
A laptop or a Chromebook are logical choices if portability is your top priority. In general, however, desktops are a much better product than laptops. There are several reasons why desktops are superior to laptops.

1. Desktops are more powerful
One of the main reasons to buy a desktop is its power. When all components must fit into such a small device, laptops are limited in their power and performance. Only desktop computers offer top-of-the-line performance. You can expect to pay significantly more if you want a laptop with specs similar to a desktop.

While modern high end laptops are very fast, top performance is available only in short bursts. They are not designed to handle high loads for extended periods of time.

There is no doubt that power is important, but it depends a lot on what you intend to use the computer for. When it comes to browsing the internet, watching videos, and writing documents, desktops have almost no advantage over laptops.

2. Desktops Have Lower Pricing
Like for like, desktops are significantly cheaper than laptops. Compared to laptops with similar characteristics, desktops cost significantly less. When it comes to high-end computers, laptops can cost twice as much as desktop computers. You could easily spend the difference in price on more powerful components or peripherals if you're paying significantly less for the same specs.

3. Desktops Are Easier to Upgrade
Using a laptop is convenient when you want to move it from place to place, but upgrading it is not easy. If you want to upgrade a desktop, it's simply a matter of opening the case and adding or replacing a component. 

The components of a laptop are packed closely together. As a result, you are restricted in what you will be able to upgrade. In addition, it makes it difficult to actually install anything.

4. Desktops Are Easier to Repair
Repairing laptops can also be a challenge. Components need to be replaced when they break. On a desktop, this can be done with minimal technical knowledge. Opening up a laptop without breaking anything can be challenging, and individual components may not always be replaceable.

5. Desktops Can Be Left On
Desktops have the advantage of being able to remain on for an indefinite period of time, something that many people ignore. This is useful for users who want to run programs overnight or who wish to use their computer as a remote server. A laptop can also be left on indefinitely, but they are not designed for this purpose, and you run the risk of damaging the hardware. 

8. Desktops Offer More Ports
Desktops have a wide variety of ports and this gives you the freedom to connect as many peripherals as you want. If a specific port isn't available, it may also be possible to add one.

Laptops do not offer this level of flexibility. There's a limit to how many ports can be installed in a laptop computer due to space restrictions. If you want to add new peripherals, this can be problematic.

9. You Can Build Your Own Desktop
A desktop gives you the freedom to build your own system exactly how you want it. It allows you to design a computer tailored to your specific requirements and provides a much greater level of choice. This level of customization is not necessary for everyone, but it is only available on desktop computers.

Overall, desktops are superior to laptops if portability is not required.

There are also Chromebooks. Since Chromebooks take advantage of cloud resources, they generally have lower processor speeds, less RAM, and less local storage than laptops. At first, they were essentially low-performance "thin clients", designed and optimized for remote access. But this is changing with the evolution of ChromeOS. High-end Chromebooks can run Linux and Android applications locally.

Overall Chromebooks are excellent for students, office workers, and anyone who works entirely on the web, but not so great for people who need more advanced capabilities of locally installed software.

## 35. Choosing hardware components.
- When buying a computer it is also important to balance price and performance. Don't be obsessed with getting the fastest available hardware components, it is not necessary. With components  that are not top-of-the-line, you can get excellent performance for less money. I will briefly point out a few other things to consider when purchasing a computer. 

- As the system drive, use SSD, and as extra storage, HDD. Install all applications on SSDs and use HDDs for long-term storage or backups only. M2.NVMe SSDs are much faster than regular SSDs and provide the best performance. With NVMe SSD, applications will load much faster and the overall system will be more responsive. 

- Choose the right memory
 - Going from 3000MHz to 3600MHz RAM makes very little difference to real-life performance (less than 1% in most cases). 
 - Don’t pay for RAM speeds your system doesn’t support. 
 - Speed of RAM depends on two factors, not just the MHz clock speed. In order to determine how fast your RAM is, you must take into account both the CAS (Column Access Strobe) latency and clock speed.
 -If you are in a position where you are unsure to go for 8GB of faster RAM or 16GB, you should always opt for the 16GB especially if you are price-conscious. Sure, if you can afford it then grabbing a 16GB+ kit with fast speeds will have some benefits it is only really relevant when small performance gains are important for you.

- Make sure you pick the right graphics card for your needs. Many users are satisfied with integrated graphics. If you plan to create content, run simulations, train ML models, or do photogrammetry on your computer, you'll need a discrete graphics card.

You can find plenty of guides on how to build your own PC. Here is one: [Want a Better PC? Try Building Your Own.](https://www.wired.com/story/how-to-build-a-pc/)

It is likely that at some point you will realize that one PC, even the fastest one, won't suffice to do the work you require. As an example, if the analysis of one sample takes a day and you have thousands of samples to analyze, it will take several years! Using HPC clusters provided by Digital Alliance of Canada might be an option in this case. It would take just a few days to complete all analyses with a thousand of CPUs. Such computational resources are available and free for academic researchers. I encourage you to attend our ACENET basics sessions next week where we will introduce these resources and explain how to use them.


## 36. When to repair your computer and when to replace it.
It's tempting to look for a new computer when a computer slows down or shows other signs of trouble.
But in order to get the most out of your investment, you probably want to extend its lifespan as long as you can.

There is a lot to consider when you’re deciding whether to repair or upgrade a PC. Eventually any computer will get too old to maintain. 3 to 7 years is a reasonable lifespan, depending on build quality (and progress in new technologies). Computers can be too old or flawed to be worth fixing, don’t waste time fixing a 10-year old machine.

If a computer is new but slow, you should figure out what’s actually causing the slowdown. Slowdowns or other problems may be caused by any of the components in your computer. In order to make sure you spend your money wisely, you need to diagnose the problem. By doing this, you can determine whether you need a replacement or if an incremental repair or upgrade would get you more time.

First, make sure it isn’t a software issue.
- Test your computer for viruses and malware, and ensure there are no infections.
- Use Activity Monitor in Task Manager. If you see a single program consuming all your CPU or RAM, uninstalling it and replacing it with an alternative may speed things up.
- Operating system could be corrupted somewhere. Wiping out and reinstalling operating system may help to fix the problem.

If this doesn't work, you might need to upgrade your hardware.
You can check your CPU and memory usage in Task Manager's Performance Tab. In case CPU or memory usage is particularly high, you'll know which component needs to be upgraded.

It’s also possible that one of your components is failing entirely. A program like HD Tune, CrystalDiskInfo or a vendor's HD utility can be used to test your hard drive and determine if it is failing.

Check your RAM as well. RAM failure could slow your computer down, but it could also make it impossible to turn it on, or it might cause it to shut down randomly. Run a RAM test like Memtest, which will check each stick and see if it’s good or not. If computer does not turn on removing all memory sticks except one will help to find a faulty one.

To determine whether an upgrade is worth your money, look at how much it will cost. I would not recommend fixing an old (> 5-7 yr) computer if its repair costs more than 25 percent of the cost of a new computer. A simple upgrade to one component can usually extend the lifespan of your computer by a couple of years if it is causing a slowdown. 


## 37. Watch our schedule of training sessions to learn how to use different software

We offer training sessions to teach you how to use different widely used application software such as Excel, OpenRefine, Python, R, Matlab, Paraview, and more. On this last slide, you will find links to our training sessions as well as to self-study materials.

## 33. Keyboard

Keyboards come in many styles or layouts. The various models differ from shape, size and feel. The most common keyboard layout is the standardized 104-key US keyboard. This layout has seven groups of keys.

### Overview of keyboard sections

#### Typing keys 
Typing keys are the keys on the keyboard that look like typewriter keys. These keys are arranged in the same way in almost every keyboard. Along with the keys that produce letters and numbers, the typing keys include punctuation keys and 3 keys having specific functions, which are, TAB, CAPS LOCK and BACK SPACE. 
Modifier Keys

#### Modifier keys
The SHIFT, ALT and CTRL keys are called the modifier keys. Because these keys modify the default input of other keys when pressed together. For example, while the CTRL key and the alphanumeric key ‘c’ are pressed together the input becomes a command sending termination signal to a program running in Linux terminal.

#### Numeric Keys in Numeric Keypad
Though the alphanumeric keys includes all the numeric keys, still in an standard keyboard there is a separate place of numeric keys, this section of the keyboard is called the Numeric Keypad. It is like calculator keypad. It contains number keys and mathematical operator keys

#### Function keys 
The function keys or F1 through F12 keys are used in programs as shortcut keys to execute frequently performed tasks. 

## 34. Function keys
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

## 35. Windows Key

Windows key is used to provide shortcuts around your system. 

Windows Key	Opens Start Menu
A combination of: 
WindowsKey + M	Minimizes all open windows.
WindowsKey + E	Opens Windows Explorer.
WindowsKey + F	Opens the Find All Files dialog box.
WindowsKey + R	Opens the Run dialog box.

## 36. Common keyboard shortcuts
One of the best methods of becoming more efficient with your computer is to learn and memorize as many keyboard shortcuts as possible. 

Here are some useful common keyboard shortcuts. Windows and Mac OS have virtually the same shortcuts, but Mac OS uses the command key instead of the Control key for the shortcuts.

### Useful Links.

#### [chocolatey](https://chocolatey.org)
Chocolatey is an open-source package manager for Windows. It builds on top of existing Windows technologies like PowerShell and NuGet. Chocolatey operates via command-line interface, which makes it easy to automate software installation and management.

## Downloading files
### Where is the file I just downloaded?

Files you've downloaded are automatically saved in the Downloads folder. In Windows this folder is usually located in C:\Users\Your_account\Downloads.
In MAC OS /Users/Your_account/Downloads
 
### Can I download files to different places?

Internet browsers allow you to specify where you want to download files.
To configure Chrome or Firefox navigate to "Settings" -> "Download". 

Here you can also configure browser to "Ask where to save each file before downloading"

