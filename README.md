# Creating-Virtual-Machines-in-Azure
This tutorial will show you how to create virtual machines in Microsoft Azure
<p align="center">
<img src="https://i.imgur.com/4wqxHID.png" height="40%" width="60%" alt="Microsoft Azure Logo"/>
</p>

<h1>Microsoft Azure</h1>
Azure is a cloud computing platform and an online portal that allows you to access and manage cloud services and resources provided by Microsoft. 
<h2>Requirements</h2>

- Computer with Internet Connection
- Microsoft Azure active subscription 

(This assumes you have already setup your Microsoft Azure subscription)

<h2>Configuration Steps</h2>


<h3>Step 1: Create a resource group in the subscription


- Once in the portal subscription select resource groups
- Select button to create resource group
     - In the basics tab name your resource group and pick the region
- Finish resource group by clicking review and create to complete


<p align="center">
<img src="https://i.imgur.com/Afnk87u.png" height="70%" width="70%" alt="Azure Free Account"/> <img src="https://i.imgur.com/yBBln5a.png" height="70%" width="70%" alt="Azure Free Services"/>
</p>


<h3>Step 2: Create a Virtual Machine</h3>
     
- Utilize the search bar and search "virtual machine"
- Select Create, then select Azure Virtual Machine
- You will need to select the same resource group, the same region, and create a name for the virtual machine
    - For this example, we will name the virtual machine "virtualmachine"
    - Use the same resource group and region as steps 2 and 3

<p align="center">
<img src="https://i.imgur.com/y0RafHM.png" height="70%" width="70%" alt="Azure Free Account"/> <img src="https://i.imgur.com/PCJ3QAr.png" height="70%" width="70%" alt="Azure Free Services"/>
</p>
 



* You will then need to select the image and disk size
    - For image we will use Windows 10 Pro
    - For size, select See All Sizes and select Standard D2as_v4
* You will then need to make a username and password
    - For username, we will use "labuser"
    - Create your own password
* Click the box under licensing and finally click Review + Create 


<p align="center">
<img src="https://i.imgur.com/p9UJXND.png" height="70%" width="70%" alt="Azure Free Account"/> <img src="https://i.imgur.com/GHBDae0.png" height="70%" width="70%" alt="Azure Free Services"/>
</p>
 
 You have just successfully created your first virtual machine within Azure!


