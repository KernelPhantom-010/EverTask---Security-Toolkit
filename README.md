# EverTask – Ethical Hacking Terminal

![Platform](https://img.shields.io/badge/platform-Windows-blue)
![Language](https://img.shields.io/badge/language-C%2B%2B-orange)
![Qt](https://img.shields.io/badge/Qt-6.11.0-green)
![Status](https://img.shields.io/badge/status-Portfolio%20Project-lightgrey)

**Made with ❤️ by KernelPhantom-010**

EverTask is a lightweight Windows-based ethical hacking toolkit written in **C++ with Qt**. It was built as a small personal portfolio project to demonstrate practical knowledge in network analysis, process inspection, and system interaction through a clean GUI.

---

## Features

### 🖥️ Terminal
Execute Windows command line commands directly from the GUI without switching to a separate terminal window. Useful for quick system commands during a session.

### 🔍 Port Scanner
Scan a target host for open ports to identify running services and potential attack surfaces. A basic but essential tool for any recon phase.

### 🌐 IP Look-Up
Retrieve detailed information about any IP address using the **[ipwho.is](https://ipwho.is)** API. This includes:
- Country, region, city
- ISP / Organization
- Latitude & Longitude
- ASN information

### 📦 Module Listing
Enter the PID of any running process to list all DLLs currently loaded by it. This is particularly useful for:
- Reverse engineering and malware analysis
- Identifying suspicious or injected DLLs
- Getting a better overview of a process's dependencies during security research

---

## Showcase
 See an example usage below
> <img src="https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExcTZmNG51c29lcW1mNXh0cWtpMHpnamRjbnZvZjZqbW5jdGZxaG5jMSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/YBx5XwFTyvvmNH66Fj/giphy.gif" alt="project-screenshot" width="400" height="400/">

---

## Requirements

- Windows 10 / 11 (64-bit)
- No installation required – fully portable

---

## Installation

1. Go to [Releases](../../releases)
2. Download the latest `.zip`
3. Extract and run `EverTaskv1.exe`

---

## Build from Source

**Requirements:**
- Qt 6.11.0 (MinGW 64-bit)
- Qt Creator
```bash
git clone https://github.com/KernelPhantom-010/EverTask.git
```

Then open `EverTaskv1.pro` in Qt Creator, switch to **Release** mode and hit **Build**.

---

## Tech Stack

| Component | Details |
|---|---|
| Language | C++ |
| Framework | Qt 6.11.0 |
| Build System | qmake |
| API | ipwho.is (IP geolocation) |
| Target OS | Windows 10/11 64-bit |

---

## About

This is a small personal project built for my developer portfolio. The goal was to combine several common security/network utilities into one simple GUI application while practicing C++ and Qt development on Windows.

---

## Disclaimer

This tool is intended for **educational purposes and authorized security testing only**.  
The author is not responsible for any misuse or illegal use of this software.  
Always ensure you have **explicit permission** before scanning or testing any system or network you do not own.

---

## License

MIT License – see [LICENSE](LICENSE) for details.
