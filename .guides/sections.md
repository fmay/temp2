---
title: What is a computer system?
files: []
layout: 2-panels-tree

---
Most of you understand what a computer system is already. You may be surprised at how many household devices are computer systems or contains computer systems. In a moment, we'll list some of them our for you, including Alarm Clocks, Washing Machines, Phones and Cameras.

##The 4 main components
Any computer system is made up of 4 main components.

| Type | Description | Examples |
|-|-|
| Input | This means informational data provided to the computer system. | Keyboard, touchscreen, smartphone accelerometer and gps, network, usb, microphone, temperature sensors |
| Output | This means information that is provided from the computer system to the outside world | Screens, speakers, network, usb ports, microphones |
| Store | Computer systems need to store data so it can be processed | RAM (Random Access Memory), ROM (Read Only Memory), Hard Drives, SD Cards, USB Sticks, Dropbox |
| Process | The CPU is the brain of the computer system and it is responsible for getting data from Inputs, sending data to Outputs and reading and writing data to and from the Store | Every computer system has a CPU processor. |




---
title: Example Devices
files: []

---
Here is a table of household devices and a few of the components they might have.

| Device | Processor | Input | Output | Store |
|-|-|-|-|
| PC | Intel or AMD | Keyboard, mouse, touchpad, microphone, USB, network | Screen, network, USB, speakers | Hard disk, RAM(1) |
| Smartphone | ARM | Touchscreen, network, GPS, accelerometer, volume button, microphone | Screen, network | RAM, Flash |
| Raspberry Pi | ARM | USB, network, custom pins that receive signals from sensors | Custom pins, network, video port, USB | SD card |
| Bread Machine | Custom | Temperature sensors, Clock | Mixing motor control, temperature control, display panel | RAM, ROM(2) |

---
title: The CPU
files: []

---
CPU stands for **C**entral **P**rocessing **U**nit. You will probably have heard people talking about *processors*. A CPU is the same as a processor.

Here are some example devices that have CPUs

- PCs
- Mobile Phones and iPads
- Modern washing machines and fridges
- Modern watches and clocks, not just digital ones

##What does a CPU look like?
Here are some images of CPUs ...

| CPU | Description |
|-|-|
|![intel-cpu](.guides/img/intel-cpu.jpg) | A typical Intel CPU|
|![motherboard](.guides/img/motherboard.jpg)| A CPU about to be inserted into a *motherboard*, the big circuit board where all the internal electronic components live.|
| ![motherboard](.guides/img/A8.jpg)| An Apple iPhone 6 chip squeezed onto its motherboard.|
---
title: CPU Specifications
files: []

---
You will probably heard people talking about the a CPU in these terms

*Intel Quad Core 2.6 GigaHertz Processor with 16Mb cache*

Let's see what this means. 

##Clock Speed
*Intel Quad Core 2.6GHx Processor with 16Mb cache*

The clock speed is the *2.6 Gigahertz* (GHz) part. What this means is that the CPU ticks over 2.6 billion times (cycles) per second.

Instructions are closely linked to 1 clock cycle. Some instructions need just one cycle whereas others require several.

If you assume that on average, a CPU might need 3 cycles per instruction (the actual number varies from one CPU make to another) then our 2.6GHz processor is able to execute nearly 1 billion instructions each second.

###How fast CPUs have got faster
[show graph showing how Hz has changed over time]

##Cache
The cache is special memory that lives on the CPU rather than on a seperate computer chip.

The big advantage of this is that it is physically closer to the heart of the processor and is optimized for speedy access.

Being physically closer makes quite a difference given that computer signals  move near to the speed of light.

##Cores
If your device has a *quad core* processor, it actually has 4 CPUs built into one physical chip. A *dual core* machine has 2 cores.

The obvious advantage of multiple cores is that you have more available power to run your programs.

Running 4 programs on a single core means that each program will run about 4 times slower than if each one was running all on its own.

Your device's operating system is responsible for trying to divide running programs across all available cores. On almost all modern consumer devices, you have a lot of programs running simultaneously even if you are unaware of it, so having multiple cores is usually a good thing for performance.



---
title: "RAM & Hard Disk Space"
files: []

---
A typical PC might have the following specification

*4GB (Gigabytes) RAM and a 1TB (Terabyte) hard disk.

1TB is equal to 1000GB. So, the above specification has about 250 times as much hard disk space as RAM. The reason for this is that RAM is a lot more expensive than disk storage space.

##RAM is very fast indeed
In fact, the only thing faster than RAM is our CPU cache. In order for our PC to work really fast, it needs to be able to access data very quickly. This is why we use RAM.

##RAM data is lost when you power off
This is the big drawback of RAM. All the data is lost when you power off. And that is what hard disks are for. When your application needs to save its data, it gets pushed to hard disk. 

In the case of web applications, the data is actually saved to hard disks on systems elsewhere on the internet and never touches your hard disk. Think of Facebook. All your data exists only on the Facebook server.

Smartphones and other small devices save their data to *Flash* memory. This is slower than RAM but keeps it data when there is no power.

##Hard Disks
Hard disks can store a lot of data but they are very slow compared to RAM. When you run a program it is transferred from the hard disk into RAM. If the program needs data that is stored on your hard disk, then it is transferred into memory first.

The software application (program) is responsible for making sure that data stored in RAM is saved properly to hard disk.

##Programs
Our simple Javascript program is loaded into your PC's memory and is then accessed in RAM by the CPU when it runs the program.

##Visualising Memory
Below is a diagram to help you visualise memory. You can see that lots of different programs and their associated data storage are stored in different parts of the device's memory.

[image showing several programs and their data in memory. Should show well known program names]

##Summary
So RAM/memory is used to store both programs and data. It is directly connected to the CPU so it can be accessed incredibly quickly, which matters a lot if you want your programs to run incredibly quickly.


---
title: New Section 6
files: []

---

---
title: New Section 7
files: []

---

---
title: New Section 8
files: []

---

---
title: New Section 9
files: []

---

---
title: New Section 10
files: []

---

---
title: New Section 11
files: []

---
