<p align="center">
<img src="https://github.com/user-attachments/assets/4163f177-02a4-4148-9171-d2f031f5e5aa"/>
</p>

<h1>Creating Virtual Machines</h1>
This tutorial demonstrates the creation of Virtual Machines on Azure.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)

<h2>Operating Systems Used </h2>

- Windows 11 Pro 24H2

<h2>Installation Steps</h2>

<p>
<img src="https://github.com/user-attachments/assets/7b7ae527-0386-4848-946a-e76bcdcccc59" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Go to https://portal.azure.com, sign in with your Microsoft account.


</p>
<p>
<br />
<img src="https://github.com/user-attachments/assets/7965f722-77e2-423a-b20a-b156368ec98f" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
In the left-hand menu, click "Virtual Machines".Click "+ Create" > "Azure virtual machine".


</p>
<p>
<br />
<img src="https://github.com/user-attachments/assets/d1e02abe-ba23-4951-80e5-cbf98c79b789" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Subscription: Choose your Azure subscription.

Resource Group: Create a new one or use an existing one.

Virtual Machine Name: Name your VM.

Region: Pick a location close to you or your users.

Image: Choose the OS

Username & Password: Set login credentials.


</p>
<p>
<br />
<img src="https://github.com/user-attachments/assets/7c22001e-6c89-4563-a912-5ae25dd2e576" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Choose Standard HDD, Standard SSD, or Premium SSD depending on your performance needs.

Keep the default unless you have specific storage requirements.


</p>
<p>
<br />
<img src="https://github.com/user-attachments/assets/280ef0d8-86e9-4740-8f37-064438ca5f37" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Use the default Virtual Network and Subnet, or create new ones.

Make sure a Public IP is assigned if you need to access the VM externally.

Keep NIC network security group settings default unless you have specific firewall rules.


</p>
<p>
<br />
<img src="https://github.com/user-attachments/assets/793ec46f-741c-453e-a581-2e8c540079a1" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
You can enable auto-shutdown, backup, and monitoring options here.

Feel free to leave most of these as default unless required.


</p>
<p>
<br />
<img src="https://github.com/user-attachments/assets/76beeef8-b0a9-47dc-9ccb-a0c9fbc13e50" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Click "Review + create".

Azure will validate your settings.

Once validation passes, click "Create".


</p>
<p>
<br />
<img src="https://github.com/user-attachments/assets/2d36ce0a-0c92-4983-b0df-d5a2186921ab" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Azure will deploy your VM. This usually takes a few minutes.

Click "Go to resource" once deployment is complete.


</p>
<p>
<br />
<img src="https://github.com/user-attachments/assets/ba02c434-209f-4e42-b5c1-42f2c1d2cec4" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Click Connect at the top of the VM overview page.

Choose RDP (for Windows) or SSH (for Linux).

Follow the connection instructions provided.


</p>
<p>
<br />
<img src="https://github.com/user-attachments/assets/c17e394a-d90f-480f-90b9-9f40fabd2237" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
And that’s it! Your virtual machine is up and running on Azure, ready for whatever tasks or applications you need.

























