<div align="center">

# HOI4 Analyzer GUI

**A powerful desktop application for analyzing Hearts of Iron IV gameplay data**

[![Latest Release](https://img.shields.io/github/v/release/zVSciy/Hoi4GraphToolReleases?style=for-the-badge)](https://github.com/zVSciy/Hoi4GraphToolReleases/releases)
[![Downloads](https://img.shields.io/github/downloads/zVSciy/Hoi4GraphToolReleases/total?style=for-the-badge)](https://github.com/zVSciy/Hoi4GraphToolReleases/releases)
[![License](https://img.shields.io/badge/License-Private-red?style=for-the-badge)](#)

[Download](https://github.com/zVSciy/Hoi4GraphToolReleases/releases) • [Report Bug](https://github.com/zVSciy/Hoi4GraphToolReleases/issues)

</div>

---

## About

The HOI4 Analyzer GUI is a sophisticated desktop application designed to capture, analyze, and visualize gameplay data from Hearts of Iron IV. Transform your gaming sessions into detailed insights with interactive graphs and comprehensive data analysis.

> **Note:** This repository contains only the public releases. Source code is maintained in a private repository.

## Features

### **Real-time Data Collection**
- Monitor your HOI4 gameplay in real-time
- Automatic data capture during gaming sessions
- Support for multiple HOI4 versions

### **Interactive Visualizations**
- Generate dynamic, interactive graphs
- Customizable data filters and views
- Export capabilities for further analysis

### **Easy to Use**
- Simple, intuitive interface
- One-click data collection start/stop
- Automatic file detection and processing

### **Secure & Reliable**
- SHA256 hash verification for all releases
- No internet connection required during gameplay
- Local data processing only

## Screenshots

### Main Interface
![Main Interface](/assets/Overview.png)
*The clean, intuitive main interface of HOI4 Analyzer GUI*

### Data Collection in Progress
![Data Collection](/assets/Live%20Dashboard.png)
*Real-time monitoring of your HOI4 gameplay session*

### Interactive Graphs
![Graph Visualization](/assets/Military%20IC.png)
*Rich, interactive graphs with customizable filters*

### Filter Options
![Filter Panel](/assets/File%20Comparison.png)
*Comprehensive filtering options for detailed analysis*

## Quick Start

### Download

1. Navigate to the **[Releases](https://github.com/zVSciy/Hoi4GraphToolReleases/releases)** section
2. Download the latest `HOI4_Analyzer.exe` from the Assets
3. Verify the download using the provided SHA256 hash

### Usage

#### **Step 1: Setup**
```
1. Launch HOI4_Analyzer.exe
2. Select your Hearts of Iron IV version
3. Click "Start Collection"
```

#### **Step 2: Play & Collect**
```
1. Launch Hearts of Iron IV
2. Play normally while the analyzer runs
3. Data is automatically collected in the background
```

#### **Step 3: Analyze**
```
1. Locate output.txt in your HOI4 directory
2. Load the file in the analyzer
3. Apply filters and view interactive graphs
```

## System Requirements

| Component | Requirement |
|-----------|------------|
| **OS** | Windows 10/11 (64-bit) |
| **Memory** | 4 GB RAM minimum |
| **Storage** | 100 MB free space |
| **HOI4** | Any supported version |

## Security & Verification

Each release includes a **SHA256 hash** for integrity verification:

```bash
# Windows PowerShell
Get-FileHash "HOI4_Analyzer.exe" -Algorithm SHA256

# Command Prompt
certutil -hashfile "HOI4_Analyzer.exe" SHA256
```

Compare the output with the hash provided in the release notes.

## File Locations

- **Output Data**: `{HOI4_Installation_Directory}/output.txt`
- **Application**: Wherever you downloaded the executable
- **No Installation Required**: Portable application

## Issues & Support

Found a bug or have a feature request?
- [Create an issue](https://github.com/zVSciy/Hoi4GraphToolReleases/issues)
- Include your system info and steps to reproduce

## License

This software is proprietary. Source code is not publicly available.

---

<div align="center">

**Made with care for the HOI4 Community**

**Star this repo if you find it useful!**

</div>

