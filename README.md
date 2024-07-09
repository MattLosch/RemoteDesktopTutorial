<p align="center">
<img src="https://www.guidingtech.com/wp-content/uploads/8_Quick_Ways_to_Open_Remote_Desktop_Connection_Tool_in_Windows_11.jpg"/>
</p>

<h1>How to create a virtual machine in Azure and remote desktop into it</h1>
In this tutorial, I will show you how to create a windows 10 virtual machine and connect to it through remote desktop<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Resource Groups/Virtual Machines)
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Azure Subscription
- Remote Desktop Connection App

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/pbz9cJY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
The first step in creating your own virtual machine is to head to your personal azure portal. You can do this by going to portal.azure.com
<p>

</p>
<br />

<p>
<img src="https://i.imgur.com/n5crCts.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once you are inside of your azure portal. Go into the resource groups area of the portal. Click on create a new resource group.
</p>
<br />

<p>
<img src="https://imgur.com/a0Q31gM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Select the azure subscription you would like to house your resource group inside of and give your group a name. You'll also want to select the region you would like it to be hosted in.
</p>
<br />

<p>
<img src="https://imgur.com/FTdXozi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once you have done the preivious step, click on review and create at the bottom of the screen and your resource group will be created.
</p>
<br />

<p>
<img src="https://imgur.com/k6A79Zs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After you have created your resource group, head back to the main azure portal and click on virtual machines. 
</p>
<br />

<p>
<img src="https://imgur.com/LuZJaNR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
When you are inside the virtual machine area, click on create an azure virtual machine in the same way you did for the resouce group.
</p>
<br />

<p>
<img src="https://imgur.com/WndgiD8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
When you get into the creation screen, you'll first want to select the resource group you've just created to put the VM into. You can then name your VM and select windows 10 as its image.
</p>
<br />

<p>
<img src="https://imgur.com/SgKZWGA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
You can then scroll down and select the size of the VM. For a windows 10 computer, I recommend using a standard size with 2 virtual cpu's with 16 gb of memory. At this point you can also create a username and password for your VM.
</p>
<br />

<p>
<img src="https://imgur.com/WNlsGQO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Make sure at the bottom of the screen to check the box under licensing. 
</p>
<br />

<p>
<img src="https://imgur.com/A7zoDf6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
When you go over to the networking area of the creation portal, you will see that azure has created a virtual network and subnet for you.
</p>
<br />

<p>
<img src="https://imgur.com/AsBS2Xs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
You can now review and create your virtual machine.
</p>
<br />

<p>
<img src="https://imgur.com/yxA1apz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Azure will now work on creating your VM with the settings you want with it. Once the deployment is complete, you will be able to use your virtual machine. 
</p>
<br />

<p>
<img src="https://imgur.com/R5vk8ce.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After the VM is created you can go back to the virtual machine section of the portal and you will see the the VM you created.
</p>
<br />

<p>
<img src="https://imgur.com/efnCM49.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
When you click on your VM you will see under essentials your public IP address. We will need this in order to Remote Desktop into it so make sure to copy it or write it down. 
</p>
<br />

<p>
<img src="https://imgur.com/Byq9q8B.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We will now go into Remote Desktop Connection which you can find by searching its name in the windows search feature on your desktop.
</p>
<br />

<p>
<img src="https://imgur.com/SDNljvX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once Remote Desktop is launched it will ask you for the IP that you took down for your virtual machine.
</p>
<br />

<p>
<img src="https://imgur.com/n3U4lMS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
<img src="https://imgur.com/R8xvjdT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After you put in your IP address and hit connect, Remote Desktop will ask for your username and password that you made for your virtual machine
</p>
<br />

<p>
<img src="https://imgur.com/3B5sItD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Finally, a pop up will show on your screen to ask if this computer can be trusted. Click "Yes" and your virtual machine will be launched.

  Congratulations, you have now successfully used Remote Desktop to get into an azure created virtual computer. 
</p>
<br />

