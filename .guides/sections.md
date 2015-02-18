---
title: What is a computer system?
files: []
layout: 2-panels-tree

---
Most of you understand what a computer system is already. You may be surprised at how many household devices are computer systems or contains computer systems. In a moment, we'll list some of them our for you, including Alarm Clocks, Washing Machines, Phones and Cameras.


## The 4 main components
Any computer system is made up of 4 main components

- **Input** : information and data from components or devices provided to the computer system
- **Output** : information provided by the computer system to other devices and components
- **Store** : Computer systems need to store data so it can be processed. This includes memory, disk drives and other forms of storage.
- **Processing** : This generally means the CPU (or processor), which is the brain of the computer system. It involves running programs as well as coordinating the flow of information between input devices, output devices and storage.

Let's take a look at typical examples of the 4 components of a computer system.




---
title: Input Devices
files: []

---
Take a look at the following input devices and you should get a clear idea about what an input device is.

>An input device is a peripheral (piece of computer hardware equipment) used to provide data and control signals to an information processing system such as a computer or other information appliance.

| Input Devices |
|-|
| ![](.guides/img/input.jpg)
(show other types)


---
title: Output devices
files: []

---
> An output device is any piece of computer hardware equipment used to communicate the results of data processing carried out by an information processing system (such as a computer) into human-understandable form.

| Output Devices |
|-|
| ![](.guides/img/output.jpg)
(show other types)
---
title: Store
files: []

---
There are two main types of stores. We'll disucss these storage types in more detail in a later section.

| Primary Storage - Memory|
|-|
| ![](.guides/img/prim-storage.jpg) |
| Primary storage (or main memory or internal memory), often referred to simply as memory, is the only one directly accessible to the CPU. The CPU continuously reads instructions stored there and executes them as required. RAM and ROM are the most common examples.|

| Secondary Storage - Memory |
|-|
| ![](.guides/img/sec-storage.jpg) |
| Secondary storage (also known as external memory or auxiliary storage), differs from primary storage in that it is not directly accessible by the CPU. A hard drives is the most common example although you can see there are many others. Secondary storage is most often *non-volatile* which means it retains information when the power is switched off.|


---
title: Example Computer Systems
files: []

---
Here is a table of household devices and a few of the components they might have.

| Device | Input | Output | Processor | Store |
|-|-|-|-|-|
| ![](.guides/img/mac.jpg)   | Keyboard, mouse, touchpad, microphone, USB, network | Screen, network, USB, speakers | Intel or AMD processors | Hard disk, RAM(1) |
| ![](.guides/img/samsung.jpg) | Touchscreen, network, GPS, accelerometer, camera, volume button, microphone | Screen, network, speaker | ARM | RAM, Flash Memory |
| ![](.guides/img/pi.jpg) | USB, network, custom pins that receive signals from sensors | Custom pins, network, video port, USB | ARM | RAM, SD-Card|
| ![](.guides/img/bread-machine.jpg) | Temperature sensors, clock/timer | Mixer motor control, temperature control, display panel, speaker/beeper | Custom  | RAM, ROM |

---
title: The CPU
files: []

---
CPU stands for **C**entral **P**rocessing **U**nit. You will probably have heard people talking about *processors*. The CPU *is* the processor.

Here are some example devices that have CPUs

- PCs
- Mobile Phones and iPads
- Modern washing machines and fridges
- Modern watches and clocks, not just digital ones

## What does a CPU look like?
Here are some images of CPUs ...

| CPU | Description |
|-|-|
|![intel-cpu](.guides/img/intel-cpu.jpg) | A typical Intel CPU|
|![motherboard](.guides/img/motherboard.jpg)| A CPU about to be inserted into a *motherboard*, the big circuit board where all the internal electronic components live.|
| ![motherboard](.guides/img/A8.jpg)| An Apple iPhone 6 chip squeezed onto its motherboard.|

## Videos
CPUs are often described as being the most complex single device of all human endeavour. If you're interested in seeing how a CPU is actually made, take a look at the videos below. 

## Manufacturing Silicon Wafers
![640x480](http://www.youtube.com/watch?v=AMgQ1-HdElM&feature=youtu.be)

## Making a chip out of the wafer
![640x480](http://www.youtube.com/watch?v=Cg-mvrG-K-E&feature=youtu.be)

---
title: CPU Specifications
files: []

---
You will probably heard people talking about the a CPU in these terms

| Intel Quad Core 2.0 GigaHertz Processor with 16Mb cache |
|-|
| ![intel-cpu](.guides/img/core2quad.jpg)

Let's see what this means. 


---
title: Clock speed
files: []

---
*Intel Quad Core **2.0Hz** Processor with 16Mb cache*

The clock speed is the *2.0 Gigahertz* (GHz) part. What this means is that the CPU ticks over 2 billion times (cycles) per second.

Instructions are closely linked to 1 clock cycle. Some instructions need just one cycle whereas others require several.

If you assume that on average, a CPU might need 3 cycles per instruction (the actual number varies from one CPU make to another) then our 2GHz processor is able to execute about 700 million instructions each second.
---
title: Cache
files: []

---
The cache is special memory that lives on the CPU rather than on a seperate computer chip.

The big advantage of this is that it is physically closer to the heart of the processor and is optimized for speedy access. Take a look at the image below to see an image of a real CPU and where the cache is located - right in the heart of the chip.

![intel-cpu](.guides/img/cache.jpg)

Being physically closer makes quite a difference given that computer signals  move near to the speed of light.
---
title: Cores
files: []

---
If your device has a **quad core** processor, it actually has 4 CPUs built into one physical chip. A dual core machine has 2 cores. The above image shows where the 4 cores are located.

The obvious advantage of multiple cores is that you have more available power to run your programs.

Running 4 programs on a single core means that each program will run about 4 times slower than if each one was running all on its own.

Your device's operating system is responsible for trying to divide running programs across all available cores. On almost all modern consumer devices, you have a lot of programs running simultaneously even if you are unaware of it, so having multiple cores is usually a good thing for performance.



---
title: "RAM & Hard Disk Space"
files: []

---
A typical PC might have the following specification

*4GB (Gigabytes) RAM and a 1TB (Terabyte) hard disk.*

1TB is equal to 1000GB. So, the above specification has about 250 times as much hard disk space as RAM. The reason for this is that RAM is a lot more expensive than disk storage space.

##Where is RAM located?
In PC's RAM comes as chips that can be slotted in and out of the motherboard. On other devices, it is soldered onto the motherboard.

![intel-cpu](.guides/img/RAM.jpg)
![intel-cpu](.guides/img/prim-storage.jpg)

##RAM is very fast indeed
In fact, the only thing faster than RAM is our CPU cache. In order for our PC to work really fast, it needs to be able to access data very quickly. This is why we use RAM.

##RAM data is lost when you power off
This is the big drawback of RAM (other than being expensive). All the data is lost when you power off. And that is what hard disks are for. When your application needs to save its data, it gets pushed to hard disk. 

In the case of web applications, the data is actually saved to hard disks on systems elsewhere on the internet and never touches your hard disk. Think of Facebook. All your data exists only on the Facebook server.

Smartphones and other small devices save their data to *Flash* memory. This is slower than RAM but keeps it data when there is no power.

##How your CPU works with RAM
Most computer systems load and run lots of programs in memory at the same time. Take a look at the illustration below, which shows what might be in memory at any given time.

[VISUALIZATION]

##Hard Disks
Hard disks can store a lot of data but they are very slow compared to RAM. When you run a program it is transferred from the hard disk into RAM. If the program needs data that is stored on your hard disk, then it is transferred into memory first.

![intel-cpu](.guides/img/RAM.jpg)

The software application (program) is responsible for making sure that data stored in RAM is saved properly to hard disk.

##Programs
Our simple Javascript program is loaded into your PC's memory and is then accessed in RAM by the CPU when it runs the program.



##Summary
So RAM/memory is used to store both programs and data. It is directly connected to the CPU so it can be accessed incredibly quickly, which matters a lot if you want your programs to run incredibly quickly.


---
title: Storage types
files: []

---
If you're interested, here is a summary of common storage types. Volatile indicates whether the data is lost when power is lost.

| Type         | Capacity | Cost | Speed | Volatile | Description |
| ------ | ----- | ---| ----- |
| [CPU Cache](http://en.wikipedia.org/wiki/CPU_cache) | 1 - 64MB | N/A | Many times speed of RAM | Yes | CPU Cache lives on the same chip as the CPU and is ecxeptionally fast. The CPU tries to load commonly accessed code and data into the cache to boost performance. |
| [RAM](http://en.wikipedia.org/wiki/Random-access_memory) | up to 4GB per chip | $$$ | Fastest | Yes | The most expensive form of memory but also the fastest. All devices have some. A washing machine needs very little, a multi-media PC can't have enough. |
| [ROM](http://en.wikipedia.org/wiki/Read-only_memory) | Usually MBs rather than GBs | $$ | Fast | No | Read Only Memory is used to store data that never changes. They are prepgrammed before being installed in a device. Usually contains programs that boot-up (start) a device.
| [Magnetic Hard Drive](http://en.wikipedia.org/wiki/Hard_disk_drive) | 50 GB to 1TB or more | $ | Slow | Yes | Used to store large amounts of data that persist without power. |
| [Solid State Drive](http://en.wikipedia.org/wiki/Solid-state_drive) | 50GB to 500GB | $$ | Quite fast | No | Like magnetic hard disks, but uses Flash memory chips (and sometimes RAM) rather than magnetic disks. Will replace hard disks as costs come down. |
| [Flash Memory](http://en.wikipedia.org/wiki/Flash_memory) | 256GB or more | $$ | Quite fast | No | Used in SD cards, USB sticks and Solid State Drives, smartphones etc. |

---
title: What does the CPU do?
files: []

---
##The CPU runs programs
The job of the CPU is to *run* or *execute* programs. That is really all a CPU ever does. It runs programs and usually lots of them at the same time.

So, let's take a look at a simple program that adds two numbers together.

##A really boring program
Below is a simple piece of Javascript code and that covers all aspects of Input, Output, Process and Store.

```javascript
getvalue(x);
getValue(y);
result = x + y;
display(result);
saveToFile(result);
```

In English, this is what it is doing.

1. Get a value and store it in RAM at a location referred to as `x`. Let's assume we are getting this from the user entering it on the keyboard.
1. Get another value and store it in RAM at another location referred to as `y`.
1. Add 'x' and 'y' together and and store the result in a third location, 'result'. 
1. Next, we display the result, let's assume we simply display it on screen.
1. Finally, we save the result to a file on our disk drive so we can retrieve it later.

Everything that happens here is controlled or managed by the CPU. When we get onto programming, and especially Machine Code programming, we'll understand this better.


---
title: The Operating System
files: []

---
##Common Operating Systems
You will probably have heard of many different operating systems. Well known ones are

- Windows
- OS X for Macs
- iOS
- Android

![OS](.guides/img/os.png)

##What it does
The Operating System is collection of programs that provides other applications access to the many different devices and components that live on a device, such as

- Memory
- Screen
- Hard Drives
- Network
- Mouse
- Printer
- Keyboard
- GPS
- Touchscreen
- etc.

Say you are writing a program that wants to save a file to your hard drive. Your code might do something like

*"here's an image I downloaded, now create a file called image.jpg and save it to my photo folder"*

You don't need to worry about how this is done, that's the job of the operating system.

##Some examples
Every device has an operating system, here are examples of just a few the components it manages and provdes access to.

| Device | OS Purpose |
| - | - |
| All Devices | RAM, hard-disks (for PCs), non-volatile storage |
| PC | Provide access memory, screen, hard drive, keyboard, mouse printer etc. |
| Smartphone | Touchscreen, volume button, make calls, internet access, power on and off |
| Car | Tyre pressure sensors, faulty lights, fuel consumption, speed |
| Washing Machine | Motor speed, motor direction, water temperatare, water flow control, display, time management |
| Printer | Display, printer head position, ink level monitoring, paper level, paper jam detection, scanner control |

In general, the simpler the device (fridge, for example) the simpler and smaller the OS. PC and Smartphone operating systems are very large and complex.





---
title: A history of networking
files: []

---
This is included to give an idea of the type of designer led ways we can enhance content.

![](.guides/img/history.png)
---
title: New Section 16
files: []

---
