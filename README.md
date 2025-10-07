# Azure Setup





<h2>Description</h2>
This Azure subscription was used to create a simulated Security Operations Center (SOC) environment using Microsoft Sentinel. Resources were deployed securely under a single resource group, with NSGs applied and logs ingested into Log Analytics for analysis. The lab demonstrated Azure security configuration, event monitoring, and cost management best practices.
<br />


<h2>Utilities Used</h2>

- <b>Azure Portal (portal.azure.com)</b> 
- <b>Microsoft Entra ID (Azure Active Directory)</b>
- <b>Azure Resource Manager (ARM)</b>

During subscription setup, I used the Azure Portal to register a free trial subscription linked to my Microsoft account. The environment was automatically associated with a Microsoft Entra ID (Azure AD) tenant for identity management and authenticated access. Azure Resource Manager (ARM) was used to provision and organize future resources under a dedicated subscription.


<h2>Setup Walkthrough:</h2>

<p align="center">
Azure portal page:
  
<br/>
<img src="https://i.imgur.com/990yCzB.png"height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Created Resources
<br />
<img src="https://i.imgur.com/JrHMCHl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Created Virtual Network
<br/>
<img src="https://i.imgur.com/7odSjEY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/Ek7gX4v.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/xcOQIJV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/wKqXwR2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
CT Lab was created
<br/>
<img src="https://i.imgur.com/e2Ek6C1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Created Virtual Machine:  <br/>
<img src="https://i.imgur.com/VbbG8dT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/rsJoRDq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
CT-SOC-Lab setup with all resources needed to do project: <br />
-Virtual Machine
-Public IP Address
-Network Security Group
-Virtual Network
-Network Interface
-Disk
-Virtual Network
<img src="https://i.imgur.com/0jAyCAP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>







<h2>Summary</h2>

Created an Azure Free Trial subscription through the Azure Portal, verified identity, and activated default directory services. Configured cost management and billing settings to monitor usage, ensuring no paid resources were deployed during initial setup. Prepared environment for future SOC lab resource creation.






