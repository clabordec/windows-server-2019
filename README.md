<p align="center">
<img src="https://github.com/user-attachments/assets/53c6f5bf-f58c-4b37-8df1-0d775950a35c" width="650" alt="Microsoft Active Directory Logo"/>
</p>



<h1>Installing and setting up Windows Server 2019 in VMware Workstation Pro</h1>
This project outlines the installation and set up of Windows Server 2016 along with the installation and management of Active Directory within VMware Workstation Pro 17.<br />


<h2>Environments and Technologies Used</h2>

- VMware Workstation Pro (Virtual Machines/Compute)
- Active Directory Domain Services

<h2>Operating Systems Used </h2>

- Windows Server 2019

<h2>High-Level Deployment and Configuration Steps</h2>

- Install and set up Windows Server 2022 onto the VM
- Add Active Directory Domain Services to the Server
- Promote the server as the Domain Controller

<br>


<h1>Deployment and Configuration Steps</h1>

## Installing and setting up Windows Server 2019
### Go to a search browser and type on the following `windows server 2019 iso download` choose the highlighed link
<p>
<img src="https://github.com/user-attachments/assets/6e9d4c67-cd56-4dd7-b369-0b04f5a428eb" width="550" alt="Disk Sanitization Steps"/>
</p> 

### Click on the `64-bit edition` download, based on your network speed, this may take between 5-30 minutes
<p>
<img src="https://github.com/user-attachments/assets/303e3a97-9e7c-41c5-af92-939c06d297ea" width="550" alt="Disk Sanitization Steps"/>
</p>

### Save the ISO in any location, in this case I have saved the ISO to the following location, I've also renamed the ISO image:
<p>
<img src="https://github.com/user-attachments/assets/2f13c813-2fb4-4788-b228-b03f95b0e50b" width="550" alt="Disk Sanitization Steps"/>
</p>

### Open VMware Workstation Pro and create a new VM
<p>
<img src="https://github.com/user-attachments/assets/cc525cd1-4138-4a4b-84db-7d0f720788ba" width="550" alt="Disk Sanitization Steps"/>
</p>

### Click Next
<p>
<img src="https://github.com/user-attachments/assets/b99d9086-cb9f-47e6-b9d6-6677b41b1386" width="550" alt="Disk Sanitization Steps"/>
</p>

### To aviod any issue with the VM starting up successfully, choose `I will install the operating system later.` radio option, then click next
<p>
<img src="https://github.com/user-attachments/assets/600e745f-0ce4-4dbc-abf7-bf99e481a92d" width="550" alt="Disk Sanitization Steps"/>
</p>

### Select `Microsoft Windows` as the OS, and `Windows Server 2019` as the version
<p>
<img src="https://github.com/user-attachments/assets/bbf0f339-d111-47d3-8147-ee9053a2aa35" width="550" alt="Disk Sanitization Steps"/>
</p>

### Give the VM a name, and choose a file path
<p>
<img src="https://github.com/user-attachments/assets/40088ffe-0cdf-40ed-aa2a-fabbaee20599" width="550" alt="Disk Sanitization Steps"/>
</p> 

### Depending on your computer specs, assign the necessary amount of storage to the VM
<p>
<img src="https://github.com/user-attachments/assets/0c71a87a-04ca-4df5-b865-2ae4717ee90d" width="550" alt="Disk Sanitization Steps"/>
</p>

### Click finish
<p>
<img src="https://github.com/user-attachments/assets/c0d2035c-dc19-4fa5-a7e8-d36a9dced689" width="550" alt="Disk Sanitization Steps"/>
</p>

### Go to the newly created VM, then select `Edit virtual machine settings`
<p>
<img src="https://github.com/user-attachments/assets/74e40510-6222-488e-bdbd-37fb0af66db7" width="550" height="550" alt="Disk Sanitization Steps"/>
</p>

### Based on the specs of your device, change the memory to a decent amount so that the VM will run smoothly
<p>
<img src="https://github.com/user-attachments/assets/e897fe63-8011-41f2-b2a8-9afd6f85fc19" width="550" alt="Disk Sanitization Steps"/>
</p> 

### Add the ISO file onto the VM
<p>
<img src="https://github.com/user-attachments/assets/a7299d1c-ec19-40fd-b268-12b1342f4dcc" width="550" alt="Disk Sanitization Steps"/>
</p>

### Power up the VM
<p>
<img src="https://github.com/user-attachments/assets/8945909d-6b0d-4757-b96d-08e45e1cb962" width="550" alt="Disk Sanitization Steps"/>
</p>

### Once the VM is powered on, click within the VM and rapidly press space bar or any key of your choosing until you see the following, then hit enter
<p>
<img src="https://github.com/user-attachments/assets/673de096-0f20-48aa-9ece-1defee174ec9" width="550" alt="Disk Sanitization Steps"/>
</p>

### Click Next
<p>
<img src="https://github.com/user-attachments/assets/5a2f044b-79d7-4c62-a745-a7ad0d71afce" width="550" alt="Disk Sanitization Steps"/>
</p>

### Click Install now
<p>
<img src="https://github.com/user-attachments/assets/e437c752-91c3-4064-8cc8-2583498a19c8" width="550" alt="Disk Sanitization Steps"/>
</p>

### Choose the `Windows Server 2019 Standard Evaluation(Desktop Experience)` to have a Graphical User Interface(GUI) for the VM, then click Next
<p>
<img src="https://github.com/user-attachments/assets/de326d97-7c60-4d47-88e3-4993e7303d28" width="550" alt="Disk Sanitization Steps"/>
</p>

### Go through the Mircosoft Software License Terms, click the checkbox to agree then click Next
<p>
<img src="https://github.com/user-attachments/assets/29749b67-470e-4e6b-a355-8703bf4f7a69" width="550" alt="Disk Sanitization Steps"/>
</p>

### Since this is a brand new VM with a brand new OS, choose the custom option to create a new OS
<p>
<img src="https://github.com/user-attachments/assets/150f1f9f-6ed7-467b-adf2-4589a65d9e66" width="550" alt="Disk Sanitization Steps"/>
</p>

### Ensure that the storage is correct, then click Next
<p>
<img src="https://github.com/user-attachments/assets/6a1aff16-7e03-4568-997c-05b9b8f82d77" width="550" alt="Disk Sanitization Steps"/>
</p>

### Depending on your network speed, the process of installing the OS can take between 5-30 minutes
<p>
<img src="https://github.com/user-attachments/assets/6ff01d6e-89c6-46b6-9d01-6a1e63f24900" width="550" alt="Disk Sanitization Steps"/>
</p>

### Once the OS has been installed, input a password, be sure to remember the password, or you will need to re-install the OS if you forget it, then click Finish
<p>
<img src="https://github.com/user-attachments/assets/1c4d5835-9756-47b6-b92a-e715181386a6" width="550" alt="Disk Sanitization Steps"/>
</p>

### After inputting the new password, press Ctrl+Alt+Insert to unlock the Windows Start Screen within the VM
<p>
<img src="https://github.com/user-attachments/assets/f8a8e5ad-710b-47b6-978f-fe4a9e39d4bb" width="550" alt="Disk Sanitization Steps"/>
</p>

### Enter the new password
<p>
<img src="https://github.com/user-attachments/assets/ed45f5f3-75f0-45de-b840-9ece2dfd4d4a" width="550" alt="Disk Sanitization Steps"/>
</p>

### Once logged in, Server Manager will be the first application that will open
<p>
<img src="https://github.com/user-attachments/assets/8c57e57d-62a4-419d-a2b7-97162208121a" width="550" alt="Disk Sanitization Steps"/>
</p>

<br>

## Installing and setting up Active Directory
### Within Server Manager, go to Manage >> Add Roles and Features
<p>
<img src="https://github.com/user-attachments/assets/d4ea0849-be7f-4f1d-9054-f99ca7703e15" width="550" alt="Disk Sanitization Steps"/>
</p>

### Click Next
<p>
<img src="https://github.com/user-attachments/assets/e05a35f3-d923-4692-8f55-ad462612f1f9" width="550" alt="Disk Sanitization Steps"/>
</p> 

### Choose `Role-based or featured-based installation` then click Next
<p>
<img src="https://github.com/user-attachments/assets/6cbe5ca4-c916-4c52-9ba7-728834363df7" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Choose `Select a Server from the server pool` then click Next
<p>
<img src="https://github.com/user-attachments/assets/a1c39903-a270-4518-9dc0-8e7db91bfed" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Add the `Active Directory Domain Services` Role then click Next
<p>
<img src="https://github.com/user-attachments/assets/b2db3a3e-259c-41eb-a3f5-e3a64e407af6" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />


### Make sure that Group Policy Management is checked then click Next
<p>
<img src="https://github.com/user-attachments/assets/179f97b4-5141-4e4a-b5d5-40a7f6666afd" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />


### Click Next
<p>
<img src="https://github.com/user-attachments/assets/78590ccc-1d55-4dc9-8402-f4e13f0599c7" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Click Install after reviewing all of the Roles and Features
<p>
<img src="https://github.com/user-attachments/assets/212cc9e3-c837-4e81-8621-fd9c350ed2bc" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />


## Promoting the server as a Domain Controller
### Once the installation for AD DS has been completed click on `Promote this server to a domain controller`
<p>
<img src="https://github.com/user-attachments/assets/12b29893-188e-487a-972c-638ca3c6fbbe" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Under `Select the deployment operation` choose `Add a forest`, then provide a domain name, in this case I will use `jobskillshare.com` as the domain name, then click Next
<p>
<img src="https://github.com/user-attachments/assets/bb90a10c-0d81-4d36-9420-3351cecd0bf5" width="550" alt="Disk Sanitization Steps" />
</p>
<br /> 

### Be sure to keep the `Forest Function Level` and `Domain Function Level` set to Windows Server 2016, and enter a secure password for the domain, then click Next
<p>
<img src="https://github.com/user-attachments/assets/13d15e13-06bf-4fba-9a84-5209a8cc55b3" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Click Next
<p>
<img src="https://github.com/user-attachments/assets/5686f2a6-974f-4508-a54c-e91410f47ff7" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### The NetBIOS domain name will appear as the domain name without the `.com`, click Next
<p>
<img src="https://github.com/user-attachments/assets/57b403b1-7138-4d68-b77b-6bb7d3dee2f8" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Click Next
<p>
<img src="https://github.com/user-attachments/assets/ff9a4ef4-28f2-421f-a4de-b27cfcb3f696" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Click Next
<p>
<img src="https://github.com/user-attachments/assets/ba0f11f4-4b8c-481c-afb0-c034544a0baf" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Make sure all prerequisites pass, ignore the warning signs, Click Install
<p>
<img src="https://github.com/user-attachments/assets/cd804ffb-b8f3-4fc5-8b6f-2fa19dc4bbd3" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Once the installation is complete, you will be prompted with the following message, the VM will automatically sign out in 5-10 seconds depending in Internet speed
<p>
<img src="https://github.com/user-attachments/assets/25ffc68a-0691-4d7e-add4-fa3b73ac45ba" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Enter in the password that was created for the domain
<p>
<img src="https://github.com/user-attachments/assets/f5f1cbd2-0e4c-4a96-81c5-b12cadc113bd" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Go to Server Manager, then click on Tools, you will see all of the features for Active Directory, along with others that was installed
<p>
<img src="https://github.com/user-attachments/assets/cfb194b7-9cfb-4f5d-9405-8dcde396dc8d" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />


---

<br />


# End of Project
