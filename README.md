<h1>VPN Setup and Usage through Proton VPN</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (VPN)
- Remote Desktop
- Proton VPN
  


<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Proton VPN

<h2>High-Level Steps</h2>

- Personal IP Adress Look up
- Create Resource Group
- Create Virtual Machine
- Open up Remote Desktop using VM Ipv4




<h2>Actions and Observations</h2>


![Screenshot 2023-09-04 163704](https://github.com/kavismith/VPN-Setup/assets/143667203/686285da-0ef9-4f2a-990b-cc88202a92ff)

</p>
<p>
Go to Whatismyipaddress.com to see what your personal computers IPv4 address is. Take note of this. 
</p>
<br />
<h2>Create Yuor Microsoft Azure VM(Virtual Machine)</h2>

![Screenshot 2023-09-05 041743](https://github.com/kavismith/VPN-Setup/assets/143667203/412265d7-de72-4ae6-979d-3b31b0e35afa) 

![Screenshot 2023-09-05 041820](https://github.com/kavismith/VPN-Setup/assets/143667203/febd0df2-8168-420c-ae59-84ad83abe440)

</p>
<p>
Create a Subscription with Microsoft Azure account. After you Microsoft Azure is created, search in the search bar for Virtual Machine and craete a Virtual Machine for your VPN. Allow the system to create its own Resource Group. Name your VM(VPN). Change your region to another country other than the country you live in. Make sure you impage is set to Widows 10 pro. Chamge your size to 2-4 vcpus to make sure your VM run fast. Then creat create a username and passowrd so you can login to you Remote Desktop Connection(maske sure its a username and password taht you will remember). Last, check the windows license box at the end before you move on. Click next and go to the networking tab. You would see that the system automatically generated the virtual network/subnet. After you pass validation, click create. 
</p>
<br />

<h2>Copy your Public IP Address from Virtual Machine Created</h2> 

![Screenshot 2023-09-05 042312](https://github.com/kavismith/VPN-Setup/assets/143667203/de66f10c-d657-4057-a254-579cd0ecba32)


</p>
<p>
Nowthat you ave create your Virtual Machine for your VPN,  searchfor virtual machine in the searchbar of microsoft azure and click on the VM you ceated for your VPn. Next, copy your public IPv4 address. Last, search for your Remote Desktop on your persona computer and past your IPv4 address in there.
</p>

<h2>Connect to Your Remote Desktop</h2>


![image](https://github.com/kavismith/VPN-Setup/assets/143667203/8cd05a3b-4f52-4aec-83e1-844a6abfb7c4)


</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
