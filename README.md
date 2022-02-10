# CEP

Step 1: Create 2 VMs using templates

Step 2: Create bastion

Step 3: Install IIS using below commands:

Install-WindowsFeature -name Web-Server -IncludeManagementTools -IncludeAllSubFeature

Step 4: Create 1 VM that can be used to connect via bastion created in step 2.
