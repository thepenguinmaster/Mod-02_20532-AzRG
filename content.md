<!---
Version: 1.0 
-->
# Exercise 1: Creating a Network and Resource Container
## INTRODUCTION MESSAGE
You want to create a virtual network that you can use for your new virtual machine. As part of creating the virtual network, you will also create a resource group.  
  
The main tasks for this exercise are as follows:  
  
Sign in to the Azure Portal.  
Create a virtual network and a resource group.
## COMPLETION MESSAGE
Results: After completing this exercise, you will have a new virtual network and resource group in Azure.
### Login as Student
Login as Student with a password of Pa$$w0rd.

#### :bulb: KNOWLEDGE
You can use the Commands menu and choose Ctrl\+Alt\+Delete then click Student and enter Pa$$w0rd and press Enter. You can also use the Command menu and choose Paste/Paste Password instead of typing the password manually.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773130.jpg
>* ShowAutomatically = No





### On the Start screen, click Internet Explorer
On the Start screen, click the Internet Explorer tile

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773131.jpg
>* ShowAutomatically = No





### Go to the new Azure Portal
Go to \(https://portal.azure.com\). Enter the email address of your Microsoft account associated with your Azure subscription. Then enter the password for your Microsoft account. Check Keep me signed in. Click Sign In.

#### :bulb: KNOWLEDGE
If this is your first time logging in to the Azure portal, you will see a dialog with a tour of the portal. Click "Maybe Later" to bypass the tour. If you see a pop-up for Skype for Business click Don't Enable. Note that you can further customize your Dashborad by clicking Edit Dashboard and then click Done Customizing when finished.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773132.jpg
>* ShowAutomatically = No





### Browse Resource Groups
In the navigation pane on the left side of the Azure Portal, scroll down, and then click More Services. In the Browse blade that displays, click Resource groups.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773133.jpg





### Click the Add button
In the Resource groups blade that displays, view your list of resource groups. At the top of the Resource groups blade, click the Add button.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773134.jpg





### In the Resource group blade, perform the following
In the Resource group blade, perform the following steps:  
a. In the Resource group name dialog box, provide the value 20532.  
b. In the Resource group location list, select the region that is closest to your current location.  
c. In the Resource group blade, click Create.

#### :bulb: KNOWLEDGE
Note: You can click on the LODS "Support" tab to view what data center location that this VM is running in. Click the LODS "Content" tab to return to these instructions.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773135.jpg





### Browse Virtual networks
In the navigation pane on the left side of the Azure Portal, scroll down, and then click More Services. In the Browse blade that displays, scroll down and click Virtual networks.

#### :bulb: KNOWLEDGE
Note that you can click the Show menu button \(3 horizontal lines at top of menu on left\) to show the full menu. You can click it again to Hide the menu \(showing just icons\).

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773136.jpg





### Click the Add button
In the Virtual networks blade that displays, view your list of virtual network instances. At the top of the Virtual networks blade, click the Add button.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773137.jpg





### In the Create virtual network blade:
In the Create virtual network blade, perform the following steps:  
a. In the Name dialog box, provide the value vnet20532.  
b. In the Location list, select the region that is closest to your current location.  
c. Ensure that the Address space box has the value 10.0.0.0/16.  
d. In the Subnet name box, provide the value Apps.  
e. Ensure that the Subnet address range box has the value 10.0.0.0/24.  
f. In the Resource group section, select the Use existing option.  
g. In the Resource group section, locate the dialog box and provide the value 20532.  
h. In the Create virtual network blade, click Create.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773138.jpg






# Exercise 2: Creating a Development Virtual Machine
## INTRODUCTION MESSAGE
You need a new storage account that you will use while creating your virtual machine. This storage account will contain the VHDs for the virtual machine that you will create.  
  
The main tasks for this exercise are as follows:  
  
Create a storage account.  
Create a virtual machine.
## COMPLETION MESSAGE
Results: After completing this exercise, you will have a new virtual machine stored in a new storage account.
### Browse Storage Accounts
In the navigation pane on the left side of the Azure Portal, scroll down, and click More Services. In the Browse blade that displays, scroll down and click Storage Accounts.

#### :bulb: KNOWLEDGE
Note that you can click the Show menu button \(3 horizontal lines at top of menu on left\) to show the full menu. You can click it again to Hide the menu \(showing just icons\).

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773139.jpg
>* ShowAutomatically = No





### Click the Add button
In the Storage accounts blade that displays, view your list of Storage instances. At the top of the Storage accounts blade, click the Add button.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773140.jpg





### In the Create storage account blade:
In the Create storage account blade that displays, perform the following steps:  
a. In the Name box, provide the value stor20532\[your name in lowercase here\]. Add a number if it is not unique.  
b. In the Deployment model section, ensure that the Resource manager option is selected.  
c. In the Account kind list, ensure that the General purpose option is selected.  
d. In the Performance section, ensure that the Standard option is selected.  
e. Click on the Replication list and select the Locally-redundant storage \(LRS\) option.   
f. Make sure the Storage service encryption and Secure Transfer options are Disabled.  
g. In the Resource group section, select the Use existing option.  
h. In the Resource group section, locate the dialog box and provide the value 20532.  
i. In the Location list, select the region closest to your current location.  
j. Ensure that the Pin to Dashboard option is selected.  
k. Allow other options to default.  
l. Click Create.

#### :bulb: KNOWLEDGE
Note: Wait for Azure to finish creating the storage account prior to moving forward with the lab. You will receive a notification when the Storage Account is created and you will see the Storage Account's blade. This may take a few minutes.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773141.jpg





### Wait for Azure to finish creating the storage acct
Wait for Azure to finish creating the storage account prior to moving forward with the lab. You will receive a notification when the Storage Account is created and you will see the Storage Account's blade. If not, click the Notification icon at the top of the dashboard \(a bell icon\) and then click the top \(latest\) deployments successful messasge to take you to the Storage Account blader.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773163.jpg





### Browse Virtual machines
In the navigation pane on the left side of the Azure Portal, scroll down, and click More Services. In the Browse blade that displays, click Virtual machines.

#### :bulb: KNOWLEDGE
Note that you can click the Show menu button \(3 horizontal lines at top of menu on left\) to show the full menu. You can click it again to Hide the menu \(showing just icons\).

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773142.jpg





### Click the Add button
In the Virtual machines blade that displays, view your list of Virtual Machine instances. At the top of the Virtual machines blade, click the Add button.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773143.jpg





### Search for template images:
In the Virtual Machines blade that displays, enter Visual Studio 2017 in the search field and press Enter.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773144.jpg





### Select Visual Studio template image:
Click on the Visual Studio Community 2017 on Windows Server 2016 \(x64\) template.

#### :bulb: KNOWLEDGE
Note: Ensure that you select this specific template as all further lab instructions assume that you are using this exact Azure SDK version, OS and Visual Studio version.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773145.jpg





### Click the Create button
In the Visual Studio Community 2017 blade, ensure that the Resource Manager deployment model is selected and click the Create button.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773146.jpg





### In the Create virtual machine blade:
In the Create virtual machine blade that displays, click Basics and perform the following steps:  
a. In the Name dialog box, provide the value vm20532.  
b. In the VM disk type list, select the value HDD.  
c. In the User Name dialog box, provide the value Student.  
d. In the Password and Confirm Password dialog boxes, provide the value AzurePa$$w0rd  
e. In the Resource Group section, locate the Use existing option, and then select the 20532 resource group.  
f. In the Location list, select the region closest to your current location.  
g. Click OK.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773147.jpg





### Locate and select the F4 Standard option
In the Create Virtual Machine blade that displays, click Size and perform the following steps:  
a. Locate and click the View all hyperlink.  
b. Locate and select the F4 Standard option.  
c. Click the Select button.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773148.jpg





### Click Settings and perform the following steps:
In the Create Virtual Machine blade that displays, click Settings and perform the following steps:  
a. Under the Storage: Use managed disks section, select the No option.  
b. Under the Storage Account section, select stor20532\[your name here\].  
c. Under the Virtual Network section, select vnet20532.  
d. Under the Subnet section, select Apps.  
e. Leave default values for Public IP Address, Network Security Group \(firewall\), Extensions and High Availability  
f. Under the Monitoring: Diagnostic section, select the Disabled option for both options.  
g. Scroll down and click OK.  
  
  


#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773149.jpg





### When presented with a Purchase blade:
When presented with a Purchase blade, confirm by clicking Purchase to create the virtual machine using your specified configuration. This will take 10-15 minutes to deploy.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/847821.jpg





### Select the newly created virtual machine
After the VM has finished deploying, the Overview blade should open automatically. If not, select the newly created virtual machine from your Dashboard. 

#### :bulb: KNOWLEDGE
Note: The creation of a new virtual machine can take anywhere between 10 to 15 minutes. You will see a notification on the Dashboard \(home screen\) when your virtual machine is created and running.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773151.jpg





### In the Settings section, select the Disks option
In the Settings section, select the Disks option. In the Disks blade, click Add Data Disk.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773152.jpg





### In the Attach unmanaged disk blade:
In the Attach unmanaged disk blade, perform the following steps:  
a. In the Source type, select New \(empty disk\)  
b. For Account type, select Standard \(HDD\).  
c. In the Size \(GiB\) dialog box, provide the value, 128.  
d. For Storage container, click Browse, then from the Storage account blade, select the previously created storage account, stor20532\[Your Name Here\]

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773153.jpg





### Select vhds container
In the Containers blade, select vhds container and click Select

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773154.jpg





### In the Attach unmanaged disk blade:
In the Attach unmanaged disk blade, in the Name box, change the name to vm20532-AllFiles, then hit tab and verify that the Storage blob name updates to vm20532-AllFiles.vhd then click OK

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773155.jpg





### Click Save and wait
Click Save.   
Note: You may have to wait a few minutes for the empty disk to be attached to the virtual machine

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773156.jpg





### Scroll left, click Overview then click Connect
Scroll to the left and click Overview to return to the vm20532 blade. Wait for the status to be Running. Click Connect at the top of the screen.

#### :bulb: KNOWLEDGE
If prompted with a message "Internet Explorer blocked a pop-up from portal.azure.com", choose "Options for this site" and then select "Always Allow". Then try to Connect again.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773157.jpg





### If necessary, allow popups
If presented with a message box that shows a popup has been blocked, select Options for this site and choose Always Allow. Then click Connect again.





### Click Open
In the download dialog box, click Open.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773158.jpg





### In the Remote Desktop Connection dialog box:
In the Remote Desktop Connection dialog box, perform the following steps:  
a. Click Don’t ask me again for connections to this computer to prevent this dialog box from displaying again.  
b. Click Connect.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773159.jpg





### In the Windows Security dialog box:
In the Windows Security dialog box, perform the following steps:  
a. For the User name dialog box, provide the value, Student.  
b. For the Password dialog box, provide the value, AzurePa$$w0rd.  
c. Click OK.

#### :bulb: KNOWLEDGE
 Note: If you computer is on a domain, you may need to add a backslash before the username to "escape" the domain.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773160.jpg





### In the Remote Desktop Connection dialog box:
In the Remote Desktop Connection dialog box, perform the following steps:  
a. Verify if the Remote certificate name matches the name of your virtual machine.  
b. Click Don’t ask me again for connections to this computer to prevent this dialog box from displaying again.  
c. Click Yes.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773161.jpg





### When you are prompted, click Yes
When you are prompted to allow your network connection to discover external devices, click Yes.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773162.jpg






# Exercise 3: Configuring the Virtual Machine for Development
## INTRODUCTION MESSAGE
Now that you have a new virtual machine, you need to configure Internet Explorer's Enhanced Security Configuration option. You also need to ensure that your working files are on the machine and ready.  
  
The main tasks for this exercise are as follows:  
  
Disable Internet Explorer Enhanced Security Configuration  
Create an AllFiles drive and extract the AllFiles Content to it.  
Authenticate to Visual Studio using the Microsoft Account associated with your Azure subscription.
## COMPLETION MESSAGE
Results: After completing this exercise, your development virtual machine will have your lab files installed. Your virtual machine will also have Visual Studio, Azure PowerShell, and the Azure SDK installed.
### Server Manager will start automatically
Server Manager will start automatically after 30 seconds. If not, on the Start screen, click the Server Manager tile.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773165.jpg
>* ShowAutomatically = No





### Click Local Server.
In the navigation pane on the left side, click Local Server.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773166.jpg





### Change IE Enhanced Security Configuration
In the Properties box, click the IE Enhanced Security Configuration option that is currently set to On.  
In the Internet Explorer Enhanced Security Configuration dialog box, perform the following steps:  
a. Under Administrators, select Off.  
b. Under Users, select Off.  
c. Click OK.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773167.jpg





### Open Create and format hard disk partitions
Press the Start button of the VM and type 'disk partition' to search for apps that contain the words 'disk partition' . Select "Create and format hard disk partitions".

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773168.jpg





### In the Initialize Disk dialog box:
In the Initialize Disk dialog box, perform the following steps:  
a. Verify that Disk 2 is selected for initialization.  
b. Verify that MBR \(Master Boot Record\) is the selected partition style.  
c. Click OK.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773169.jpg





### In the lower-half of the Disk Management window:
In the lower-half of the Disk Management window, perform the following steps:  
a. Scroll down and find Disk 2 that was previously initialized.  
b. Right-click the unallocated partition, and then click New Simple Volume.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773170.jpg





### In the New Simple Volume wizard:
In the New Simple Volume wizard: Click Next.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773171.jpg





### Verify the Simple volume size in MB
Verify that the Simple volume size in MB is a number greater than 100,000. Click Next.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773172.jpg





### In the Assign the following drive letter list:
In the Assign the following drive letter list, click F. Click Next.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773173.jpg





### Verify that the File System setting is set to NTFS
Verify that the File System setting is set to NTFS. In the Volume Label dialog box, provide the value AllFiles. Click Next.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773174.jpg





### Click Finish to close the dialog box
Click Finish to close the dialog box, to create the partition.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773175.jpg





### Ignore format disk warning
Note: If a dialog box displays stating that “You need to format the disk in drive F: before you can use it.”, you can safely close it because you have already formatted the disk. You can close the Disk Management window also.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773176.jpg





### On the Taskbar, open Internet Explorer
On the Taskbar, click the Internet Explorer icon.





### Set up Internet Explorer 11
If you are prompted to set up Internet Explorer 11, perform the following steps:  
a. Select Use recommended security, privacy and compatibility settings.  
b. Click OK.

#### :bulb: KNOWLEDGE
If you see a pop-up for "Several add-ons are ready for use" choose Don't Enable

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773178.jpg





### Go to Github
Go to https://github.com/MicrosoftLearning/20532-DevelopingMicrosoftAzureSolutions/releases/tag/C-v.1.1.1  
\(You can position the cursor in the URL address field and click the "A" icon \(Type Text\) in the step window to paste the code\)

#### :bulb: KNOWLEDGE
If you wish to go with the latest published release of the labfiles you can go to: https://github.com/MicrosoftLearning/20532-DevelopingMicrosoftAzureSolutions/releases/latest   
  
However, please recognize that the lab instructions and screenshots listed here may not be aligned with the latest release.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773179.jpg



#### :calling: COMMAND
```TypeText
https://github.com/MicrosoftLearning/20532-DevelopingMicrosoftAzureSolutions/releases/tag/C-v.1.1.1
```


### Download the AllFiles compressed folder
Scroll down the screen until you find the allfiles download link. \(It will likely have a version number in the file name e.g. allfiles-v1.1.1.zip\) Click the link to download the AllFiles compressed folder. In the Internet Explorer download dialog box, click Save.  After the download is completed, you can then close the download dialog box.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773180.jpg





### Click the Windows File Explorer icon:
Click the Windows File Explorer icon in your Taskbar. On the left navigation bar, expand the This PC node and click the Downloads node. Right-click the allfiles compressed folder and select the Properties option.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773181.jpg





### Click Unblock if present
In the allfiles Properties dialog box, do the following:  
a. Click Unblock if present.  
b. Click OK.

#### :bulb: KNOWLEDGE
If the Unblock button is not present, do the following:  
a. Clear ReadOnly checkbox.  
b. Click OK.  
c. Click OK.  \(to apply to all files and folders\)  
d. Open Properties window again and click Unblock and click OK.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773182.jpg





### Select the Extract all option.
Right-click the allfiles compressed folder and select the Extract All option.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773183.jpg





### In the Extract Compressed (Zipped) Folders dialog
In the Extract Compressed \(Zipped\) Folders dialog box, do the following:  
a. In the Files will be extracted to this folder: dialog, provide the value F:\\  
b. Ensure that the Show extracted files when complete checkbox is NOT selected.  
c. Click Extract.  
Wait for the extraction process to complete.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773184.jpg





### Verify the F: drive
Verify the F: drive, by clicking This PC and then double-clicking the F: drive. You should see folders for some of the future modules. You can close File Explorer now.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773185.jpg





### Open Visual Studio
On the Start screen, locate and click the Visual Studio app. Note: You might have to scroll-down to locate the Visual Studio app on your Start list. There should also be a shortcut on the desktop. It may take a few minutes for Visual Studio to open for the first time.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773186.jpg





### Sign-in using a Microsoft Account
You will be prompted to sign-in using a Microsoft Account. Perform the following steps:  
a. Click the Sign in button.  
b. Enter the email address of your Microsoft account.   
d. Enter the password for your Microsoft account.  
e. Click Sign In.

#### :bulb: KNOWLEDGE
Note: You may be prompted by Internet Explorer to remember this password. You can safely close and ignore this dialog.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773187.jpg





### Configure the appearance of your IDE
If you have never used Visual Studio in the past, you will also be prompted to configure the appearance of your IDE. Perform the following steps:  
a. Leave all fields set to their default values.  
b. click the Start Visual Studio button.

#### :bulb: KNOWLEDGE
Wait for Visual Studio to finish preparing for first use. Note: This process typically takes between 2 to 5 minutes.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773189.jpg





### Validate the Visual Studio Start Page
Validate that you can see the Visual Studio Start Page. This may take a few minutes to appear.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773190.jpg





### Close Visual Studio
Close Visual Studio





### Close Internet Explorer
Close Internet Explorer





### Close Server Manager
Close Server Manager





### Close RDP session
Close RDP session and click OK to disconnect

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773194.jpg





### Stop VM to save billing charges
If you are stopping labs for the day, on the vm2032 Overview page in the Azure Portal, click Stop to stop billing charges until you start labs again. When prompted, click Yes to stop the VM.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens/773195.jpg





### Close Internet Explorer
Close Internet Explorer to end the lab






