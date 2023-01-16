---
title: "What is a Computer"
teaching: 30
exercises: 0
questions:
- "What is a computer?"
- "How do computers work and what are their main functions?"
- "What are the different categories of computers?" 
- "How does a computer function and what are the necessary components for it to do so?"
- "What is computer hardware?"
- "What is computer software?"
objectives:
- "Learn about the main functions of a computer and how it can help you"
- "Understand what components are required for a computer to function."
- "Learn what computer hardware is and how it works."
- "Learn what is system software and what does it do?"
- "Get a better understanding of what application software is and how it works."
keypoints:
- "A computer is a programmable device that processes data, produces results and stores the results for future use" 
- "Computers can be categorized in four types by their size and performances"
- "In order for a computer to function properly, it needs three components: hardware, an operating system, and software."
- "A computing platform is the stage on which a computer program can run"
---

Poll questions: 

1. The first exascale supercomputer Frontier was built with what type of CPUs?
    1. Intel Xeon
    2. AMD Epyc
    3. IBM Power
    4. Apple M2

2. What components are required for a computer to function?
    1. Hardware, device drivers, operating system
    2. Operating system, application software, hardware
    3. Hardware, application software
    4. Boot loader, operating system, application software, CPU

## 1. Introduction 
A few basic computer topics will be covered in this lesson. We will learn what is inside a computer and how it works, how to use and maintain a computer, and how to handle possible issues.

## 2. What is a computer?
In its original sense, the term "computer" referred to someone who performed mathematical calculations. In doing their jobs, human computers were supposed to follow fixed rules and they had no authority to alter them. The term was later applied to mechanical devices that replaced human computers.

Today a computer is a programmable device that  
- accepts data as input
- processes that data with a set of instructions (a program) 
- produces results as output
- stores the results for future use

## 3. What are the different types of computers? 
There are different types of computers:
- supercomputers
- mainframes
- minicomputers (servers, don't confuse with mini-PCs)
- microcomputers

![](../fig/compouter_types.png)

### Supercomputers
Supercomputers are unique facilities, providing exceptional computing power. The term is used to describe the fastest high-performance systems available at any given time. Computers of this type are primarily used for scientific and engineering work requiring extremely fast computations.

Currently the most powerful supercomputer is Frontier. The Frontier has achieved a performance of 1.102 exaFLOPS. One exaFLOP is a quintillion (10<sup>18</sup>) double precision floating point operations per second.

### Mainframes
Mainframes are a type of computers that generally are known for their large size, amount of storage, processing power and high level of reliability. Mainframes first appeared in the early 40s. Companies and governments use mainframes as central computers to carry out their day-to-day operations. Mainframes are primarily used for mission-critical applications requiring high volumes of data processing such as census, industry and consumer statistics, and enterprise resource planning. Most mainframes are built by IBM.

### Minicomputers (Midrange Servers)
Computers called minicomputers have many of the features and capabilities of mainframe computers, but are smaller. DEC introduced mini computers in 1965 as a smaller and inexpensive alternative to mainframes. The PDP-1 (Programmed Data Processor) was the first mini computer. It is famous for being the computer most important in the creation of hacker culture. And history's first space shooter game Spacewar! featuring orbital mechanics around a gravitational star.

![](../fig/spacewar1.jpg)

https://www.youtube.com/watch?v=1EWQYAfuMYw

In recent years mini computers evolved into a midrange computers or midrange servers running business and scientific applications. Midrange computer is a loosely defined term for a computer system that is more powerful than a general-purpose personal computer but less powerful than a full-size mainframe computer.

### Microcomputers
A microcomputer is a small, personal computer that is typically used by only one person at a time. 

## 4. What components are required for a computer to function?
There are three components that every computer needs to function, regardless of its type:

1. Hardware
2. Operating system (system software + device drivers)
3. Application software

### Computer Hardware 
Hardware is stuff you can touch as opposed to the software which is abstract and exists in a virtual world of computer code. Hardware is made of materials mostly metals and semiconductors. It includes various components that are required for a computer to run.

### Computer Software
Software, in its most general sense, is a set of instructions or programs instructing a computer to do specific tasks. All computer programs such as executable files, libraries, and scripts can be defined as software. Software is stored in computer memory and can not be physically touched.

Software consists of instructions that upon execution instruct hardware to perform tasks for which it was designed. At its lowest level an executable program is composed of machine language instructions specific to a particular processor. 

A machine language consists of groups of binary values signifying processor instructions that change the state of the computer from its preceding state. For example an instruction may change the value stored at the particular memory location inside the computer. This effect is not directly observable by the user. An instruction may also cause something appear on the display of the computer system. Such state change is visible for the user. The processor carries out instructions in the order they are provided unless it is instructed to jump to a different instruction or interrupted. 

There are two types of software: system software, also known as an operating system, and application software.

### Operating System
Operating system is designed to operate the computer hardware, to provide basic functionality and to provide a platform for running application software. Operating system is an essential collection of computer programs that manages resources and provides common services for other software. Operating systems are composed of system software and device drivers. Boot loaders, command line shells, device drivers and windows managers are core parts of operating systems. 

Device drivers are programs that controls a particular type of device that is attached to a computer. Each  device needs a corresponding device driver. Thus a computer needs multiple device drivers. Also, operating systems come with software designed to assist users in maintaining and caring for their computers. This software is referred to as utilities.

An operating system can be compared to the driver of a car. The driver might appear as if all he is doing is instructing the car where to go. However, in fact he is bringing in a variety of information from different parts of a vehicle. He is also taking in any information that is given to him, like a map, instructions for where to travel, and road signs that he encounters along the way. An operating system within a computer interacts with a variety of components inside it in the same way that a driver interacts with a car. An operating system acts as a middle man between users and the computer by creating an environment that allows them to interact with the computer as efficiently as possible.

### Application software and computing platforms
Application software uses the computer system to perform useful work or provide entertainment functions beyond the basic operation of the computer itself.

In order for a piece of application software to run, it requires an appropriate environment which is known as a platform. Platforms can refer to a variety of things depending on the context. The term platform may refer to hardware or to an operating system. A platform can also be a Web browser or other underlying application software such as the Java or QuickTime, for example. Computing platforms can be thought of as the stage on which computer programs can run.

As an example, operating systems run on hardware, so when it comes to operating systems, hardware is a platform. In the case of Office or Photoshop, they are both programs that run on an operating system. This means that their platform consists of the operating system and the underlying hardware combined. As a final example, Java applications only need the Java runtime environment to operate, which means they can be run on any computer regardless of its hardware and its operating system, as long as Java runtime is installed on it.

Despite the fact that a lot of things work across different platforms, some more involved programs, like video editing software or games, do not run well or do not work at all across all platforms.

Hardware and software require each other and neither can be used without another.


