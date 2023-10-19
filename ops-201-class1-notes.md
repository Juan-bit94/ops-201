# Class 1

## Backup and Restore
- This topic is important because computers can experience many failures that result in data loss.
- Having a backup ensures that an organization can recover important files and data in a worst case scenario.
- Backups also restore systems back to a previous stable state, it minimizes down, and it helps individuals get back to work or normal operations faster.
- It is a deterrent to ransomware attacks, in ransomware attacks the hackers encrypt files and demand a ransom to unlock them. If organizations have a recent copy, they can restore the system to a state before the attack.
## Definitions
- Define backup strategies:
  - Full: A full backup includes every file, folder, application and system component. It is a standalone backup, and does not rely on other backups to be useful. Full backups maintain data integrity because they capture the data exactly as it is at the time of the backup. The strategy for full backup is to ensure that all data is backed up, regardless of whether it has changed since the last backup.
  - Incremental: Incremental backups focus on capturing the modifications made since the last backup. This is more storage-efficient and quicker to perform. This type of backup relies on a reference point, typically the last full backup or the last incremental backup. To fully restore data, the last full backup and all incremental backups are needed. The strategy for incremental backups is that it provides a balance between data protection and storage efficiency. Often organizations will perform a full backup weekly and incremental backups daily to capture changes. 
  - Differential: Differential backups capture all the data that has changed or been added since the last full backup, as opposed to just the changes since the last backup operation (i.e. incremental). This strategy is often used for when frequent backups are required to minimize data loss. This requires more storage space compared to incremental backup, but it is faster to recover from than incremental backups.
- Off-site backup strategies:
  - A hot site is ready at a moment's notice to take over for the failed production site.
  - Cold sites takes a long time to spin up but are less costly than hot sites.
  - warm sites take some time to spin up but not as long as cold sites and have middling costs to maintain.
- System redundancy:
  - A server cluster (or server farm) is a set of servers that work together to deliver the same service
  - Reliability, data protection and availability is achieved when redundancy is implemented in case the first server goes down.
  - Failover occurs when the primary server fails over to the backup server. This is done to ensure continuity of services in the event of a failure of the primary server.
  - Snapshots can save the virtualbox vm in an exact state, allowing you to experiment freely and restore back to that state anytime. 
   
