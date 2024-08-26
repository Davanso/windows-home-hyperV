# Windows Home Hyper-V

A single batch file to enable Hyper-V on Windows 10 Home.

Hyper-V is a feature that allows you to create virtual machines in Windows. While it is available on Windows 8.1, 10, and 11, it is only officially supported on the Professional and Enterprise editions. By default, Hyper-V cannot be installed on Windows 10/11 Home or Single Language editions.

This repository provides a simple batch file to enable Hyper-V on Windows 10 Home.

## Prerequisites

Before enabling Hyper-V, you need to verify that your computer supports virtualization.

1. Open the Command Prompt.
2. Type the following command and press Enter:

   ```bash
   systeminfo
Look for the entry “Hypervisor has been detected.” If you don't see this, virtualization might be disabled in your computer's BIOS. You can enable it by entering your BIOS setup and looking for an option similar to “Intel Virtualization Technology” or “SVM Mode” and enabling it.
Installation Instructions
To install Hyper-V on Windows 10 Home or Single Language:

Download the hyperv_win10.zip file and extract its contents to a folder of your choice.

Right-click on the hyperv_win10.bat file and select “Run as administrator.”

Note: The script has been analyzed on VirusTotal using over 60 different antivirus programs and is confirmed to be safe.

Wait for the installation process to complete.

When prompted, press “Y” to restart your computer.

Verification
Once your computer restarts, you can verify the installation of Hyper-V:

Press Windows+R to open the Run dialog.
Type optionalfeatures and click “OK.”
In the window that appears, look for "Hyper-V." It should be listed and the checkbox should be checked.
Usage
After confirming the installation, you can start using Hyper-V:

Open the Start menu and search for “Hyper-V.”
You can use “Hyper-V Quick Create” to quickly set up virtual machines, or open “Hyper-V Manager” for more advanced management of virtual machines.
