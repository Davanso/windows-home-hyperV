# 🚀 Windows Home Hyper-V

A single batch file to enable Hyper-V on Windows 10 Home.

Hyper-V is a feature that allows you to create virtual machines in Windows. While it is available on Windows 8.1, 10, and 11, it is only officially supported on the Professional and Enterprise editions. By default, Hyper-V cannot be installed on Windows 10/11 Home or Single Language editions.

This repository provides a simple batch file to enable Hyper-V on Windows 10 Home.

## 🛠️ Prerequisites

Before enabling Hyper-V, ensure your computer supports virtualization:

1. **Open the Command Prompt.**
2. **Run the following command**:

   ```bash
   systeminfo
Check for “Hypervisor has been detected.”
If you don't see this, virtualization might be disabled in your BIOS. Enter your BIOS setup and look for “Intel Virtualization Technology” or “SVM Mode” to enable it.
📥 Installation Instructions
To install Hyper-V on Windows 10 Home or Single Language:

Download the hyperv_win10.zip file and extract its contents to a folder of your choice.

Right-click on the hyperv_win10.bat file and select “Run as administrator.”

⚠️ Note: The script has been analyzed on VirusTotal using over 60 different antivirus programs and is confirmed to be safe.

Wait for the installation to complete.

Press “Y” when prompted to restart your computer.

✅ Verification
After your computer restarts, verify the installation of Hyper-V:

Press Windows+R to open the Run dialog.
Type optionalfeatures and click “OK.”
In the window that appears, look for "Hyper-V." It should be listed and the checkbox should be checked.
🚀 Usage
Once Hyper-V is installed, you can start using it:

Open the Start menu and search for “Hyper-V.”
Choose your tool:
“Hyper-V Quick Create”: Quickly set up virtual machines.
“Hyper-V Manager”: For advanced management of virtual machines.
