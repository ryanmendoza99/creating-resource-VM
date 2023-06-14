#creating-resource-VM


<h1> Creating a Resource Group and Deploying Virtual Machines</h1>
I will be creating a Resource Group in Azure and Deploying two Virtual Machines.
<br/>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure
- Microsoft Remote Desktop

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)
- Ubuntu Server 22.04 LTS
<br/>

<h1> Steps </h1>

<b> Click Resource Groups-> click create -> New RG and select West 3, click create-> click on virtual machines and create - Name the Virtual Machine ->Select the region (should be the same as the resource group)-> Select Windows 10 under Image->Choose Standard size -> Pick a username and password-> create VM-> Log in via Remote Desktop :white_check_mark:</b>

<img src="https://imgur.com/szrg9CA.png">
<img src="https://imgur.com/nnxCLRl.png">

<b>Create Another VM</b>
<p> This VM will be a Domain Controller (Windows server 2022) Same Resource Group->Same location->Name the VM->Select Windows Server 2022->Choose Standard Size-> Pick a username and password-> Log in via Remote Desktop-> logged in :white_check_mark:
</p>
<img src="https://imgur.com/vA04yrG.png">

<b> Create a Linus VM (Ubuntu server)-> same RG->same loc->name the VM-> select Ubuntu->choose standard size-> pick a username and password -> click password NOT SSH public key :no_entry_sign: -> click create and log in via Remote Desktop :white_check_mark:</b>

<img src="https://imgur.com/YzLNrLS.png">



<b>The End </b>
