# HowToSetUpAVirtualBox


<h2>Description</h2>
The project consists of a step-by-step guide to setting up a VirtualBox for Windows Server 2022 and Windows 10.
<br />


<h2>Languages, Utilities, and Environments Used</h2>

- <b>Active Directory</b> 
- <b>Oracle VM VirtualBox</b>
- <b>Windows 10</b> (Enterprise Edition)
- <b>Server 2022</b>


<h2>Project walk-through:</h2>

<p align="center">
To start with installing Virtualbox, first, go to the link provided.
(https://www.virtualbox.org/wiki/Downloads) and click on Windows hosts to install the VirtualBox and All supported platforms with the title (VirtualBox 7.0.8 Oracle VM VirtualBox Extension Pack). <br/>
<img src="https://i.imgur.com/3SysK86.png" height="80%" width="80%" alt="VirtualBox Steps"/>
<br />
<br />
Next would be to go to the link (https://www.microsoft.com/en-us/evalcenter/evaluate-windows-10-enterprise) to download Windows 10. Click Download the ISO - Enterprise.
Register with your information and click Download now. Now go to your Language and click the 64-bit edition ISO - Enterprise downloads.
 <br />
<img src="https://i.imgur.com/nOjyi3s.png" height="80%" width="80%" alt="VirtualBox Steps"/>
<br />
Now we will be downloading Server 2022 ISO. 
Go to the website link https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2022. 
Now you will scroll down to the section titled Get Started For Free. Click Download the ISO, and under the section Register for your free trial today fill out the blank information such as your name and email, etc., then click on Download now. Here you will download your language ISO 64-bit edition.

  <br/>
<img src="https://i.imgur.com/zfwOnpU.png" height="80%" width="80%" alt="VirtualBox Steps"/>
<br />
<br />

We are going to open up Virtualbox, Just click on the setup and hit Next, and install until you proceed with finishing the installation. 
<br />
<br />

<img src="https://i.imgur.com/U6waAS1.png" height="80%" width="80%" alt="VirtualBox Steps"/>
<br />
<br />

Now that we have the Oracle VM VirtualBox installed, we will navigate to Machine and New. This will allow you to choose a name and operating system. Now you can choose the name you would like, I have chosen Windows_2022 as the name and changed the Version to Windows 2022 (64-bit), Now you can click Next. Depending on how much RAM you have, you can leave the base memory as default or move it up to about the recommended max 2048 MB which is 2GB, and move the processers up from 1 to 2 depending on how strong your PC is. Then hit next until you finish creating. <br/>
<br />
<img src="https://i.imgur.com/EFVsQXD.png" height="80%" width="80%" alt="VirtualBox Steps"/>
<br />
<br />

So before we install server 2022, we are going to change and change a few things. First, go to the settings page and under General click on the Advanced tab. 
<br />
<br />

<img src="https://i.imgur.com/bBPz6BT.png" height="80%" width="80%" alt="VirtualBox Steps"/>
<br />
<br />
Change Shared Clipboard and Drag'n'Drop to Bidirectional. 
<br />
<br />

<img src="https://i.imgur.com/BCJurpi.png" height="80%" width="80%" alt="VirtualBox Steps"/>
<br />
<br />

This will let you have control between the Virtualbox and your actual PC screen and Drag'n'Drop lets you drag files from your pc to the virtual machine.
Now go to storage and click on the empty DVD, on the right side where the DVD pulldown is I'm going to click on Choose a disk file and find where you saved the Windows 2022 ISO download.  <br/>
<img src="https://i.imgur.com/GegNDLd.png" height="80%" width="80%" alt="VirtualBox Steps"/>
<br />
<br />

Finally, you can double-click DC to get the VM started and installed.
Now you should have the install screen where you choose the language to install, time, and Keyboard Method. Hit next and install, Choose windows Server 2022 Standard Evaluation (Desktop Experience). Next, Hit custom installation, pick the default disk by pressing Next, and then wait a while for it to reboot and install. You will then be able to create a password for the VM and hit finish.:  <br/>
<img src="https://i.imgur.com/GpSSqyT.png" height="80%" width="80%" alt="VirtualBox Steps"/>
<br />
<img src="https://i.imgur.com/vqyxUvK.png" height="80%" width="80%" alt="VirtualBox Steps"/>
<br />

To unlock the main page go to Input, Keyboard, and Insert Ctrl-Alt-Del.
The last step we will do is go to Devices and click on Insert Guest Additions CD image. This consists of device drivers and system applications that optimize the guest operating system for better performance and usability. Now go to file, click on VirtualBox Guest Additions, and find where it says VboxWindowsAdditions-amd64. Hit next until you hit install and let it reboot.
<br/>
<br/>
<img src="https://i.imgur.com/D2CuszY.png" height="80%" width="80%" alt="VirtualBox Steps"/>
<br/>
<img src="https://i.imgur.com/DaR42qg.png" height="80%" width="80%" alt="VirtualBox Steps"/>
<img src="https://i.imgur.com/BV2q2RT.png" height="80%" width="80%" alt="VirtualBox Steps"/>

<br/>

Thats it!  Now we have finished setting up a VirtualBox on Oracle VM.
 
