Use an Azure VM to manage on-premises systems
=============================================

            

**Description**


This runbook uses an Azure VM as a management node which will invoke commands on other computers in its network. Combined with an Azure Virtual Network using a site-to-site VPN, this can enable management of on-premises nodes from Azure Automation.


**Requirements**


Before running this runbook, make sure the following resources are available in your Azure environment:


  *  An Azure VM with the VM Agent installed (the 'Proxy VM'), to be used as the management node in the network

  *  A certificate which is installed both on the Proxy VM and as an asset in Azure Automation, for security purposes

  *  An Azure Storage account, in which the runbook will store generated scripts 

**Runbook Contents**


The runbook's contents are displayed below: 


 


 

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
