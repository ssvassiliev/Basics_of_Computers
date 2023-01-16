---
title: "Operating Systems"
teaching: 30
exercises: 
questions:
- "What files are needed to run an MD simulation with AMBER?"
objectives:
- "Learn what types of files are needed to run an MD simulation with AMBER"
keypoints:
- "To run an MD simulation with AMBER 3 files are needed: an input file, a parameter file, and a file describing coordinates/velocities . "
---

## 17. Choosing a computer
Choosing a computer is always about making trade-off decisions. Unless money is absolutely no issue for you, you will have to make some trade-offs such as:

Powerful desktop or portable laptop.
Faster CPU or longer battery life
Lighter weight or less expensive
Bigger and better display or less cost

The trade-offs really depend on how you plan to use the system.  The point is, before you choose your platform, it's important for you to identify your needs.  It may be that you have a limited budget or that you have a specific pressing need. Unless your first priority is to get your job done as soon as possible, there is little need to spend a great deal of money.

In my opinion, there are quite a few differences in the criteria for selecting a desktop computer or laptop. My choice of a laptop computer will be dictated by my preferences. My laptop must be lightweight and small, but I also need a reasonable-sized keyboard and high-definition screen. The size, weight, and screen quality are more important to me than any other factor, including price.  Remember that identifying your needs is the first step in choosing the right platform. 

## 18.Tradeoffs in Buying a Computer

Find balance between price and performance. Don't be obsessed with getting the fastest available hardware components. By choosing components that are not top of the line, you can get a very good performance on a much smaller budget. 

Laptop even the most expensive will not be suitable for serious computations for extended periods of time. 

- Desktops are powerful, upgradable, repairable, flexible price, but not portable. Full-sized parts make hardware reliable and replaceable. Desktops are way more flexible, and you can buy exactly what you need without having to buy unnecessary components. 

- As the system drive, use SSD, and as extra storage, HDD. Install all applications on SSDs and use HDDs for long-term storage or backups only. M2.NVMe SSDs are much faster than regular SSDs and provide the best performance. With NVMe SSD, applications will load much faster and the overall system will be more responsive. 

RAM speed 
- The speed of RAM is a tricky subject and one that actually comes down to several different factors, not just the MHz clock speed.
- Going from 3000MHz to 3600MHz RAM makes very little difference to real-life performance (less than 1% in most cases). 

If you are in a position where you are unsure to go for 8GB of faster RAM or 16GB, you should always opt for the 16GB especially if you are price-conscious. Sure, if you can afford it then grabbing a 16GB+ kit with fast speeds will have some benefits it is only really relevant when small performance gains are important for you.

Laptops are less powerful than desktops but portable. They are expensive and tough to upgrade, maintain, or repair due to miniaturized parts. Only a limited set of features can be customized.

Mobile are very portable, but limited in power and impossible* to repair. Same issues as laptops, but less power and I/O options.

It is likely that at some point you will realize that one PC, even the fastest one, won't suffice to do the work you require. As an example, if the analysis of one sample takes a day and you have thousands of samples to analyze, it will take several years! Using HPC clusters provided by Digital Alliance of Canada might be an option in this case. It would take just a few days to complete all analyses with a thousand of CPUs. Such computational resources are available and free for academic researchers. I encourage you to attend our ACENET basics sessions next week where we will introduce these resources and explain how to use them.


## 19. Keeping your computer in good shape (Maintain your equipment)

In the past computers required to be regularly powered down or rebooted. New computers can go without power cycling for months. However, if computer becomes unusually sluggish, or some programs do not behave as they should even if they are restarted then rebooting your computer is the first thing you should do before trying to solve the problem..

- Cleanup storage. You can free up disk space on your hard drive by running a disk cleanup. This will clean out temporary files as well as delete big attachments and other types of files.

- Organize similar files into folders. Keeping multiple files on your desktop can slow down your machine. Instead, organize similar files into folders where you can easily find them. This will also help streamline the cleaning process when it comes time to delete unnecessary items.

- Delete unused programs. Delete unnecessary programs from your computer to free up storage space. 

- If you have mechanical HDD defragment it to restore performance when needed.

- An important factor in maintaining your computer is installing latest security updates to keep your operating system up-to-date with the latest patches.

- Keep your anti-virus software up-to-date and frequently scan your computer for viruses.

## 20. Password manager
Use a different password for each account, never use same password for several sites. When breaches expose credentials, all accounts that share a password are exposed. 

Of course it is impossible to remember all passwords, so get a password manager like DashLane, BitWarden or 1Password.  With a password manager, you don't have to remember strong, unique passwords for all your accounts. The password manager stores them for you and even helps you generate new, random ones. A password manager is like a digital keyring, it keeps everything in one secure place for easier access.

Generate a strong master password at least 8 chars lond with 3 types of characters. Never use a dictionary word or even a part of a word for passwords. These are very easy to crack. Alternatively you can use passphrases. Passphrase is easy to remember because it uses a combination of dictionary words but provide a good level of security.
  
## 21. Security
Do you need an Antivirus? It depends on the operating system. Windows and macOS include protection against viruses, in one way or another.

Microsoft Defender Antivirus in addition to providing antivirus protection, also manages other security features such as Windows Firewall. However it was reported that is has some significant limitations and you can improve your protection by installing a third-party antivirus such as BitDefender, Avast, AVG.

MacOS Includes Security by Design. The operating system resides on a read-only drive partition, separate from all other programs. To infect another program, a virus needs to modify that program, and that’s not allowed in macOS. To steal private data, a banking Trojan must read memory belonging to your browser, which is likewise not allowed. In the macOS environment, apps are isolated, and limited to accessing their own resources. macOS includes a technology called Gatekeeper, that's designed to ensure that only trusted software runs on your Mac. While Macs aren’t as vulnerable as Windows boxes they still can get malware. 

## 22. MFA
For accounts that require enhanced security, enable multifactor authentication if it is supported.
There are many ways to enable MFA, such as Authenticator Apps, USB Security Keys, Email or SMS login confirmations, Biometrics.

You just need to pick a method that works for your services. With two-factor authentication, it is impossible for someone to break into your account with a stolen password.

## 23. Stay secure
Always be suspicious of any unexpected email or unusual request – especially if it concerns finances, log-in credentials, or clicking a file or link. Don’t open attachments from unknown users, poorly written/vague emails. Think twice before clicking on any links!  Phishing emails today are the result of well-organized criminal businesses, and they are very inventive in crafting messages that get opened. When in doubt look at the email header to see where it actually came from and check if the domain it came from is black listed.
Never give your password to anyone. You will not be asked for your password by the admin, they shouldn't have access to it, and they don't need it for anything.

## 24.Backups

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


## 28. Keyboard

Keyboards come in many styles or layouts. The various models differ from shape, size and feel. The most common keyboard layout is the standardized 104-key US keyboard. This layout has seven groups of keys.

1. Typing keys are the keys on the keyboard that look like typewriter keys. These keys are arranged in the same way in almost every keyboard. Along with the keys that produce letters and numbers, the typing keys include punctuation keys and 3 keys having specific functions, which are, TAB, CAPS LOCK and BACK SPACE. 
Modifier Keys

The SHIFT, ALT and CTRL keys are called the modifier keys. Because these keys modify the default input of other keys when pressed together. For example, while the CTRL key and the alphanumeric key ‘c’ are pressed together the input becomes a command sending termination signal to a program running in Linux terminal.

2. Numeric Keys in Numeric Keypad

Though the alphanumeric keys includes all the numeric keys, still in an standard keyboard there is a separate place of numeric keys, this section of the keyboard is called the Numeric Keypad. It is like calculator keypad. It contains number keys and mathematical operator keys

## 29. Function keys
The function keys are located in a row at the top of the keyboard. These keys allow you to input commands without typing long strings of characters. 

For example, if you press the 
F1 key, in most programs it will open the HELP DOCUMENT of the program.
F2	Renames a selected item.
F3	Opens the "Find All Files" dialog box.
F4	Opens the drop-down list box on the toolbar, if there is one.
F5	Refreshes the current window.
F6	Switch Panes in Explorer
F10	Activates Windows Menu Bar

Hold F2 or F11 during boot up to enter BIOS
Hold F8 during boot up to enter boot menu 


# 30. Windows key
This key is used to provide shortcuts around your system. 

Windows logo key	Opens Start Menu
A combination of: 
Windows logo key+M	Minimizes all open windows.
Windows logo key+E	Opens Windows Explorer.
Windows logo key+F	Opens the Find All Files dialog box.
Windows logo key+R	Opens the Run dialog box.

Special purpose keys.

Alt + PrintSc - Screenshot your active window.
Ctrl/Cmd + V - “Paste clipboard object”

Shift usually alters a command slightly, such as
Ctrl/Cmd + Shift + V - “Paste without formatting”

On macOS:

To take a screenshot, press and hold these three keys together: [Shift, Command, and 3]. 
Press and hold  [Shift, Command, and 4] to capture a fraction of screen

## 31. Common keyboard shortcuts
Here are some useful common keyboard shortcuts. Windows and Mac OS have virtually the same shortcuts, but Mac OS uses the command key instead of the Control key for the shortcuts.

## 32. What is electronic computer?

In the computer, there are many millions of nanoscale electronic switches called transistors capable of flipping on and off billions of times each second. Except for a busted switch, a switch can be on or off, closed or open. When a switch is "on" or "closed", an electrical signal passes through it, while when it is "off" or "open," that signal is blocked. In computer science a switch that is "on" is represented by a 1 and a switch that is "off" is represented by a 0. 


## 33. Why do computers use binary numbers

Computers use binary code inside the central processing unit (CPU) and RAM because this is the easiest and simplest way to record and process the electrical currents that run through their hardware. Representation of data in 1s and 0s reflects how computers are organized internally. By representing data in a way that matches how an actual computer works, scientists enabled computers to carry out data processing and instructions processing with the same components. With this way of organizing the computer and the data it processes, we are now able to achieve incredible computational performance and storage capacities.

[ Binary number system is positional numeral system employing 2 as the base and so requiring only two different symbols for its digits, 0 and 1, instead of the usual 10 different symbols needed in the decimal system. ]

Another reason why computers use binary system is binary logic. Boolean algebra defines operators for manipulating manipulating combinations of True and False values.  True and False sounds similar to 1 and 0, or on and off. Thus it is no surprise that boolean algebra is a foundation of digital circuit design. 

If you stack transistor switches together, you create a logic gate with two inputs. The gate compares two different input states (for example if each of the switches is on or off) to determine its output. Therefore, there are three main types of gates and three different logical operations available in computing: AND, OR, and NOT. This is how computers make decisions and is the basic principle of computer programming. A program is made up of logical sets of instructions. An example of how this works in real life might be: “If I push the button on the front door or I push the button on the garage door the doorbell will ring". 


## 34. TRUE and FALSE (Boolean Logic)
Let's have a quick look at Basic Boolean Operations.
A very useful tool when working with boolean logic is the truth table.

AND: the result is T if, and only if, all inputs are T; if any input is F, the result is F.
OR: the result is T if any inputs are T; the result is F if, and only if, all inputs are F.
NOT: the result is T if the input is F, and F if the input is T.

These basic operations can be combined in any number of ways to build, literally, everything else in a computer. With logic gates, we can create circuits for data storage and for mathematical operations such as addition, multiplication, division, etc.

One neat thing about Boolean Logic is that it converts directly into electronic circuitry.
We used True (T) and False (F) to indicate logic states. When we talk about actual circuits, it's more typical to talk about high (H) and low (L) signals. Computers become “faster” by getting switches that can go from H to L faster.


## 35. Hexadecimal number system

If you worked with image editing or webpage design you are probably familiar with Hexadecimal Colors. In this color coding system intensity of each of the three primary colors (red, green and blue) is represented by two hexadecimal digits between 00 and FF to create 256 possible values, thus resulting in more than 16 million possible colors. 

The hexadecimal number system is a type of number system, that has a base value equal to 16. It is also pronounced sometimes as 'hex'. Hexadecimal numbers are represented by 16 symbols. These symbols are 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, A, B, C, D, E and F.

21 (dec) = 1x16^1 + 5x16^0 = 15 (hex)

Hexadecimal number system provides convenient way of converting large binary numbers into more compact and smaller groups because 4 binary digits are represented with just one hexadecimal digit.

Hex system is commonly used in Computer programming and Microprocessors. Hexadecimal number system is used to describe locations in memory for every byte. These hexadecimal numbers are also easier to read and write than binary or decimal numbers for Computer Professionals. There is wide number of advantages in data science field, artificial intelligence and machine learning.

The major disadvantage of Hexadecimal number system is that it may not an easy to read and write for people, and also difficult to perform operations like multiplications, divisions using hexadecimal number system. 

## 36. Everything in computers is digits.

In computers numbers encode both commands and data. Everything on a computer is represented as streams of binary numbers. Audio, images and characters all look like binary numbers in machine code. These numbers are encoded in different data formats to give them meaning, eg the 8-bit pattern 01000001 could mean the number 65, the character 'A', or a color in an image.

## 37. Pointers
Pointers provide a very efficient access to variables stored in memory and are used in many programming languages. A pointer tells you where something is, like an address or a phone number and many other things that you encounter every day. However pointers and pointer arithmetic are a leading factor of confusion for many new, and even experienced programmers. 

I'll try to explain as simple as possible what are pointers. Suppose the computer is a community, every data stored in the computer is a house, and every smallest unit of memory is a person in the house, and your friend happens to live in this community. Now you come to this community to visit friend. You want to find his house, so you check his address. It points to the location of your friends house, and you find this house according to address.

Thus pointers are variables that store the addresses of other variables. In other words, pointer points to a variable that is stored at a given address. 

## 38. So why don’t I need to enter numbers?

Since everything in the computer is a number, why it doesn't require me to enter any numbers?
You don’t enter in billions of numbers because people have built operating systems. An operating system is the most important software that runs on a computer. It manages the computer's memory and processes, as well as all of its software and hardware. It also allows you to communicate with the computer without knowing how to speak the computer's language. Without an operating system, a computer is useless.

In early days of electronic computers (1955–65) there was no operating system. A programmer would first write the program on paper in FORTRAN or assembler, then punch it on cards. He would then bring the card deck down to the input room and hand it to one of the operators and go drink coffee until the output was ready.

When the computer finished whatever job it was currently running, an operator would go over to the printer and tear off the output and carry it over to the output room, so that the programmer could collect it later. Then he would take one of the card decks that had been brought from the input room and read it in. If the FORTRAN compiler was needed, the operator would have to get it from a file cabinet and read it in. 

Much computer time was wasted while operators were walking around the machine room. People quickly looked for ways to reduce the wasted time. The solution was the batch system. The idea behind it was to collect a tray full of jobs in the input room and then read them onto a magnetic tape. Thus the first operating system was born and a long way (almost a century) of OS development began.     

## First digital computer
~~~
The first digital computer was designed by the English mathematician Charles Babbage who died 1871. He never got his 'analytical engine' working properly because it was purely mechanical, and the technology could not produce the required wheels, gears, and cogs to the high precision that he needed. And of course the analytical engine did not have an operating system.

Interestingly, Babbage realized that he would need software for his 'analytical engine', so he hired Ada Lovelace, who was the daughter of the British poet Lord Byron, as the world's first programmer. The programming language Ada® is named after her.
~~~

### Polls:
#### 1.
What is the number of charge levels in a quad level cell?
1. 4
2. 8
3. 12
4. 16

