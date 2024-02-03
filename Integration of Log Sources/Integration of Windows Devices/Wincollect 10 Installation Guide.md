
<h2 align="center">
This folder contains the Installation guide of Wincollect 10
</h2>
<h3>We will use three methods to install Wincollect 10 on Windows devices</h3>
<h3 align="center">Method 01</h3>
<h4>Procedure</h4>
<h4>•	Download the latest version of the Win Collect 10 agent from IBM official website or download from this repository.</h4>
<h4>•	Double-click the installer to begin the installation.</h4>
<h4>•	In the Welcome to the IBM 64-bit Setup Wizard window, click Next.</h4>

<img width="700" class="avatar mr-2 d-none d-md-block" alt="Owner avatar" src="https://github.com/mehtab-hashim/IBM-Qradar/assets/95371702/aec7ad7f-4fd0-4ed7-9b14-136f96f1a3f5">
 
<h4>•	Accept the EULA and click Next.</h4>
<img width="700" class="avatar mr-2 d-none d-md-block" alt="Owner avatar" src="https://github.com/mehtab-hashim/IBM-Qradar/assets/95371702/ec6fc0ac-6c6e-4542-b186-f0840f9de451">



<h4>•	In the Installer Options window, select Quick.</h4>
<img width="700" class="avatar mr-2 d-none d-md-block" alt="Owner avatar" src="https://github.com/mehtab-hashim/IBM-Qradar/assets/95371702/53862cd2-9d63-4a72-b2cc-27a0e7d2461a">

 
<h4>The Quick installation option configures the agent to collect Security, System, and Application events.</h4>
<img width="700" class="avatar mr-2 d-none d-md-block" alt="Owner avatar" src="https://github.com/mehtab-hashim/IBM-Qradar/assets/95371702/cd07528c-bb69-407d-a7c1-ce6cedcd74dd">


 

<h4>•	After the installation is complete, the Completing the IBM Win Collect Setup Wizard window appears. Click Finish to close the installer.</h4>


<h4>•	To verify, Select Start > IBM Win collect 10 Console & open it.</h4>
<img width="700" class="avatar mr-2 d-none d-md-block" alt="Owner avatar" src="https://github.com/mehtab-hashim/IBM-Qradar/assets/95371702/9373d9b0-2fd4-453c-af13-24afc35a3f4a">
<img width="700" class="avatar mr-2 d-none d-md-block" alt="Owner avatar" src="https://github.com/mehtab-hashim/IBM-Qradar/assets/95371702/62adc6fc-023d-45e7-a5de-88ab22fb74c7">

 
<h4>•	Go to Agent Configuration > Agent Settings</h4>
<img width="700" class="avatar mr-2 d-none d-md-block" alt="Owner avatar" src="https://github.com/mehtab-hashim/IBM-Qradar/assets/95371702/72ff6804-d081-4ac7-a131-39dd8e5780f1">

 

<h4>•	The last step is to Test the connection and if your test connection is passed, its means your installation is successful.</h4>

 
<img width="700" class="avatar mr-2 d-none d-md-block" alt="Owner avatar" src="https://github.com/mehtab-hashim/IBM-Qradar/assets/95371702/a203c77a-4a03-4013-8c3a-4b4ba687e692">

<h2 align="center">While following above procedure, you may get following error at the end of Installation</h2>

<img width="700" class="avatar mr-2 d-none d-md-block" alt="Owner avatar" src="https://github.com/mehtab-hashim/IBM-Qradar/assets/95371702/9e5c83e9-64fc-4bf3-a440-a98cb146d9fb">

<h3>In this case open Commad prompt as Administrator, go to the location(folder) of Wincollect.msi and write following command</h3>

<h3>msiexec.exe /qn /i WinCollect-10.1.6-3.x64.msi QUICK_INSTALL="yes" WC_DEST=“<ip_addr>" ADMIN_GROUP="true“   </h3>
<h3>Where ip address is ip address of Qrdar machine   </h3>
<h3>In this method, nothing will appear on the screen and wincollect will install in the background automatically</h3>

<h2 align="center">While following above procedure, you may get error of missing msiexec.exe file</h2>
<h3>In this case, open CMD as administrator and goto the location where you keep the wincollect setup and just type the name of the exe file like that:</h3>


<img width="700" class="avatar mr-2 d-none d-md-block" alt="Owner avatar" src="https://github.com/mehtab-hashim/IBM-Qradar/assets/95371702/50f6e5ac-add1-4d3f-9b2b-fcae4e3ba056">

<h3>Now from the GUI follow all the steps we saw in our first procedure</h3>
