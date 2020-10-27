Mount volumes on StorSimple device after Failover
=================================================

            

 

 

This runbook creates a script and stores it in an Azure storage account. It then uses the custom VM script extension to run the script from the VM. This script will connect to the iSCSI target and mount the volumes after the failover using ASR (Azure Site
 Recover) recovery plan.


 


 


Azure VM agent should be installed on the VM before this script cna be executed. If it is not alreay installed, install it inside the VM from http://aka.ms/vmagentwin


        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
