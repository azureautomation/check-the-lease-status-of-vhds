Check the Lease status of VHDs
==============================

            

This script traverses through the VHDs of all the storage accounts in your subscription and obtains the lease status of them. You can then use the information to delete the unused VHDs. The file is saved as: c:\AzureUnusedVHDs\VHDlist.txt. You can run it
 as Azure Automation runbook as well and hook it to a scheduler, contributing to cost.

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
