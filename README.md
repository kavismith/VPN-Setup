<h1>VPN Setup and Usage through Proton VPN</h1>
In this tutorial, we will be seeting a VPN through Microsoft Azure and download Proton VPN. <br />


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
Nowthat you ave create your Virtual Machine for your VPN,  searchfor virtual machine in the searchbar of microsoft azure and click on the VM you ceated for your VPn. Next, copy your public IPv4 address. 
</p>

<h2>Connect to Your Remote Desktop</h2>


![image](https://github.com/kavismith/VPN-Setup/assets/143667203/8cd05a3b-4f52-4aec-83e1-844a6abfb7c4)



</p>
<p>
Search for your Remote Desktop on your personal computer and paste your IPv4 address in there. Next, sign into your Remote Desktop with  the username and password you created while creating your virtual machine for your VPN.
</p>

<h2>Check your Remote Desktop IPv4 address</h2>


![image](https://github.com/kavismith/VPN-Setup/assets/143667203/d3708220-6589-46a7-85f3-362a60e9d4d6)




</p>
<p>
Once signed into your Remote Desktop go whatismyipaddress.com to check your Remote Desktop IPv4 address
</p>

<h2>Sign up for Proton VPN</h2>


![image](https://github.com/kavismith/VPN-Setup/assets/143667203/cd57294b-7dda-4d71-aaf4-04b637eec782)


</p>
<p>
On your personal computer go to account.protonvpn.com/signup to sign up for a free Proton VPN account. 
</p>

<h2>Download Proton VPN</h2>


![image](https://github.com/kavismith/VPN-Setup/assets/143667203/528083d4-55de-43a5-8dba-be331094b670)
![image](https://github.com/kavismith/VPN-Setup/assets/143667203/81706cc3-7a1b-411a-9f24-9eb82a837ca6)




</p>
<p>Once you hace successfully signed up and you created your username and password to Proton VPN on your personal computer, the next step is to sign into Proton VPN account on the Remote Desktop. Once signed in you need click on downloads to download your proton Vpn server.
</p>


<h2>/Download Proton VPN</h2>


![image](https://github.com/kavismith/VPN-Setup/assets/143667203/8ae1bac3-0368-48ae-9575-f8717fdaef09)


</p>
<p>
once you have clicked download, go to your downloads in your folder file and open the download. Then go through the stept to download Proton VPN on your Remote Desktop
</p>
