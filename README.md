<h1>Improve Incident Response with Azure Alerting</h1>

<h2>Description</h2>
In this lab, I improved incident response by implementing Azure Alerting. 
I began by creating a virtual machine (VM) using the Azure CLI. 
Next, I set up an alert rule to monitor the VM's performance. 
Using the CLI, I also created a metric alert to track specific metrics, followed by establishing a service health alert to monitor Azure service issues. 
Additionally, I created an Azure Activity log monitor to keep track of activities within the Azure environment. 
To test the alerts, I deleted the VM, which triggered the alerts as expected. I received email notifications, and the alerts were visible in the monitor. 
This lab demonstrated my ability to enhance incident response capabilities using Azure Alerting, ensuring timely notifications and effective monitoring of resources.
<br />


<h2>Concepts and Utilities Used</h2>

- <b>Azure - Monitor</b>
- <b>Alerts</b>
- <b>CLI</b>
- <b>VMs</b>

<h2>Environments Used </h2>

- <b>Azure</b>

<h2>Environment walk-through:</h2>

<p align="center">
Create VM: <br/>
<img src="https://imgur.com/uBkMPOH.png" height="80%" width="80%" alt="Alerts Steps"/>
<br />
<br />
Create Alert Rule:  <br/>
<img src="https://imgur.com/pRHtLBz.png" height="80%" width="80%" alt="Alerts Steps"/>
<br />
<br />
Create an alert for the VM using greater than 90% CPU:  <br/>
<img src="https://imgur.com/BW6IGfK.png" height="80%" width="80%" alt="Alerts Steps"/>
<br />
<br />
Create a Service Health Alert for the deletion of the VM:  <br/>
<img src="https://imgur.com/QaUmpkm.png" height="80%" width="80%" alt="Alerts Steps"/>
<br />
<br />
Create Azure Activity log monitor:  <br/>
<img src="https://imgur.com/5sw2Ns1.png" height="80%" width="80%" alt="Alerts Steps"/>
<br />
<br />
Set the rule to email when the VM is deleted:  <br/>
<img src="https://imgur.com/gWQvKO7.png" height="80%" width="80%" alt="Alerts Steps"/>
<br />
<br />
The alerts are in Monitor:  <br/>
<img src="https://imgur.com/tjcydur.png" height="80%" width="80%" alt="Alerts Steps"/>
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
