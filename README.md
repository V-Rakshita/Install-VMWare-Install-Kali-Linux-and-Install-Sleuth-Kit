# Install-VMWare-Install-Kali-Linux-and-Install-Sleuth-Kit
## AIM:

To install VMware, set up Kali Linux as a virtual machine, and install Sleuth Kit for digital forensic analysis.

## DESIGN STEPS:
### INSTALLING VMWARE:

  Step 1: Download VirtualBox

•	Go to: https://www.virtualbox.org/

•	Click on the “Downloads” link under the Get Started
 
<img width="979" height="487" alt="image" src="https://github.com/user-attachments/assets/38e360a3-c766-456b-bc8b-c1b0b1ad6b85" />

•	Click on the Windows hosts link under the VirtualBox Platform Packages

<img width="628" height="312" alt="image" src="https://github.com/user-attachments/assets/1b9f1dde-12bf-4a03-9d6c-07009f43e88a" />

Step 2: Run the Installer

•	Locate the downloaded .exe file (usually in your Downloads folder)
 
<img width="979" height="142" alt="image" src="https://github.com/user-attachments/assets/e52a0580-a106-464f-a145-b995c32ce34a" />

•	Double-click it to run the installer

<img width="628" height="314" alt="image" src="https://github.com/user-attachments/assets/fae3b6b7-12b3-4d63-85c9-aabbe084b961" />


•	Click Next

•	Keep default settings unless you want to change any installation location or any other features

•	Click Next

Step 4: Network Interface Warning

•	Click yes to proceed

<img width="547" height="305" alt="image" src="https://github.com/user-attachments/assets/52b8f189-c2e1-4ddb-9519-171d4c769e0b" />

Step 5: Begin Installation

•	Click Install

<img width="626" height="332" alt="image" src="https://github.com/user-attachments/assets/2c8b02bb-45fe-49f9-b6b2-f6e9b2bbc9c6" />

Step 6: Finish Setup

•	Click Finish

•	VirtualBox will launch

<img width="535" height="281" alt="image" src="https://github.com/user-attachments/assets/9641a98b-1930-4675-b782-6ed8bf6a4e20" />


### INSTALLING KALI LINUX:

Step 1: Open Oracle VirtualBox

•	After installing VirtualBox, open it

•	The main screen of VirtualBox should appear.

Step 2: Download Kali Linux VirtualBox Image

•	Go to: https://www.kali.org/get-kali/#kali-platforms

•	Choose Virtual Machines

<img width="583" height="293" alt="image" src="https://github.com/user-attachments/assets/088405f5-f09c-4f2b-9839-8a8768e765a8" />

•	Choose VirtualBox and download the .7z file.

<img width="272" height="274" alt="image" src="https://github.com/user-attachments/assets/34938c99-6df1-43dd-b9d6-3eca5c27a6fd" />

Step 3: Extract the file

•	Use WinRar to extract the .7z file by right clicking on the downloaded file and choosing the “Extract” option.

•	A folder containing a .vbox file is created.

Step 4: Import Kali Linux into VirtualBox

•	Open Oracle VirtualBox

•	Go to File and choose the “Import Appliance” option

<img width="315" height="274" alt="image" src="https://github.com/user-attachments/assets/2be5a4f8-7a4b-43f3-8f0c-f704d766bc66" />

•	Click Choose, then browse to the extracted .vbox file.

•	Select the .vbox file and click Next.

•	Keep the default settings as such.

•	Click Import and wait for the import process to finish.

Step 5: Start Kali Linux

•	Once imported, you will see "Kali Linux" in the left panel

•	Select it and click Start and wait for Kali Linux to boot.

<img width="369" height="276" alt="image" src="https://github.com/user-attachments/assets/932b866c-f0c1-43be-8757-69c1b6c70c5c" />


<img width="372" height="265" alt="image" src="https://github.com/user-attachments/assets/52db4d0b-33e1-4079-8fc7-f36ffc227385" />


<img width="364" height="264" alt="image" src="https://github.com/user-attachments/assets/fb9b4ad7-0698-40ce-9d74-f3c8c78d6dca" />

Step 6: Use the terminal in Kali Linux

•	After login (default username: kali, password: kali)

•	Open the Terminal (black monitor icon)

•	Try the basic Linux commands:

<img width="394" height="285" alt="image" src="https://github.com/user-attachments/assets/2a2c255d-6d46-4c13-884c-7196158a9c21" />


### INSTALLING SLEUTH KIT:

•  Download Sleuth Kit from www.sleuthkit.org/sleuthkit/download.php

<img width="628" height="321" alt="image" src="https://github.com/user-attachments/assets/2451b155-2023-4cc6-9165-ab44795d5815" />

•	Move the downloaded folder to the program files.

•	Go to the system environment variables from the Start menu.

<img width="628" height="262" alt="image" src="https://github.com/user-attachments/assets/e0f2d493-f9a1-4862-a183-22e8a3f83ad8" />

<img width="384" height="446" alt="image" src="https://github.com/user-attachments/assets/daf52caa-3b9e-4fc6-b6dd-95ea7e623d13" />

•	Click environment variables

<img width="419" height="460" alt="image" src="https://github.com/user-attachments/assets/54b53a5f-1026-4ac4-ac11-3e09ac22e42d" />

•	Click the path

•	Now add the sleuth kit folder address.

•	And then click OK.

<img width="448" height="151" alt="image" src="https://github.com/user-attachments/assets/e0452dbe-a7d0-4579-84c9-733a98b1781d" />

•	Open command prompt and type fls -V to check sleuth kit is installed or not.

•	Lists partition layout


•	Lists files and directories

<img width="513" height="222" alt="image" src="https://github.com/user-attachments/assets/58926a70-31a6-4ead-8283-0f80d9ea57e6" />


## RESULT:
The setup and installation of VMware, Kali Linux, and Sleuth Kit was completed successfully.
