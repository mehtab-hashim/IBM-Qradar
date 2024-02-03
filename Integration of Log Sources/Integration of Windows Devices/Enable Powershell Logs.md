<h2 align="center">
This folder contains the procedure for enbling and forarding Powershell logs to Qradar
</h2>

<h3>Step 01</h3>
Run CMD as administrator

<h3>Step 02</h3>
Run Following three commands one by one:

<h4>01: REG ADD HKLM\SOFTWARE\Policies\Microsoft\Windows\Powershell\ScriptBlockLogging /f /v EnableScriptBlockLoggging /t REG_DWORD /d 1</h4>  
<h4>02: REG ADD HKLM\SOFTWARE\Policies\Microsoft\Windows\Powershell\ModuleLogging /f /v EnableModuleLogging /t REG_DWORD /d 1</h4>    
<h4>03: REG ADD HKLM\SOFTWARE\Policies\Microsoft\Windows\Powershell\ModuleLogging\ModuleNames /f  /v “*” /t REG_SZ /d “*” </h4> 

<h3 align= "Center">
That's all for Powershell Log Enabling
</h3>

<h2 align= "Center">
Now Let's send the Powershell logs to IBM Qradar using Wincollect 10
</h2>

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

 



 <h3>Step 02:  Write following details and click on deploy changes:
  <img width="700" class="avatar mr-2 d-none d-md-block" alt="Owner avatar" src="https://github.com/mehtab-hashim/IBM-Qradar/assets/95371702/a47dcbde-9384-48f7-9bd4-bf3f994a7614">
</h3>

<h3>•	Click on Add Button, a new window is open, Enter the unique Name, Select the type Microsoft Exchange Server, add the path of Microsoft exchange server , & save it as shown below.</h3>
<img width="700" class="avatar mr-2 d-none d-md-block" alt="Owner avatar" src="https://github.com/mehtab-hashim/IBM-Qradar/assets/95371702/c0922b12-6877-4f82-b002-05e45b45e908">

 


<h3>•	After that, go to Notification Tab and apply changes.</h3>

<img width="700" class="avatar mr-2 d-none d-md-block" alt="Owner avatar" src="https://github.com/mehtab-hashim/IBM-Qradar/assets/95371702/01932638-df5d-404b-841e-af47b93b5b34">


<h3>•	At End, go to Log Viewer Tab, and you can see path is added successfully.</h3>

<img width="700" class="avatar mr-2 d-none d-md-block" alt="Owner avatar" src="https://github.com/mehtab-hashim/IBM-Qradar/assets/95371702/70da46bb-3996-416b-a741-a2ccb0b9fc28">





 

<h2>NOTE: if you add one or more path, the process is same.</h2>
<h3 align= "Center">
Now Powershell logs will be forwarded to Qradar
</h3>
