# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*

| service        | cost           |scalability  |availability | workflow |
| ----------- | ----------- | ----------- | ----------- |   ----------- |
| VM     | VMs are more expensive :Service type	Custom name	Region	Description	Estimated monthly cost Virtual Machines		West US	1 B1S (1 vCPU, 1 GB RAM) x 730 Hours; Linux – CentOS; Pay as you go; 0 managed disks – S4, 100 transaction units; Inter Region transfer type, 5 GB outbound data transfer from West US to East Asia	$9,10 | more scalable than App service |can reach 99,99 (SLA)|requires more effort for management and administration|
| App service     | App Service		West US	Basic Tier; 1 B1 (1 Core(s), 1.75 GB RAM, 10 GB Storage) x 730 Hours; Linux OS	$13,14      |   scalability limited with limited instance | less than VM MAX 99,95 in SLA|less managerial efforts, mush simpler and faster|


- *Choose the appropriate solution (VM or App Service) for deploying the app*

app service

- *Justify your choice*
- 
for this project my choice is app service because it is quick to deploy and does not require too much effort.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 
To choose to pass the vm the following points must be considered:

- If the application is excessively demanding in terms of performance, it is necessary to switch to the VM,

- If access to the application must be ensured with a greater level of availability, the choice of the VM makes sense here.

- If the storage of files (such as images on the current application) and database data requires more in terms of storage, switching to the VM is less expensive in the long term than the service app
