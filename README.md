# CEP

Step 1: Create 2 VMs using templates

Step 2: Create bastion

Step 3: Install IIS using below commands:

Install-WindowsFeature -name Web-Server -IncludeManagementTools -IncludeAllSubFeature

Step 4: Connect 2 VMs using bastion.

Step 5: Download source code from repo below:

https://github.com/simplilearnaz305/ContosoClinic

Change branch to master branch and download entire code.

Step 6: Extract the code and upload to C:\inetpub\wwwroot\

Step 7: Try accessing website with private IPs.

Step 8: Create Azure SQL using ARM template.


