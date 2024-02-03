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

<h3 align= "Center">
Now Let's send the Powershell logs to IBM Qradar using Wincollect 10
</h3>

<h3>Step 01: Open the Wincollect 10 in your PC, you will see following dashbord screen:
 <img width="700" class="avatar mr-2 d-none d-md-block" alt="Owner avatar" src="https://github.com/mehtab-hashim/IBM-Qradar/assets/95371702/903d9acc-c8f4-4652-8273-0433add179b6">
</h3>
 <h3>Step 02:  Write followinf details and click on deploy changes:
  <img width="700" class="avatar mr-2 d-none d-md-block" alt="Owner avatar" src="https://github.com/mehtab-hashim/IBM-Qradar/assets/95371702/a47dcbde-9384-48f7-9bd4-bf3f994a7614">
</h3>

<h3 align= "Center">
Now Powershell logs will be forwarded to Qradar
</h3>
