---
title: What is a computer system?
files: []
layout: 2-panels-tree

---
Most of you understand what a computer system is already. You may be surprised at how many household devices are computer systems or contains computer systems. In a moment, we'll list some of them our for you, including Alarm Clocks, Washing Machines, Phones and Cameras.


## The 4 main components of a computer System
Any computer system is made up of 4 main components

- **Input** : information and data from components or devices provided to the computer system
- **Output** : information provided by the computer system to other devices and components
- **Store** : Computer systems need to store data so it can be processed. This includes memory, disk drives and other forms of storage.
- **Processing** : This generally means the CPU (or processor), which is the brain of the computer system. It involves running programs as well as coordinating the flow of information between input devices, output devices and storage.

>The above 4 component system is known as the Von Neumann acrchitecture.

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

[add a few more example to the listthis list should contain lots of options as just images. The user would mouse over to get a pop-up info box]

| Device | Input | Output | Processor | Store |
|-|-|-|-|-|
| ![](.guides/img/mac.jpg)   | Keyboard, mouse, touchpad, microphone, USB, network | Screen, network, USB, speakers | Intel or AMD processors | Hard disk, RAM(1) |
| ![](.guides/img/samsung.jpg) | Touchscreen, network, GPS, accelerometer, camera, volume button, microphone | Screen, network, speaker | ARM | RAM, Flash Memory |
| ![](.guides/img/pi.jpg) | USB, network, custom pins that receive signals from sensors | Custom pins, network, video port, USB | ARM | RAM, SD-Card|
| ![](.guides/img/bread-machine.jpg) | Temperature sensors, clock/timer | Mixer motor control, temperature control, display panel, speaker/beeper | Custom  | RAM, ROM |

Other example computer systems include

- Air traffic control systems
- Pacemakers
- Hospital medical equipment
- Traffic management systems
- In flight avionics control systems

So you can see that as well as your beloved personal gadgets there are computer systems that are truly important to many aspects of modern society that we probably don't even think about.

---
title: Hardware reliability
files: []

---
Reliability is a big issue when designing computer systems. 

If hardware fails then it is realtively easy to imagine how the system as a whole can fail. 

| Failure | Effect | Solution |
|-|-|-|
| Computer power supply blows | Computer shuts down completely | *Redundant power supply* means the computer has 2 power supplies built in so if one fails, the other still operates while the broken one is replaced |
| Server Disk drive crashes | All data on that drive is lost | File servers have several disks with data spread across them so if one fails, the others contain the same data allowing the faulty one to be replaced after which the data is restored. This is known as a RAID disk array |
| Aircraft avionics system failure | Plane could crash | Modern planes have *triple redundant systems* meaning there are 3 entirely separate control systems located in different physical locations to reduce likelihood of all 3 failing |

---
title: Software reliability
files: []

---
If software fails then the effect can vary. 

| System Type | Seriousness | Description |
|-|-|-|
| IMG Pacemaker | Faintness or even death | If the software would fail, then either pacemaker would stop completely or it could send out pulses to stimulate the heart and an irregular or even  very fast rate, neither of which are comfortable |
| IMG Traffic | Traffic jams or even death | Traffic lights fail to operate correctly resulting in chaos or accidents. |
| IMG Gaming | Annoying | You are about to achieve your high score when the game crashes or freezes. Your life is temporarily ruined. |
| IMG Word processor | Lost work | You have been editing a document for 2 hours without saving then it crashes. You have lost 2 hours of work. Other than testing, adding an auto-save feature can prevent this, which modern word-processors all have. |

## Testing
Software engineers spend a lot of time writing code with reliability in mind. The table below shows the various ways software development teams look to enhance reliability through testing.

| Method | Description |
|-|-|
| Unit Tests | All good developers incorporate unit tests into their development process. A unit test is code that simulates all possible or known scenarios for a discreet bit of functionality. A software program can have hundreds or thousands of these even. The developer then runs alls the tests to ensure that all test pass successfully. Any failures are higlighted. |
| User Tests | Software teams include *Quality Assurance* staff, whose job it is to follow *test plans* that tell teh QA person what to do. They can then check that everything looks right and behaves right, which unit tests often cannot do. |
| Emulations | If you are testing an in-flight control system, testing at 30'000 feet is not a great idea as any failures can result in death. An emulation allows the developers to emulate a real in-flight situation from the comfort of their desks. Only then does the software get tested in flight. |


---
title: Standards
files: []

---
Nowadays, when you buy a keyboard or a mouse, you can be pretty sure that when you plug it in to a PC or Mac, it is going to work.

Not so long ago, however, you had to know exactly what you were buying and whether it was compatible with your computer. This was annoying for both buyers and sellers of computer equipment.

The same thing applies to computer software. Document standards such as PDF, audio standards such as MP3, video standards such as MP4 are all crucial in ensuring that information can be exchanged between systems.

In the next sections, we'll look at some examples of hardware and software standards.


---
title: Hardware standards
files: []

---
The following table shows some well known hardware standards.

| Standard | Description |
|-|-|
| USB [image] | Allows you to connect things like printers, keyboards, mice, cameras, microphones and many other peripheral devices. |
| Bluetooth | Wirelessly connect smartphones, mice, keyboards and other devices |
| RAID | Connect two or more hard disks together so that if one disk drive fails, the other drive(s) have the same data spread across them so if one fails, you don't lose data |
| DDR SDRAM | This is a standard for RAM memory chips that allows different chip manufacturers to built RAM chips that will work in different computers. If this standard did not exists, then you could only buy RAM from one manufacturer. |
| HDMI | You will probably have a couple of HDMI cables in your house. You connect your gaming console and your satellite or cable console to your TV. TV manufacturers all make use of the HDMI standard to ensure that their TVs will work with other devices happily. |




---
title: Software standards
files: []

---
The following table lists some well-known software standards.

| Standard | Description |
|-|-|
| IMG PDF | Allows any document (text, spreadsheet, image, web-page etc.) to be distributed to anyone with a PDF reader. All modern computers, tablets and iPhones have PDF readers preinstalled. |
| IMG ASCII | This is an old standard that specified how computer characters are represented internally For example, A=65, B=66, 1=49, 2=50. The word 'CAT' is stored in a computer as the number sequence 67, 65, 84. This is how data messages can be reliably sent between systems of any type and reliably understood. |
| IMG MP3 | This is well known standard for compressing and storing digital audio. |
| IMG MP4 | A common standard for compressing and storing video |


---
title: "Ethics & Environment 1"
files: []

---
How many computers and mobile phones have you had while growing up? What about other items of technology, what do you do with them once you’ve replace them with something newer, faster or better?

What do you do with old, unwanted or broken electrical items? Do you throw them away? Recycle them? Have you ever wondered what happens to electrical items once recycled?

In this video we will be speaking about environmental and ethical considerations that need to be in place with the technology that we use.

## Environmental Considerations
Waste Electrical and Electronic Equipment (WEEE) regulations have been setup by the European Union since 2007 to encourage consumers to recycle unwanted electrical items, known as ‘eWaste’. The Environment Agency encourages all manufactures to mark all new products placed on the market with a logo.

According to the Environment Agency, the UK throws away 2 million tonnes of WEEE each year and there is a growing concern to the amount of waste we are throwing away. 

So what can we do with all this eWaste?

## Recycling
The EU has put together the WEEE regulations to make sure less eWaste goes to landfi ll and instead the valuable materials found inside everyday electrical items thrown away are instead recycled.

Did you know that there is steel found in electrical toasters and Nickel in old kettles. For example the Zinc found in old mobile phones could be reused in ship building and the Gold and Platinum found in a computer or consoles could be melted down to make jewellery.

Do you know where your local WEEE recycle point is? You can use [this website](http://www.recyclenow.com/why_recycling_matters/electricals/index.html) to find out where your local centre is.

## Ethical considerations of recycling eWaste
Instead of recycling we could donate working electrical items to charity or to developing countries to reuse. 

However, according to Greenpeace, many old products that are being exported to developing countries might have some short term benefits, but in the long term these items are being dumped and are
contributing to the countries waste management problems.

Globally we have a real problem that is emerging. For example, it costs $30 for a computer to be recycled in the United States and $2 to recycle the same computer in China. Therefore western companies prefer to ship these items to be disposed to China, India and Pakistan.

It is legal for countries to export items to developing countries for reuse or refurbishment, but according to Interpol and the Guardian, many items sent are incorrectly classifi ed to avoid recycling costs and are actually waste items which are lost on the black market to avoid the legitimate costs of recycling.


---
title: "Ethics & Environment 2"
files: []

---
Ever wondered what the actual electricity cost is for keeping electrical items at home on standby instead of switching them off? According to “The Energy Saving Trust” an average home spends between £45 to £80 a year in electrical costs for keeping items on standby.

You might not think that’s a lot of money over a year, but think how much wasted electricity that is, now multiply that by each household on your street, in your town and across the country! That’s a lot of wasted electricity.

Different items have different energy effi ciency ratings, and we are encouraged to consider an energy efficient item when purchasing it.

Did you know that a laptop can use up to 85% less electricity when compared to a desktop PC? Older laptops would become incredibly hot when used for long periods, if you compare this with some newer laptops they have more efficient parts inside them to prevent the laptops from heating up, they also use less electricity and there is therefore less waste.

The fan attached to a PC, on a computer, is always on while the computer is on. The purpose of the fan is to make sure the computer’s CPU remains at a constantly low temperature.

Now if we think about how things are maintained on a larger scale in Data Centres their level of wasted electricity increases in order to keep all those computers and components cooled down, air conditioning units are powered 24/7 to constantly make sure that the servers are at a constant temperature. According to 4d-dc offering an environmentally friendly data centre alternative:

“5% of Europe’s annual energy bill is spent just on cooling computers. In legacy data centres (usually those computers older than 5 years), this can often account for nearly 40% of the power consumed.”

This alternative method offered if adopted by a data centre could decrease their energy usage by 88.9% which just goes to show how much energy is wasted in cooling these systems.

## Computing Ethics for Professionals
Medics and Lawyers can only practice in their field if they belong to a self-regulating professional organisation. The Computing profession is still relatively new; there has not been the organisational capability to develop a binding set of moral rules.

The British Computing Society has published a ‘Code of Conduct’ they expect their members to follow. These outline a duty to be followed by professionals and outline expected moral behaviour. Although these are not legislated in law, members can be expelled from the society if they do not adhere to the code of conduct.

The code of conduct covers four important areas:

- Obligation to public interest
- Professional competence and integrity
- Duty to relevant authority
- Duty to the profession

By adopting a professional code an organisation benefi ts from gaining in public trust. The profession uses the code of conduct to self-regulate the behaviours of its members. The code of conduct instils ethically values, which is acceptable behaviour.

Ethical codes of practice are needed as computer professionals have access to a lot of sensitive information that could be misused. A computer professional will have access to a company’s data, as well as fi nancial and medical records, the code of ethics sets clear guidelines of what is expected from individuals working under the trust of their employers.


---
title: Legal - Data Protection Act
files: []

---
The law has an important role to play when it comes to computer systems and espeically software applications such as social media. 

There are some specific acts in law that relate to computer systems

- The Data Protection Act 1998
- The Computer Misuse Act 1998
- Copyright, Design and Patents Act 1998

## The Data Protection Act 1998
This governs the way in which companies have to look after data they hold about us. The following organizations all hold data about us, such as

- Doctors
- Banks
- Web shops 
- Social media sites
- Web applications where you sign up and supply private information

If a company wishes to hold data about us, they must first register with the Information Commissioner's Office (ICO). There are 8 princpiles that they must adhere to

- Data must be processed fairly
- It can only be used for the purposes they have stated
- They should only hold data they actually need
- Data must be accurate and up to date
- Data must not be held longer than it is needed for
- Data will be used in accordance with your rights
- Data will be kept safe
- Data will not be transferred to any country where they do not have similar laws

In most cases, if data is held about you, you have the rght to seei it and if it is incorrect, you can insist it is changed.




---
title: Legal - Computer Misuse Act
files: []

---
In 2011, hackers managed to break into Sony's computer systems and steal information about individuals held on their Playstation network.

Sony were heavily criticised and the ICO decided that Sony had failed to keep its systems security up to date with general technical security developments.

This was in breach of the principle that data data should be kept safe. As a result, the ICO fined Sony £250,000.

## Computer Misuse Act
Of course, hacking into a computer system is in itself illegal. This is covered by the Computer Misuse Act, which focuses on unauthorised access to computer systems. 

The Act covers three crimes

- Attempting to access a computer system to access information that you know you are not authorised to access. Note the use of the word *attempt*, as you do not have to be successful to be in breach of the law. Attempting to guess someone's password is in breach of the Computer Misuse Act, even if your guesses were wrong.
- Attemping to access computer system with the intention of committing a further crime. This could be trying to access personal data with the intention of committing identity theft.
- Unauthorised access a computer system with the intention of changing data held on it or to impair the running of the computer system. This offense can lead to a jail sentence of up to 10 years in the UK.






---
title: "Legal - Copyright, Design & Patents Act"
files: []

---
## Copyright, Design and Patents Act 1998
This acts prevents work from being copied without permission. This would typically cover

- Text
- Images
- Video 
- Music
- Software

If someone else takes a photograph and publishes it, it is against the law for someone to copy it. 

People have been breaking copyright law long before the Internet but the Internet has made it much easier to do so.

File sharing websites and peer-to-peer networks have meant that large amounts of copyright material are being shared online, much to the concern of the film and music industry.

There are, however, many more laws about computer and Internet use. As uses of the Internet develo, the law is having to be applied in new ways. 

For example, there have been cases of people being sued for lible for posts they have made on Twitter. 

You also need to keep in mind that use of the Internet spans the world and what may be legal in the UK may not be legal in other countries. 

- Some countries have very strict rules about the sort of material that people are allowed to access.
- Some countries have strong rules on the use of encryption

This has become an increasingly complex area and people have to become aware of their online actions. 


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