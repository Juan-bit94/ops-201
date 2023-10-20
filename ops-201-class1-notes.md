# Class 1

## Backup and Restore
- This topic is important because computers can experience many failures that result in data loss.
- Having a backup ensures that an organization can recover important files and data in a worst case scenario.
- Backups also restore systems back to a previous stable state, it minimizes down, and it helps individuals get back to work or normal operations faster.
- It is a deterrent to ransomware attacks, in ransomware attacks the hackers encrypt files and demand a ransom to unlock them. If organizations have a recent copy, they can restore the system to a state before the attack.
## Understanding How Backups Work
- Backups generally work by looking at an attribute of the file known as an archive bit. When a file is created or modified, the archive bit is set to 1, indicating that the file has not been backed up in its current state.
- When a backup is made, that archive bit may be cleared - that is, set back to 0 - to indicate that the file has been backed up. Be aware, some backups do not clear the archive bit.
- Navigate to a file, such as a word doc, right-click it, and choose properties. At the bottom of the general tab, you will see an advanced button, click the advanced button. If the File is ready for archiving, the box is checked, which means the archive bit is set.
## Backup Options
- When performing a data backup, you will have several decisions to make on various options. Windows comes with a backup utility, named File History (or Backup and Restore in versions older than Windows 8). There are also network-based backup programs that can back up multiple systems across a network. Finally, online and cloud-based backup utilities have gained significant popularity over the last few years. 
## Definitions
- Define backup strategies:
  - Full: A full backup includes every selected file, folder, application and system component. It is a standalone backup, and does not rely on other backups to be useful. Full backups take the longest to back up, but it is the fastest to restore. This backup clears the archive bit, and is set to 0.
  - Incremental: Incremental backups focus on capturing the modifications made since the last backup. It clears the archive bit and this type of backup is the fastest in terms of backup speed but slower to restore. 
  - Differential: Differential backups capture all the data that has changed or been added since the last full backup, as opposed to just the changes since the last backup operation (i.e. incremental). It does not clear the archive bit, and it's between normal and incremental on backup and restore speeds.
- Off-site backup strategies:
  - A hot site is ready at a moment's notice to take over for the failed production site.
  - Cold sites take a long time to spin up but are less costly than hot sites.
  - warm sites take some time to spin up but not as long as cold sites and have middling costs to maintain.
- System redundancy:
  - A server cluster (or server farm) is a set of servers that work together to deliver the same service
  - Reliability, data protection and availability is achieved when redundancy is implemented in case the first server goes down.
  - Failover occurs when the primary server fails over to the backup server. This is done to ensure continuity of services in the event of a failure of the primary server.
  - Snapshots can save the virtualbox vm in an exact state, allowing you to experiment freely and restore back to that state anytime.
## Setting up a backup in windows 10
- Open File History (Windows Backup) by clicking Start -> Settings -> Update & Security -> Backup.
- To back up files, you need to select a location to back them up. This can be an optical drive, USB device, or network location that's been mapped to a drive letter.
- Click add A drive to select a backup location. It will open the select drive window like the one shown.
- Set Automatically Back Up My Files to the Off position.
- Click the more options link to open the backup options page.
- This page allows you to set how often files are backed up, how long they are kept, and what will get backed up.
- To start the backup immediately, click the backup now button.
## Verifying and testing Backups
- After backups, you need to complete one more step-verifying the backup.
- You can use backup and data recovery software to verify a backup. Two free softwares to use are Macrium Reflect and EaseUS Todo Backup.
  - These types of softwares offer validation features.
  - You can also use data recovery software to simulate a data recovery process. If these tools can successfully recover data from your backup files, it's a good indication that the backup is valid. 
  - You can use data recovery software such as Recuva and TestDisk, they are free and again it can help users recover lost or deleted data from various storage devices. 

