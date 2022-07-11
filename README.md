### [Update-Office365.ps1](https://github.com/chosangho89/Update-Office365/raw/master/Update-Office365.ps1) : Script for Update or Rollback Office 365 Client build
##### You can also install this script using cmdlet "Install-Script Update-Office365" <http://scho.kr/update365psg>  
Former links:    
https://aka.ms/update365   
https://gallery.technet.microsoft.com/office/Script-for-Update-or-8fb223bd   
https://gallery.technet.microsoft.com/Script-for-Update-or-8fb223bd


![Update-Office365](/info.png)

Description
==============
-This sciprt helps you to update or rollback your Office 365 client.   
-You can choose your build number or channel.   
-This sciprt change your update channel for Office 365 client.   
-You may need to change execution policy of your system. (Run : Set-ExecutionPolicy -ExecutionPolicy RemoteSigned #more detail : https://docs.microsoft.com/en-us/powershell/module/microsoft.powershell.core/about/about_execution_policies?view=powershell-6)   
-You may need to unblock this script. (User Unblock-File cmdlet or right click - Properties - Unblock)   
-You need to run Internet Explorer if you get a blank drop down list of Version field. (Initial setting for IE is required)   
-About this script [Apps for Microsoft 365 update script](https://blog.scho.kr/en-us/microsoft365/Offfice365-Update-script/)
  
Details
===========
MD5 : 021078D21428D106435EEA12B582802B   
SHA1 : 6760DC201A936CFEBDF7BF0C5AAA67DB76553948   
SHA256 : 983C356485057EBD658C2373AA96FB7BD3050DBA3A94DC29539DBA61208AB0D8   
File size : 14.5KB (14,916 bytes)   
File type : PS1   

Requirements
============
Office 365 Business, Office 365 ProPlus, Office 365 Personal   

Release note
==============
2020-08-18 : Channel name bug fixed. (Correction by [tobiasabele](https://github.com/tobiasabele))   
2020-06-26 : Channel name changed.   
2019-04-19 : Verification procedure for installed Office 365 client  is added.   
2019-02-26 : Bud fixed / SSL/TLS issue.   
2018-10-16 : Insider, Monthly Channel (Targeted), DevMain channel added.   
2018-10-02 : Bud fixed / Original content URL is changed.   
2018-06-25 : Bug fixed / Deferred channel entry is displayed correctly.   
2018-06-08 : Updated (Source content is updated!. Modified regular expression) / Add check box for disabling update.   
2018-03-06 : Bug fixed / Now, you can change channel again!   
2017-09-26 : Bug fixed / Insider channel removed   
2017-07-26 : GUI is added   
2017-07-25 : This script can modify registry value for changing update channel.   
2017-07-24 : Insider channel (First release for current channel) is added.   
