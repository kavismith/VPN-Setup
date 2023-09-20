<h1>VPN Setup And Proton VPN Setup</h1>
In this tutorial, we will be setting up a VPN through Microsoft Azure and download Proton VPN<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (VPN)
- Remote Desktop
- Proton VPN
  


<h2>Operating Systems Used </h2>

- Windows 10 Microsoft Azure
- Proton VPN

<h2>High-Level Steps</h2>

- Personal Desktop IP Address Look up
- Create Resource Group
- Create Virtual Machine
- Open up Remote Desktop using VM Ipv4
- Create a free account with Proton VPN
- Download Proton VPN




<h2>Actions and Observations</h2>


![Screenshot 2023-09-04 163704](https://github.com/kavismith/VPN-Setup/assets/143667203/686285da-0ef9-4f2a-990b-cc88202a92ff)

</p>
<p>
To find your personal computer's IPv4 address, please follow these steps:

- Open a web browser on your personal computer.

- In the web browser's address bar, type in "whatismyipaddress.com" and press Enter.

- The website will display your personal computer's IPv4 address on the screen.

Make sure to take note of this IPv4 address for your reference or any necessary networking configurations.


</p>
<br />
<h2>Create Yuor Microsoft Azure VM(Virtual Machine)</h2>

![Screenshot 2023-09-05 041743](https://github.com/kavismith/VPN-Setup/assets/143667203/412265d7-de72-4ae6-979d-3b31b0e35afa) 

To set up a subscription with your Microsoft Azure account and create a Virtual Machine for your VPN, follow these steps:

- Start by creating a subscription with your Microsoft Azure account.

- Once your Microsoft Azure account is set up, use the search bar to find and select "Virtual Machine."

- Create a new Virtual Machine for your VPN, allowing the system to create its own Resource Group.

- Name your Virtual Machine (VM) as "VPN."

- Change the region to a country different from your current location.

- Ensure that the VM image is set to "Windows 10 Pro."

![Screenshot 2023-09-05 041820](https://github.com/kavismith/VPN-Setup/assets/143667203/febd0df2-8168-420c-ae59-84ad83abe440)

- Adjust the size of the VM to have 2-4 vCPUs for optimal performance.

- Create a username and password that you can remember for logging in to your Remote Desktop Connection.

- Check the Windows license box at the end of the setup.

- Click "Next" and proceed to the networking tab, where you'll notice that the system has automatically generated the virtual network and subnet.

- After passing the validation checks, click "Create."

By following these steps, you will have successfully set up a Microsoft Azure subscription, created a Virtual Machine for your VPN, configured the necessary settings, and initiated the creation process. This Virtual Machine will allow you to run a Windows 10 Pro image with enhanced performance for your VPN needs.

</p>
<p>

</p>
<br />

<h2>Copy your Public IP Address from Virtual Machine Created</h2> 

![Screenshot 2023-09-05 042312](https://github.com/kavismith/VPN-Setup/assets/143667203/de66f10c-d657-4057-a254-579cd0ecba32)


</p>
<p>
Now that you have created your Virtual Machine for your VPN, follow these steps to find your public IPv4 address:

- In Microsoft Azure, use the search bar to locate and select "Virtual Machine."

- Locate and click on the Virtual Machine that you previously created for your VPN.

- Within the VM's details or settings, you should be able to find and copy your public IPv4 address.

Make sure to note down or copy this public IPv4 address for your reference, as it will be essential for configuring and accessing your VPN on the Virtual Machine. 
</p>

<h2>Connect to Your Remote Desktop</h2>


![image](https://github.com/kavismith/VPN-Setup/assets/143667203/8cd05a3b-4f52-4aec-83e1-844a6abfb7c4)



</p>
<p>
To access your Virtual Machine for your VPN from your personal computer using Remote Desktop, please follow these steps:

- On your personal computer, search for "Remote Desktop."

- Open the Remote Desktop application.

- In the Remote Desktop application, paste the IPv4 address that you copied from your Virtual Machine settings in Microsoft Azure.

- After pasting the IPv4 address, click on "Connect."

- You will be prompted to enter the username and password that you created while setting up your Virtual Machine for your VPN in Microsoft Azure.

- Enter the username and password, and then click "Sign In" or "Connect."

By following these steps, you will establish a Remote Desktop connection to your Virtual Machine for your VPN, allowing you to access and manage it from your personal computer.

</p>

<h2>Check your Remote Desktop IPv4 address</h2>


![image](https://github.com/kavismith/VPN-Setup/assets/143667203/d3708220-6589-46a7-85f3-362a60e9d4d6)




</p>
<p>
After signing into your Remote Desktop session, you can check the IPv4 address assigned to your Remote Desktop by following these steps:

- Open a web browser within your Remote Desktop session.

- In the web browser's address bar, type in "whatismyipaddress.com" and press Enter.

- The website will display the IPv4 address associated with your Remote Desktop on the screen.

This will allow you to view and note the specific IPv4 address assigned to your Remote Desktop session.
</p>

<h2>Sign up for Proton VPN</h2>


![image](https://github.com/kavismith/VPN-Setup/assets/143667203/cd57294b-7dda-4d71-aaf4-04b637eec782)


</p>
<p>
To sign up for a free Proton VPN account on your personal computer, please follow these steps:

- Open a web browser on your personal computer.

- In the web browser's address bar, type "account.protonvpn.com/signup" and press Enter.

- You will be directed to the Proton VPN sign-up page.

- Follow the on-screen instructions to create your free Proton VPN account, which typically includes providing your email address, creating a secure password, and any other required information.

- Once you have completed the sign-up process, you should have access to your new Proton VPN account.

By following these steps, you can easily register for a free Proton VPN account on your personal computer, allowing you to use Proton VPN services for enhanced online privacy and security.
</p>

<h2>Download Proton VPN</h2>


![image](https://github.com/kavismith/VPN-Setup/assets/143667203/528083d4-55de-43a5-8dba-be331094b670)

After successfully signing up and creating your username and password for Proton VPN on your personal computer, the next step is to sign in to your Proton VPN account on the Remote Desktop. Once signed in, follow these steps to proceed:

- Within the Remote Desktop session, open a web browser.

- Visit the Proton VPN website and locate the "Sign In" option.

- Enter your Proton VPN username and password that you previously created on your personal computer.

- Once signed in, navigate to the "Downloads" section on the Proton VPN website.

![image](https://github.com/kavismith/VPN-Setup/assets/143667203/81706cc3-7a1b-411a-9f24-9eb82a837ca6)

Here, you can download the Proton VPN client software tailored for your Remote Desktop operating system.

By following these steps, you will be able to access and download the Proton VPN client on your Remote Desktop, allowing you to configure and use Proton VPN for enhanced online privacy and security within your Remote Desktop session.

</p>
<p>
 
</p>


<h2>Download Proton VPN</h2>


![image](https://github.com/kavismith/VPN-Setup/assets/143667203/8ae1bac3-0368-48ae-9575-f8717fdaef09)


</p>
<p>
After clicking the "Download" button on the Proton VPN website, go to your "Downloads" folder in your file directory on your Remote Desktop. Locate the downloaded Proton VPN installer file, open it, and then follow the provided steps to install Proton VPN on your Remote Desktop.
</p>
