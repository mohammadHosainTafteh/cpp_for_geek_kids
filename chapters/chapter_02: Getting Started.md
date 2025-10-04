# chapter 02: Getting Started

## 2.1 Define Your First Project

### 2.1.1 What is a “Hello, Geek!” program?

A “Hello, Geek!” program is your very first step into the world of coding. It’s a simple C++ program that prints a message to the screen — usually something like `Hello, Geek!` — and helps you understand how code turns into action. This tiny project teaches you how to:

* Write a basic C++ program

* Save and compile your code

* Run your program and see the output

Even though it’s small, this program introduces key ideas: structure, syntax, and the power of the compiler. It’s also a great way to test your setup and make sure everything — from your operating system to your editor and compiler — is working correctly.

Think of it as your geeky handshake with the computer. You write the code, the computer responds, and the adventure begins.

### 2.1.2 Why Start with a Simple Project?

Starting with a simple project like "Hello, Geek!" is the perfect way to begin your coding journey. It’s small, quick, and gives you a full tour of the tools you’ll be using throughout Chapter 1. You’ll write code, compile it, run it, and see the result — all in one sitting.

Here’s why it works:

* It helps you focus on learning the tools: Ubuntu, VS Code, g++, and GitHub.

* It builds confidence by showing you that you can write and run real code.

* It introduces the basic workflow: write → save → compile → run.

* It sets the stage for deeper learning in later sections.

By starting simple, you avoid getting overwhelmed. You’ll understand how each part of your setup works and how they connect. Once you’ve completed this project, you’ll be ready to explore the rest of Chapter 1 — installing build tools, setting up VS Code, writing in different editors, and even using AI to generate your own programs.

### 2.1.3 How to Search and Identify What Tools You Need to Solve It

Before you start building your first project, you need to know what tools are required — and how to find them. This section helps you think like a geeky problem-solver and researcher.

Let’s say your goal is to write and run a simple C++ program. What tools do you need?

* **Operating System** — Ubuntu is recommended for its simplicity and power.

* **Text Editor** — nano, gedit, or VS Code.

* **Compiler** — g++ is the standard C++ compiler.

* **Terminal** — to run commands and compile code.

* **Version Control** — Git and GitHub help you save and share your work.

You don’t need to memorize these tools — you just need to learn how to search for them. Try asking questions like:

* "How do I install g++ on Ubuntu?"

* "What’s the best C++ editor for beginners?"

* "How do I run C++ code in VS Code?"

* "What is GitHub and how do I use it?"

Learning to search is a superpower. It helps you find answers, discover new tools, and solve problems on your own. In the rest of Chapter 1, you’ll install each tool step-by-step, write your first program, and even use AI to generate code. But first, get comfortable with asking questions and exploring answers — that’s how real geeks learn.

## 2.2 Choosing Your Operating System

### 2.2.1 Comparing Popular OS Options (Windows, macOS, Linux)

Before choosing your operating system, it helps to understand the strengths and limitations of each one. This section gives you a quick overview so you can make an informed decision based on your goals as a geek kid.

* **Windows** — The most widely used OS for gaming, school, and general tasks. It’s user-friendly and supports many applications, but it’s not ideal for learning low-level programming or using open-source tools. You’ll need extra setup to run Linux-style commands and compilers.

* **macOS** — Great for creative work like design and media. It has a Unix-based terminal, which is helpful for coding, but some tools (like g++) may require extra configuration. macOS devices are also expensive and less customizable.

* **Linux (Ubuntu)** — The best choice for geek kids who want to learn how computers really work. Ubuntu is free, open-source, and gives you full control over your system. It’s perfect for learning C++, using the terminal, and exploring how software is built from the ground up.

In this book, we’ll use **Ubuntu** because it’s powerful, beginner-friendly, and teaches you real-world skills. You’ll learn how to install it, navigate the terminal, and use it to build your first projects — just like a real developer.

### 2.2.2 Why Ubuntu Is Great for Geek Kids and Creators

Ubuntu isn’t just a good operating system — it’s a geek’s paradise. It gives you full control, teaches you how computers really work, and opens the door to everything from creative coding to industrial automation. If you want to build robots, program microcontrollers, or explore the world of IoT, Ubuntu is your launchpad.

Here’s why Ubuntu is the ultimate choice:

* **Total Freedom** — Ubuntu is open-source, which means you can inspect, modify, and rebuild every part of it. You’re not just using a system — you’re mastering it.

* **Terminal Mastery** — The command line in Ubuntu is like a magic wand. You’ll learn to install packages, automate tasks, and control your environment with precision.

* **Perfect for C++ and Embedded Systems** — Ubuntu is the go-to OS for developers working with Arduino, Raspberry Pi, STM32, and other embedded boards. It supports cross-compilation, serial communication, and hardware debugging out of the box.

* **Industrial-Grade Reliability** — Ubuntu powers everything from factory robots to space probes. It’s used in automotive systems, smart cities, and industrial IoT — and now, you’ll use it too.

* **Developer Ecosystem** — Ubuntu supports g++, CMake, VS Code, Git, and GitHub natively. You’ll be working with the same tools used by professional engineers and open-source contributors.

* **Security and Stability** — With regular updates and a massive community, Ubuntu is one of the most secure and stable platforms available. You’ll learn how to manage users, permissions, and system resources like a pro.

* **Customization Heaven** — From your desktop layout to your keyboard shortcuts, Ubuntu lets you tweak everything. You’ll learn how to build a system that fits your workflow perfectly.

* **Community Power** — Ubuntu has one of the largest and most helpful communities in tech. Forums, wikis, and tutorials are everywhere — and they’re written by geeks, for geeks.

* **Built for Makers and Innovators** — Whether you're building a smart greenhouse, a wearable device, or a robot dog, Ubuntu gives you the tools to connect sensors, control motors, and manage data streams.

* **Educational Superpower** — Ubuntu teaches you how operating systems work, how software is compiled, and how hardware interacts with code. It’s like having a lab in your laptop.

* **Global Standard in Engineering** — Ubuntu is used by NASA, Tesla, CERN, and thousands of tech companies. Learning it now means you’re stepping into the same ecosystem as the world’s top engineers.

* **Most Popular Server OS in the World** — Linux powers the majority of web servers, cloud platforms, and enterprise infrastructure. If you ever work in DevOps, backend development, or cloud engineering, you’ll be working with Linux every day — configuring servers, deploying containers, and managing systems at scale.

In this book, Ubuntu is your foundation. You’ll use it to write code, compile programs, explore the terminal, and connect to real hardware. Whether you’re blinking LEDs or building a smart sensor network, Ubuntu gives you the tools to do it all — with style, speed, and full control.

### 2.2.3 How to Install Ubuntu (Dual Boot, USB Live, Virtual Machine, Embedded Boards, and More)

Ubuntu is incredibly flexible — you can install it almost anywhere. Whether you're using a Windows laptop, a MacBook, a Raspberry Pi, or even a cloud-based terminal, there’s a Linux environment waiting for you.

#### Option 1: USB Live Boot

This is a suggested option for beginners who want to explore Ubuntu safely. USB Live Boot lets you run Ubuntu directly from a USB stick without installing it or changing your hard drive. It's perfect for testing, learning, and experimenting with Linux tools like VS Code and nano in a temporary environment.

##### USB Live Boot: Step-by-Step Guide for Beginners

Want to try Ubuntu without installing it? Boot it from a USB stick! This method is safe, fast, and perfect for beginners who want to explore Ubuntu without changing their computer.

**Yes, you can install applications like VS Code, nano, and other CLI packages — but only if you choose the "Try Ubuntu" option and have internet access.**

##### What You Need

* A USB stick (at least 8 GB)

* Ubuntu ISO file (download from [ubuntu.com](https://ubuntu.com/))

* A tool to create the bootable USB (Rufus for Windows, BalenaEtcher for macOS/Linux)

##### Step-by-Step Instructions

* **Download Ubuntu ISO**

  * Go to [ubuntu.com/download](https://ubuntu.com/download)

  * Choose the latest LTS version for stability

* **Create a Bootable USB**

  * Open Rufus or BalenaEtcher

  * Select the Ubuntu ISO and your USB drive

  * Click "Start" to write the ISO to the USB

* **Restart Your Computer and Enter Boot Menu**

  * Plug in the USB

  * Restart your computer

  * Press the boot key (usually F12, Esc, or Del)

  * Select your USB drive to boot

* **Choose "Try Ubuntu"**

  * When Ubuntu loads, select "Try Ubuntu" instead of installing it

  * This runs Ubuntu directly from the USB — no changes to your hard drive

* **Explore Ubuntu Safely**

  * You’ll see the Ubuntu desktop and can use the terminal, browser, and file manager

  * You can install apps like:

    * `nano` → `sudo apt install nano`

    * `g++` → `sudo apt install g++`

    * `VS Code` → Download from [code.visualstudio.com](https://code.visualstudio.com/) or use `snap install code --classic`

* **Persistence (Optional)**

  * If you want Ubuntu to remember your changes (installed apps, saved files), create a **persistent USB**

  * Rufus and other tools offer this option during setup

##### What You Can Learn

* How Ubuntu works without installing it

* How to use the terminal and install packages

* How to write and run C++ code

* How to explore VS Code and other tools

##### When You’re Done

* Shut down Ubuntu

* Remove the USB

* Your computer will boot back into Windows/macOS like nothing happened

This is the safest way to explore Ubuntu. You can install apps, write code, and learn Linux — all without touching your hard drive.


This setup lets you choose between Ubuntu and your existing OS every time you start your computer. It’s perfect for geek kids who want a dedicated Ubuntu system for coding, while keeping Windows or macOS for school or family use.

* Use tools like Rufus or BalenaEtcher to create a bootable USB.

* Shrink your existing partition and install Ubuntu alongside your current OS.

* Choose Ubuntu from the boot menu when you want to enter geek mode.

~~//TODO~~

#### Option 2: USB Live Boot

Want to try Ubuntu without installing it? Boot it from a USB stick!

* Create a live USB and boot into Ubuntu without touching your hard drive.

* Great for testing, learning, or using on borrowed computers.

* You can even make it persistent so it remembers your changes.

~~//TODO~~

#### Option 3: Virtual Machine (VM)

Run Ubuntu inside Windows or macOS using software like VirtualBox or VMware.

* Ideal for beginners who want to experiment safely.

* You can pause, snapshot, and restore your Ubuntu environment anytime.

* Perfect for learning terminal commands and compiling code.

~~//TODO~~

#### Option 4: Windows Subsystem for Linux (WSL)

If you're using Windows 11, you can install Ubuntu directly inside Windows — no dual boot or VM required.

* Use the Microsoft Store to install Ubuntu via WSL.

* Run Linux commands and compile C++ code from your Windows terminal.

* Great for lightweight development and learning Unix tools.

~~//TODO~~

#### Option 5: Embedded Boards and IoT Devices

Ubuntu isn’t just for laptops — it runs on tiny computers too!

* Raspberry Pi, Jetson Nano, and STM32 boards can run Ubuntu or Ubuntu Core.

* Perfect for robotics, sensors, and smart devices.

* You’ll learn how to flash Ubuntu images, connect to serial terminals, and deploy real code to real hardware.

~~//TODO~~

#### Option 6: Cloud-Based Linux Environments

You can also access Ubuntu through cloud platforms like GitHub Codespaces, Replit, or online Linux terminals.

* No installation needed — just open your browser and start coding.

* Great for quick experiments, remote learning, or collaborative projects.

~~//TODO~~

#### Geek Tip: Keep a Pure Ubuntu System

If you’re serious about learning Linux, consider setting up a dedicated Ubuntu machine. It could be an old laptop, a second partition, or even a Raspberry Pi. This gives you a clean, distraction-free environment to explore, experiment, and build — separate from your school or work system.

Linux is everywhere — from your desktop to your robot, from your terminal to the cloud. It runs natively inside Windows 11, powers embedded boards, and dominates the server world. Once you learn how to install it, you’ll start seeing Linux all around you. And that’s when the real geek journey begins.Boards, and More)

### 1.2.4 Getting familiar with the terminal and file system

For many Windows and macOS users, the terminal can feel intimidating at first. It’s just a black screen with blinking text — no icons, no buttons, no safety nets. But here’s the secret: the terminal is where real geeks thrive. It’s fast, powerful, and gives you direct control over your computer. Once you learn how to use it, you’ll never want to go back.

The terminal lets you talk to your computer using text commands. You can navigate folders, create files, install software, and even compile your C++ programs — all from the keyboard. It’s like having superpowers that most users never unlock.

The file system is how your computer organizes everything: folders, files, programs, and settings. In Linux (Ubuntu), the file system starts at the root / and branches out into directories like /home, /etc, and /usr. You’ll learn how to move through this structure using terminal commands.

Here’s a list of essential terminal commands every geek kid should know:

#### Navigation

* `pwd` — Show your current directory

* `ls` — List files and folders

* `cd foldername` — Change directory

* `cd ..` — Go up one level

* `cd /` — Go to the root directory

* `cd ~` — Go to your home directory

#### File and Folder Management

* `mkdir foldername` — Create a new folder

* `touch filename.txt` — Create an empty file

* `cp source.txt destination.txt` — Copy a file

* `mv oldname.txt newname.txt` — Rename or move a file

* `rm filename.txt` — Delete a file

* `rm -r foldername` — Delete a folder and its contents

* `tree` — Show folder structure (install with `sudo apt install tree`)

#### Viewing and Editing Files

* `cat filename.txt` — View file contents

* `less filename.txt` — Scroll through file contents

* `nano filename.txt` — Edit a file in the terminal

* `gedit filename.txt` — Edit a file with a graphical editor

#### System Info and Permissions

* `whoami` — Show your username

* `id` — Show user and group info

* `chmod +x filename.sh` — Make a file executable

* `sudo command` — Run a command as superuser

* `top` — View running processes

* `htop` — Advanced process viewer (install with sudo apt install htop)

* `df -h` — Show disk usage

* `free -h` — Show memory usage

* `uname -a` — Show system info

* `uptime` — Show how long the system has been running

* `hostname` — Show system hostname

#### Package Management (Ubuntu)

* `sudo apt update` — Refresh package list

* `sudo apt upgrade` — Install updates

* `sudo apt install packagename` — Install a package

* `sudo apt remove packagename` — Remove a package

* `sudo apt purge packagename` — completely removes a package from your system along with its configuration files

* `apt list --installed` — List installed packages

* `dpkg -l` — Another way to list packages

#### Search and Help

* `man command` — View manual for a command

* `command --help` — Show help options

* `grep keyword filename.txt` — Search for text inside files

* `find . -name "filename"` — Search for files by name

* `which command` — Show the path of a command

* `locate filename` — Quickly find files (install with `sudo apt install mlocate`)

* `history` — Show command history

* `history -c` — clear command history

#### Useful Shortcuts

* **Tab** — Auto-complete file and folder names

* **Ctrl+C** — Cancel a running command

* **Ctrl+L** — Clear the terminal screen

* **Up Arrow** — Repeat previous command

* **Ctrl+Shift+T** — Open a new terminal tab

* **Ctrl+D** — Log out or close terminal

Once you master these commands, you’ll be able to navigate, manage, and troubleshoot your system like a real geek. These tools are used everywhere — in Ubuntu, in embedded boards, inside Windows 11 (WSL), and in cloud terminals. The terminal is your universal passport to Linux-powered environments.

In the next sections, you’ll use these commands to install build tools, compile C++ code, and manage your projects. So take your time here — this is where your geek powers begin.




































Option 2: Dual Boot with Windows or macOS

This setup lets you choose between Ubuntu and your existing OS every time you start your computer. It’s perfect for geek kids who want a dedicated Ubuntu system for coding, while keeping Windows or macOS for school or family use.

🛡️ Dual Boot Ubuntu: Step-by-Step Guide for Beginners

Dual booting means installing Ubuntu alongside your current operating system (like Windows or macOS), so you can choose which one to use each time you start your computer. It’s powerful — but risky if done carelessly. Follow these steps exactly, and always back up your data first.

🔍 Step 1: Understand What Dual Booting Does

Your hard drive will be split into two sections (called partitions).

One partition keeps your current OS (Windows/macOS), the other holds Ubuntu.

At startup, you’ll choose which OS to boot using a menu called GRUB.

⚠️ WARNING: If you accidentally delete or overwrite your current OS partition, you could lose all your files. That’s why the next step is critical.

💾 Step 2: Back Up Everything

Save important files to an external hard drive or cloud storage (Google Drive, Dropbox, etc.).

Don’t skip this — even pros make mistakes.

📥 Step 3: Download Ubuntu

Go to ubuntu.com and download the latest Ubuntu Desktop ISO file.

Choose the LTS (Long Term Support) version for stability.

🔧 Step 4: Create a Bootable USB

Use Rufus (Windows) or BalenaEtcher (macOS/Linux) to write the ISO to a USB stick.

Plug in your USB and launch the tool.

Select the Ubuntu ISO and your USB drive, then click “Start.”

🧹 Step 5: Shrink Your Existing Partition

On Windows: Open Disk Management → Right-click your main drive → “Shrink Volume.”

On macOS: Use Disk Utility → Select your drive → Partition → Add a new partition.

Leave at least 20 GB free for Ubuntu.

⚠️ WARNING: Do not delete any partitions. Only shrink.

🚀 Step 6: Boot from USB

Restart your computer and enter the boot menu:

Windows: Usually F12, Esc, or Del

macOS: Hold Option key

Select your USB drive to boot into Ubuntu.

🧙 Step 7: Start Ubuntu Installation

Click “Install Ubuntu.”

Choose “Install Ubuntu alongside Windows/macOS” — this is the safest option.

If you don’t see this option, STOP and ask for help. Manual partitioning is risky.

🧭 Step 8: Follow the Installer Carefully

Select your language, keyboard layout, and time zone.

When asked about partitions, double-check that your existing OS is not being erased.

Confirm that Ubuntu is being installed in the new space you created.

🔄 Step 9: Finish Installation and Reboot

Let Ubuntu install (takes 10–30 minutes).

When done, remove the USB and restart your computer.

🧭 Step 10: Choose Your OS at Startup

You’ll see a menu called GRUB.

Use arrow keys to select Ubuntu or Windows/macOS.

Press Enter to boot.

✅ You’re Done!

You now have a dual-boot system. Ubuntu is ready for coding, and your original OS is still intact.



Option 3: Virtual Machine (VM)

This is a beginner-friendly way to run Ubuntu inside your current operating system without changing anything on your hard drive. You’ll use a virtual machine app like VirtualBox or VMware to create a "computer inside your computer" — perfect for safe experimentation.

🧰 What You Need

A computer running Windows or macOS

At least 8 GB RAM and 20 GB free disk space

Ubuntu ISO file (download from ubuntu.com)

VirtualBox (free) or VMware Workstation Player (free for personal use)

🪄 Step-by-Step Guide

Download and Install VirtualBox

Go to virtualbox.org and download the installer for your OS

Install it like any other app

Download Ubuntu ISO

Visit ubuntu.com/download

Choose the latest LTS version for stability

Create a New Virtual Machine

Open VirtualBox → Click "New"

Name it "Ubuntu VM" and select "Linux" as the type, "Ubuntu (64-bit)" as the version

Allocate memory (at least 4096 MB recommended)

Create a virtual hard disk (20 GB or more)

Attach the Ubuntu ISO

Go to Settings → Storage → Click the empty disk icon → Choose the Ubuntu ISO file

Start the VM and Install Ubuntu

Click "Start" to boot the VM

Follow the Ubuntu installer steps (language, keyboard, time zone, etc.)

Choose "Erase disk and install Ubuntu" — this only affects the virtual disk, not your real computer

Finish Installation and Reboot

Let Ubuntu install (takes 10–30 minutes)

Reboot the VM when prompted

Explore Ubuntu Safely

You now have a full Ubuntu desktop inside a window

You can install apps like nano, g++, and VS Code

Try writing and compiling C++ code, using the terminal, and exploring Linux commands

🧠 What You Can Learn

How Ubuntu works without installing it on your real computer

How to use the terminal and install packages

How to write and run C++ code

How to experiment with Linux safely

🧼 When You’re Done

Close the VM window to pause Ubuntu

You can resume anytime, or take snapshots to save your progress

This is one of the safest and most flexible ways to learn Ubuntu. You get all the power of Linux, with none of the risk.

Option 4: Windows Subsystem for Linux (WSL)

This is a suggested option for beginners who use Windows 10 or 11 and want to try Ubuntu without installing anything or using a virtual machine. WSL lets you run Ubuntu inside your Windows system — like a built-in Linux terminal.

🧰 What You Need

A computer running Windows 10 or 11

Internet connection

Administrator access to install features

🪄 Step-by-Step Guide

Enable WSL Feature

Open PowerShell as Administrator

Run: wsl --install

This installs WSL and sets up Ubuntu automatically (on Windows 11)

On Windows 10, you may need to run:

dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart
dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart
wsl --set-default-version 2

Install Ubuntu from Microsoft Store

Open Microsoft Store

Search for "Ubuntu"

Click "Get" to install your preferred version (e.g., Ubuntu 22.04 LTS)

Launch Ubuntu

After installation, open Ubuntu from the Start Menu

The first time, it will set up your Linux environment

Create a username and password when prompted

Start Using Ubuntu

You now have a full Linux terminal inside Windows

Try commands like:

ls → list files

sudo apt update → refresh package list

sudo apt install nano g++ → install tools for C++ development

Install VS Code (Optional)

Download VS Code from code.visualstudio.com

Install the "Remote - WSL" extension to edit Linux files directly from VS Code

🧠 What You Can Learn

How to use Linux commands and tools

How to compile and run C++ code in a real Linux environment

How to integrate Linux with Windows workflows

✅ Why Beginners Love WSL

No need to dual boot or use a USB

Safe and easy to install

Great for learning Linux and C++ side-by-side with Windows

This is one of the easiest ways to start using Ubuntu if you're already on Windows. You get the power of Linux with the comfort of your existing system.



Option 5: Embedded Boards and IoT Devices

This is a suggested option for beginners who want to learn Linux using embedded boards like Raspberry Pi. I absolutely love Raspberry Pi — it's one of the most exciting tools for geek kids and creators. These tiny computers are perfect for hands-on learning, robotics, and real-world coding.

Having a Raspberry Pi opens up endless possibilities:

Learn Python by writing real code that controls hardware

Build IoT projects like smart sensors, weather stations, or home automation

Explore robotics by connecting motors, cameras, and sensors

Experiment with AI using tools like TensorFlow Lite and OpenCV

Create your own Linux-powered gadgets and servers

Practice networking, security, and system administration

Build a personal cyberdesk with custom dashboards and automation

Explore industrial applications like factory monitoring and smart agriculture

Set up Raspberry Pi clusters for parallel computing and distributed tasks

Control GPIO pins to blink LEDs, read sensors, and trigger relays

Manage microcontrollers and interface with Arduino, STM32, and ESP32

Configure routers, firewalls, and network bridges for home labs

Learn ethical hacking, penetration testing, and cybersecurity basics

Create magical IT setups with voice control, gesture sensors, and automation

Build retro gaming consoles, emulators, and arcade machines

Host multiplayer servers or LAN parties with Raspberry Pi as the hub

It’s like having a mini lab in your backpack — affordable, powerful, and endlessly customizable.

🧰 What You Need

A Raspberry Pi board (Model 4 or newer recommended)

microSD card (16 GB or more)

Power supply and HDMI cable

Keyboard, mouse, and monitor (or remote access via SSH)

Internet connection

🪄 Step-by-Step Guide

Choose Your Operating System

You can use Raspberry Pi OS (formerly Raspbian) — it's lightweight and beginner-friendly.

Or install Ubuntu Server or Ubuntu Desktop for Raspberry Pi — better for learning real Linux workflows.

Recommendation: Start with Raspberry Pi OS to learn basics, then switch to Ubuntu when you're ready to explore advanced tools.

Download and Flash the OS

Use the Raspberry Pi Imager to flash your chosen OS to the microSD card.

Insert the card into your Raspberry Pi and power it on.

Initial Setup

Follow the on-screen setup for language, Wi-Fi, and updates.

Enable SSH if you want to access it remotely.

Explore the Terminal

Open the terminal and try commands like:

ls → list files

sudo apt update → update package list

sudo apt install nano g++ → install C++ tools

Write and Run C++ Code (you'll learn this in the next chapter!)

Use nano hello.cpp to write your first program

Compile with g++ hello.cpp -o hello

Run with ./hello

Try Ubuntu Later

When you're ready, flash Ubuntu Server or Desktop to your Pi

You'll get access to the same tools used by professional developers

Perfect for learning cross-compilation, hardware control, and advanced Linux features

🧠 What You Can Learn

How Linux works on real hardware

How to use the terminal and install packages

How to write and run C++ code on embedded devices

How to connect sensors, control GPIO pins, and build smart projects

Using Raspberry Pi is one of the most fun and effective ways to learn Linux. Start with Raspberry Pi OS for simplicity, then move to Ubuntu when you're ready to go deeper.

Option 6: Cloud-Based Linux Environments

You can also access Ubuntu through cloud platforms like GitHub Codespaces, Replit, or online Linux terminals.

This is a suggested option for beginners who want to start coding without installing anything. Cloud-based Linux environments let you run Ubuntu in your browser — perfect for quick experiments, remote learning, and collaborative projects.

🧰 What You Need

A computer with internet access

A modern web browser (Chrome, Firefox, Edge)

A free account on platforms like GitHub or Replit

🪄 Step-by-Step Guide

Choose a Platform

GitHub Codespaces: Full Ubuntu environment with VS Code in the browser

Replit: Easy-to-use coding platform with Linux terminal access

Linux Containers: Advanced option for cloud-based Linux labs

Create an Account

Sign up for GitHub or Replit (free plans available)

Start a New Project

On GitHub: Create a repository → Click "Code" → "Open with Codespaces"

On Replit: Click "Create Repl" → Choose "C++" or "Bash" → Start coding

Explore the Terminal

Use commands like:

ls → list files

sudo apt update → update package list

sudo apt install nano g++ → install C++ tools

Write and Run C++ Code (you'll learn this in the next chapter!)

Create a file like hello.cpp

Write your code using the built-in editor

Compile with g++ hello.cpp -o hello

Run with ./hello

🧠 What You Can Learn

How to use Linux tools in the cloud

How to write and run C++ code without installing anything

How to collaborate with others using shared environments

✅ Why Beginners Love Cloud Linux

No installation required

Accessible from any device

Great for learning, teaching, and experimenting

This is the fastest way to start coding in Ubuntu — just open your browser and begin. You’ll learn how Linux works, how to use the terminal, and how to write real C++ code — all in the cloud.

Geek Tip: Keep a Pure Ubuntu System

If you’re serious about learning Linux, consider setting up a dedicated Ubuntu machine. It could be an old laptop, a second partition, or even a Raspberry Pi. This gives you a clean, distraction-free environment to explore, experiment, and build — separate from your school or work system.

Linux is everywhere — from your desktop to your robot, from your terminal to the cloud. It runs natively inside Windows 11, powers embedded boards, and dominates the server world. Once you learn how to install it, you’ll start seeing Linux all around you. And that’s when the real geek journey begins.

2.2.4 Getting familiar with the terminal and file system


