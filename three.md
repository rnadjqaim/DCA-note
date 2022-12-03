![image](https://user-images.githubusercontent.com/103530494/205360771-fcfeb8fd-c705-4708-881f-fa8a6ab1ebde.png)
* container not VMs : 
- docker engine rather than hypervisor, each vm has full os with its own kernal, memory
management and virual device drivers, 
-docker containers are able to share a host kernal and share application libraries.
- we can docker inside the vm, 
- vm need backups but the containers dod not need backup , dara store in volume, 
- capacity optimization.
- physical server can host vms that may house docker host , but also may host any number
- of monolithic vms
- -file system in containers : layered but in vm independet
- 
