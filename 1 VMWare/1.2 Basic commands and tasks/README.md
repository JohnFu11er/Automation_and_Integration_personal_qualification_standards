<h1><u>VMWare Basic Commands and Tasks</u></h1>

<h1>Creating a Virtual Machine</h1>

### 1. Launch VMware Workstation
### 2. Click New Virtual Machine
### 3. Select the type of virtual machine you want to create and click Next:<br>
    
    Note: Your choice depends partially on the hardware version you want your virtual machine to have. For more information, see Virtual machine hardware versions (1003746).

    Custom:
        This gives you an option to create a virtual machine and choose its hardware compatibility. You can choose from Workstation 16.x, Workstation 15.x, Workstation 14.x.<

    Typical:
        This creates a virtual machine which has the same hardware version as the version of Workstation you are using. If you are using Workstation 16.x, it creates a virtual machine with hardware version 16. If you are using Workstation 15.x a virtual machine with hardware version 15 is created.

### 4. Click Next
### 5. Select your guest operating system (OS), then click Next. You can install the OS using: 
    - An installer disc (CD/DVD)
    - An installer disc image file (ISO)
         
### 6. Click Next
### 7. Enter your Product Key (if applicable)
### 8. Create a user name and password
### 9. Click Next
### 10. Enter a virtual machine name and specify a location for virtual machine files to be saved, click Next.
### 11. Establish the virtual machine's disk size, select whether to store the virtual disk as a single file or split the virtual disk into 2GB files, click Next.
### 12. Verify the other configuration settings for your virtual machine:
    - Memory
        Change the amount of memory allocated to the virtual machine.

    - Processors
        Change the number of processors
        Change the number of cores per processor
        Change the virtualization engine

    - CD / DVD
        With advanced settings where you can choose between SCSI, IDE

    - Network adapter
        Configure it to bridge, NAT, or Host-only mode, or customize where you can choose between 0 to 9 adapters

    - USB Controller
    
    - Sound card
    
    - Display
         
### 13. Click Finish.
    When the virtual machine is powered on, the VMware Tools installation starts. You are prompted to restart your virtual machine once the Tools installation completes.

### 14. Configure your Operating System from it's installation wizard