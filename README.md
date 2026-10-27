
### Name:Madhu Shrie J
### Reg No:212224100034
## AIM:

To install VMware, set up Kali Linux as a virtual machine, and install Sleuth Kit for digital forensic analysis.

## **Design Steps:**

### **Step 1: Install  VirtualBox**

### **Installation Steps:**
1. Download the **Windows hosts** `.exe` file from the official VirtualBox website.  
2. Run the installer and follow the on-screen instructions.  
3. Once installed, launch VirtualBox to verify the installation.


### **Step 2: Install Kali Linux on VirtualBox**
🔗 **Download Kali Linux VM**: [Click Here](https://www.kali.org/get-kali/#kali-virtual-machines)  

### **Installation Steps:**
1. Download the Kali Linux ISO file.Open VirtualBox, click New, enter "Kali Linux", select Type: Linux and Version: Debian (64-bit).  
2. Set RAM to at least 4GB ,Set disk storage to at least 30GB, choose Dynamically Allocated or Fixed Size, and create the VM. 
3. Go to Settings > Storage, click Empty under Controller: IDE. 
4. Select Graphical Install, follow the prompts to set language, location, username, and password.
5. Choose Partitioning Method (Guided - Use Entire Disk) and wait for installation to complete.


### **Step 3: Install Sleuth Kit (CLI-based Forensic Tools)**
🔗 **Download Sleuth Kit**: [Click Here](https://sleuthkit.org/download.php)  

### **Installation Steps:**
1. Download the **Windows ZIP package** from the official website.  
2. Extract the ZIP folder and move it to a suitable directory (e.g., `C:\sleuthkit`).  
3. Add the **bin folder** to Windows PATH:
   - Open **Control Panel** → **System** → **Advanced System Settings**.  
   - Click **Environment Variables** → Edit **Path**.  
   - Add the Sleuth Kit `bin` folder path and save changes.  
4. Verify installation by running:
   ```sh
   fls -version
   
## PROGRAM:

## OUTPUT:
**VIRTUAL BOX:**
<img width="1522" height="1140" alt="Screenshot 2026-10-26 110706" src="https://github.com/user-attachments/assets/bdd48a36-0b9a-430c-bd4c-b8719639bdb2" />


**KALI LINUX:**

<img width="1151" height="893" alt="Screenshot 2026-10-26 110902" src="https://github.com/user-attachments/assets/a73320cc-742b-4e95-8a47-908b6e2149c5" />


**SLEUTH-KIT:**

<img width="963" height="150" alt="Screenshot 2026-10-26 111036" src="https://github.com/user-attachments/assets/a35f5738-34b6-4114-b0cc-f2ae2b08a3de" />


## RESULT:
The setup and installation of VMware, Kali Linux, and Sleuth Kit was completed successfully.
