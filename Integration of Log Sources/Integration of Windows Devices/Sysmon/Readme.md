<h2 align="center">
This folder contains the Installation guide of sysmon on windows devices
</h2>

<h3 align= "Left">
Step 01:
</h3>
Download the zip file of sysmon from this repository and extract it at your required desired location.

<h3 align= "Left">
Step 02:
</h3>
Open the command prompt as administrator and goto the location where you extracted the sysmon folder

<h3 align= "Left">
Step 03:
</h3>
In command prompt run following command
<h4 align= "center">
sysmon64.exe –accepteula –i c:\windows\config.xml   
 where "c:\windows\config.xml" is path to your config file,
  if the config file is in the same folder just write name of
  the config file like

  sysmon64.exe –accepteula –i config.xml
</h4>

<h3 align= "Left">
Step 04:
</h3>
Now to see the logs of sysmon, follow the following steps:
01: Goto EventViewer
02: Click on Application and Services Logs
03: Click on Microsoft
04: Click on Windows 
05: Look for the Sysmon folder

<h3 align= "Center">
That's all for sysmon installation
</h3>

<h3 align= "Center">
Now Let's send the Sysom logs to IBM Qradar using Wincollect 10
</h3>
Step 01: Open the Wincollect 10 in your PC, you will see following dashbord screen:
 <img width="700" class="avatar mr-2 d-none d-md-block" alt="Owner avatar" src="https://github.com/mehtab-hashim/IBM-Qradar/assets/95371702/903d9acc-c8f4-4652-8273-0433add179b6">

 Step 02: Click on any of the log sources and type following detail in the next window:
 <img width="700" class="avatar mr-2 d-none d-md-block" alt="Owner avatar" src="https://github.com/mehtab-hashim/IBM-Qradar/assets/95371702/6f12558b-6642-4f2c-9720-cac94473959a">


 <img width="700" class="avatar mr-2 d-none d-md-block" alt="Owner avatar" src="https://github.com/mehtab-hashim/IBM-Qradar/assets/95371702/a1034a49-599a-4788-9c2a-2cd895012be3">

 Step 03: After **deploying changes**, wait for 2 to 3 minutes , you will see sysmon in the “Top Sources TAB”   
 <h3 align= "Center">
Now Sysmon logs will be forwarded to Qradar
</h3>


