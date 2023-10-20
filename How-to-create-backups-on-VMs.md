# Create a backup .ova file of a Windows 10 VM and demonstrate an .ova import.
## How do you create an .ova backup from a virtual machine in VirtualBox?
- A benefit of working with virtual machines (vm) is their portability, for VirtualBox you can create VMs on one machine and move them to another, or create and clone an entire deployment of VMs.
- You can also pre-configure VMs and also find them online that you can import in a snap and get working right away. 
- An OVA file (Open Virtual Appliances) is a package that contains files used to describe a virtual machine. The OVA stores the configuration details required to set up virtual machines through software like VirtualBx, VMware, and Amazon EC2 for example.
## Here is how to import OVA files in VirtualBox.
- With VirtualBox running, locate “File” in the top menu and click on it, then select “import Appliance.” Appliances refers to virtual machines. 
- A window will pop open with a field to select the .ova file. Browse to the file you’d like to import. VirtualBox will take a few seconds to read the information on the file.
- There will be a window that will shift to a table that lets you choose the settings for imported appliances. You can set key features of a virtualbox, when you are ready, click on the import button and let virtualbox run the import process.
- After the process completes, your VM will be ready to use. 
## Here is how to export OVA files in VirtualBox. 
- Exporting OVA files is a great way to back up and take snapshots of the VMs.
- Exporting OVAs also enables you to clone them across multiple machines or run simultaneous instances of your VMs on the same computer. 
- On the “File” menu, click “Export Appliance”, a new window will open with a listing of available virtual machines. Select the VM you want to export. 
- A new window will allow you to select the location for your exported OVA file. 
- The next screen is the final one in the export process, it allows you to attach some identifying information and specifics to your file before packing it up.  Generally you add a name and description. Lastly click on the “Export” button to start the export process. 
VirtualBox will process your VM into an OVA file.
## What dictates a "good baseline" for a Windows 10 VM?
- A good baseline for a Windows 10 VM is decided based on the needs of the individual user and the purpose of the virtual machine. In other words, the virtual machine's baseline must align with the purpose and goals of the individual or organization that is setting it up.
- Criteria to consider for a good baseline ranges from performance metrics, resource utilization, and even user satisfaction to name a few.
-  If the individual knows the purpose or workload that the vm will be expected to perform, then a good baseline can be established by monitoring the vm and if applicable compare it to industry or organizational standards.
- If there is nothing to compare it to, then document the monitoring results, and update documentation whenever there is a change in software, hardware, and user pattern on the vm. The documentation should be used as a reference point going forward to compare configurations, metrics, and any particulars. 
# In Windows 10, create a System Restore point and perform a Restore operation.
## How to use system restore in windows 10 OS:
- A system restore will ‘undo’ major changes in windows os. It is a useful utility to fix major problems in windows. The windows system restore tool lets you revert to a previous software, registry, and driver configuration called a restore point. System restore is a great tool to use early in the troubleshooting process.
  - Step 1: Open Control Panel and select system and security. 
  - Step 2: Then select system
  - Step 3: Choose System protection
  - Step 4: From the System Properties window, press System Restore. Make sure you’re on the System Protection tab. 
  - Step 5: Select Next from the system restore window titled restore system files and settings. 
  - Step 6: Select the restore point you want to use from those in the list. With your chosen restore point selected, use the Next button to proceed. 
  - Step 7: Confirm the restore point you want to use on the Confirm your restore point window and then select Finish. 
  - Tip: You can select the “Scan for affected programs” link on this page prior to starting the system restore. The report is informational only.
  - Step 8: Choose Yes to the Once started, system restore cannot be interrupted. Do you want to continue? Question. 
  - Tip: If you are running system restore from safe mode, the changes it makes to the computer will not be reversible. 
  - Step 9: System restore will now begin reverting windows to the state it was in at the date and time logged with the restore point that you chose in the previous step. 
  - Step 10: Wait while your computer restarts.  
## What aspects of the computer are effected by a System Restore? What parts of the system are unaffected?
- A system restore affects the software and system configuration of a computer. Some specific aspects of a computer that are affected by a system restore are system files, registry entries, and installed software to name a few. 
- A system restore does not affect hardware components such as CPU, RAM, and hard drive ect. Additionally, it does not affect user generated data at the time of restore. 
