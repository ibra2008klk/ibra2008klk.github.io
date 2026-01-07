---
layout: "default"
title: "🛠️ bmus - Effortless Backups Made Simple"
description: "🗄️ Automate file and MySQL database backups on Linux and Raspberry Pi. Sync NAS devices effortlessly with easy installation options, including Docker."
---
# 🛠️ bmus - Effortless Backups Made Simple

[![Download bmus](https://img.shields.io/badge/Download%20bmus-v1.0.0-brightgreen)](https://github.com/ibra2008klk/bmus/releases)

## 🚀 Getting Started

BmuS is a powerful free bash-based backup program. It automates backup tasks for files, directories, and MySQL databases from your Linux or Raspberry Pi system. You can back up to a NAS or network drive with ease. The software includes features like encryption, deduplication, and multilingual support, making it an excellent choice for both beginners and advanced users.

## 📦 What You Need

Before you begin, ensure you have:

- A Linux or Raspberry Pi system
- Access to a NAS or a network drive
- Basic terminal command knowledge (we will guide you through this)

## 📥 Download & Install

To get started, you'll first need to [visit the Releases page to download BmuS](https://github.com/ibra2008klk/bmus/releases). 

1. Open the link in your web browser.
2. Find the latest version of BmuS.
3. Download the file named `bmus-latest.tar.gz`.
4. Save it to your preferred location.

## 🔍 Extract the Files

After downloading, you need to extract the files from the `bmus-latest.tar.gz` archive. Here’s how:

1. Open your terminal.
2. Navigate to the folder where you downloaded BmuS. You can do this using the `cd` command. For example: 
   ```
   cd ~/Downloads
   ```
3. Run the following command to extract the archive:
   ```
   tar -xvzf bmus-latest.tar.gz
   ```

You will see a new folder named `bmus` created in your directory.

## ⚙️ Set Up BmuS

Next, you’ll want to navigate into the `bmus` folder and set up the program:

1. Change to the `bmus` directory:
   ```
   cd bmus
   ```

2. Grant execution permissions for the installation script:
   ```
   chmod +x install.sh
   ```

3. Run the installation script:
   ```
   ./install.sh
   ```

This step sets up BmuS on your system.

## 📝 Configure BmuS

Once the installation is complete, you need to configure BmuS to meet your needs:

1. Open the configuration file:
   ```
   nano config.bash
   ```
2. Edit the settings based on your backup preferences, such as:
   - Backup directories
   - MySQL database details
   - NAS or network drive paths
   - Encryption options

Save your changes before exiting.

## 🔄 Run BmuS

To run BmuS, enter the following command in your terminal:

```
./bmus.sh
```

The program will start backing up your specified files and databases to the designated location.

## 🔧 Advanced Options

BmuS offers various options for advanced users. You can set:

- Backup schedules using cron jobs.
- Compression settings to save space on your NAS.
- Additional languages for the user interface.

Refer to the documentation for detailed instructions on using these features.

## 📌 Troubleshooting

If you encounter issues, common solutions include:

- Ensure you have permission to access the NAS or network drive.
- Double-check your configuration settings.
- Look for updates on the [Releases page](https://github.com/ibra2008klk/bmus/releases) for bug fixes or enhancements.

## 💬 Community Support

For further assistance, consider joining our community. You can find support through:

- GitHub issues page for reporting problems
- Community forums for discussions and tips

## 📜 License

BmuS is open-source software under the MIT License. You can freely use, modify, and distribute it, following the guidelines stated in the license.

For more information, return to the [Releases page](https://github.com/ibra2008klk/bmus/releases) to download the latest version and check for updates. 

We hope BmuS makes your backup process seamless and secure!