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
<h3>Procedure</h3>
<h3>•	To verify, Select Start > IBM Win collect 10 Console & open it.</h3>
<img width="700" class="avatar mr-2 d-none d-md-block" alt="Owner avatar" src="https://github.com/mehtab-hashim/IBM-Qradar/assets/95371702/6528d48b-46aa-405b-88c7-6e429e6f9047">


 
<h3>•	After open, below window is shown.</h3>
<img width="700" class="avatar mr-2 d-none d-md-block" alt="Owner avatar" src="https://github.com/mehtab-hashim/IBM-Qradar/assets/95371702/8bce0317-be03-4496-8b70-4d58d1ea9027">


<h3>•	Click on IBM Wincollect </h3>
 
<img width="700" class="avatar mr-2 d-none d-md-block" alt="Owner avatar" src="https://github.com/mehtab-hashim/IBM-Qradar/assets/95371702/3c4c58ea-9265-4c2f-85df-87a8ac4d76bc">


<h3>•	Click on Local Sources </h3>
<img width="700" class="avatar mr-2 d-none d-md-block" alt="Owner avatar" src="https://github.com/mehtab-hashim/IBM-Qradar/assets/95371702/34318d8d-fe93-4b88-84e3-0e01db66a4fc">

 
<h3>•	After click on Local Sources a new window is open as below in Snap.</h3>
<img width="700" class="avatar mr-2 d-none d-md-block" alt="Owner avatar" src="https://github.com/mehtab-hashim/IBM-Qradar/assets/95371702/d6d80f05-aedd-4d1b-99c8-dace868c15cd">

 

<h3>•	Click on Local.</h3>

 

<img width="700" class="avatar mr-2 d-none d-md-block" alt="Owner avatar" src="https://github.com/mehtab-hashim/IBM-Qradar/assets/95371702/8ded589d-1961-46c0-b017-a3ca61a6ccda">




<h3>•	After that, a new tab is open as shown below</h3>

 
 <img width="700" class="avatar mr-2 d-none d-md-block" alt="Owner avatar" src="https://github.com/mehtab-hashim/IBM-Qradar/assets/95371702/a1034a49-599a-4788-9c2a-2cd895012be3">
<h3>•	After that, go to Notification Tab and apply changes.</h3>

<img width="700" class="avatar mr-2 d-none d-md-block" alt="Owner avatar" src="https://github.com/mehtab-hashim/IBM-Qradar/assets/95371702/01932638-df5d-404b-841e-af47b93b5b34">


<h3>•	At End, go to Log Viewer Tab, and you can see path is added successfully.</h3>

<img width="700" class="avatar mr-2 d-none d-md-block" alt="Owner avatar" src="https://github.com/mehtab-hashim/IBM-Qradar/assets/95371702/70da46bb-3996-416b-a741-a2ccb0b9fc28">





 

<h2>NOTE: if you add one or more path, the process is same.</h2>  
 <h3 align= "Center">
Now Sysmon logs will be forwarded to Qradar
</h3>


