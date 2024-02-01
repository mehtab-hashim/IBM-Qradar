<h1 align="center">Linux Log Source Integration</h1>

<h3 align="Left">Step 01: </h3>
<div align="Left">  
 Login as root user in Linux server
 </div>
<h3 align="Left">Step 02: </h3>
Open terminal and type “cd /etc/”

<h3 align="Left">Step 03: </h3>
 Type “nano rsyslog.conf”

<h3 align="Left">Step 04: </h3>
At the end of the file enter the following line:
local6.*;authpriv.*;*.err;*.info @@ip_addr_Qradar:514
<h3 align="Left">Step 05: </h3>
Type the following command:
“service auditd restart”
<h3 align="Left">Step 06: </h3>
 Type the following command:
“service rsyslog restart” or “Systemctl restart rsyslog”

<h3 align="Left">Step 07: </h3>
After restarting the services, check the status of both files by:
“service auditd status”, “service rsyslog status”
Make sure that there are no error messages regarding the syslog facilities.
<h3 align="Left">Step 08: </h3>
 Check for the log sources in QRadar
