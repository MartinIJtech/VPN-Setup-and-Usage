# VPN-Setup-and-Usage
<p align="center">

<img width="855" height="318" alt="image" src="https://github.com/user-attachments/assets/a0e30f13-6364-4578-8bd2-85bdc75d3ffe" />


</p>

<h1> VPN Setup And Installation</h1>

This tutorial outlines the installation of a A VPN (Virtual Private Network).<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)

- Personal Computer

- Proton VPN

- Windows App



<h2>What is a VPN</h2>

 A VPN (Virtual Private Network) creates a secure, encrypted tunnel for your internet traffic, hiding your online activity, identity, and location by routing it through a remote server. It gives the appearance that you're browsing from the server's location instead of your own.

 


<h2>Installation Steps</h2>

<p>

<img width="2295" height="1547" alt="image" src="https://github.com/user-attachments/assets/e0e3a6d7-6c5a-4ccf-9e7d-a23729ae52dc" />



</p>

<p>

 To begin you are going to start on your actual computer and go to your web browser. On your web browser go to whatismyipaddress.com to observe and confirm what your IP address is.

</p>

<br />

<p>

<img width="2310" height="1800" alt="image" src="https://github.com/user-attachments/assets/2e627378-1cea-41eb-94ca-096c561c63fa" />


</p>

<p>

<img width="2313" height="1592" alt="image" src="https://github.com/user-attachments/assets/635d5786-116e-4018-a9bd-021503126c81" />



</p>

<p>

 After getting your IP address along with the additional information of the city and country it would be best to use a note pad or your computers note feature to keep track of it so we can come back to it later.

<br />

<p>

</p>

<br />

<p>

<img width="2307" height="1800" alt="image" src="https://github.com/user-attachments/assets/9be768d1-3565-4e7d-85f2-7b6cee03369b" />


<img width="2308" height="1800" alt="image" src="https://github.com/user-attachments/assets/b1fbaae0-b3f3-4fe7-81d9-ab796ba35eb3" />


<img width="2307" height="1800" alt="image" src="https://github.com/user-attachments/assets/be4abefb-a955-44e5-8c2e-2ee043d3e894" />


<img width="2309" height="1800" alt="image" src="https://github.com/user-attachments/assets/76d5e09a-871d-4b13-956d-7105cf0bcf75" />

</p>

<p>

 Now go into your browser and log into azure so we can create a virtual machine. These next steps would help in completing your virtual machine 
- Create a new resource group and name it whatever’s best for you. 
- In the region put a different location( in this example its going to be Africa)
- In the image category put windows 11 or 10 if it is there.
- Choose a size to run the azure account in
- Then pick a username and password that you want.
- Click next in the bottom section until your able to create the VM


<br />

<p>
<img width="1150" height="667" alt="Screenshot 2025-12-28 at 2 59 41 PM" src="https://github.com/user-attachments/assets/37be67e6-e020-40fc-b41b-00a0f2a67c58" />


</p>

<p>

 After refreshing the page you should see your new Virtual machine available to click. Once you click it on the right hand side of the page you will see your ip address for the VM, make sure you copy it as we will be using it in the following sections

<br />

<p>

<img width="2307" height="1743" alt="image" src="https://github.com/user-attachments/assets/76d611b4-7117-4874-97e7-239dc8845400" />


<img width="2306" height="1279" alt="image" src="https://github.com/user-attachments/assets/1ce76ee4-5710-448c-9e88-073a6b82fd70" />


<img width="2297" height="1286" alt="image" src="https://github.com/user-attachments/assets/00d1b9ce-8602-4728-a5ac-ff799ec079d7" />

</p>

<p>

 With the virtual machine created go into the windows app and click the plus int he corner to add a new PC. In the Pc name section place the Ip address for the virtual machine and whatever name works for you in th friendly name section. Add the new pc and connect to it with the username and password you created.

<br />

<p>

<img width="1157" height="900" alt="Screenshot 2025-12-30 at 8 38 35 PM" src="https://github.com/user-attachments/assets/1ab7cba1-abea-444d-a4c7-610eaad48fbb" />


<img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/6f530d05-b985-43b3-a95f-53fe5fdefb1b" />


<img width="2306" height="1800" alt="image" src="https://github.com/user-attachments/assets/b59797e5-9a94-42eb-9b7a-60f697d940ad" />

</p>

<p>

 Now you should be logged into the virtual machine, use  the Microsoft edge web browser to visit whatismyipaddress.com to get the new information thats specific to the virtual machine. After getting all the information including the ip address, the region, country etc, Copy it down so we can reference it later. 

<br />

<p>

<img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/0583fce7-6141-4db3-96d8-fde05e4f0fd1" />


<img width="2311" height="1800" alt="image" src="https://github.com/user-attachments/assets/b49d879a-8d2a-472e-aa39-e8edd94d9886" />


<img width="2307" height="1701" alt="image" src="https://github.com/user-attachments/assets/9c7ead03-3467-4530-ab6a-a9d58c17686f" />


<img width="2307" height="1800" alt="image" src="https://github.com/user-attachments/assets/5474ff53-31a6-4e5d-abba-9e8d7a749b99" />


</p>

<p>

 Now going back to your actual computer we are going to sign up for the free version of Proton VPN. After the signup process is completed go back into the virtual machine and log into Proton VPN there. Once signed in download proton VPN to your computer(mac or windows).

<br />

<p>

<img width="2309" height="1669" alt="image" src="https://github.com/user-attachments/assets/631cb5ef-89a1-4104-ab1b-3dc8f51c0bac" />


<img width="2308" height="1744" alt="image" src="https://github.com/user-attachments/assets/adba4735-ab11-41c0-8cff-706dab3d1177" />

</p>

<p>

 Once downloaded on the VM desktop open Proton VPN. You should see boxes where you should put your sign in info.

  Because this is the free version of Proton VPN you have less control over the servers you get assigned to but overall you should be placed in the fastest available server.

<br />

<p>

<img width="2311" height="1693" alt="image" src="https://github.com/user-attachments/assets/6475e52a-a106-487e-ad5b-238a63d36455" />


<img width="2304" height="1648" alt="image" src="https://github.com/user-attachments/assets/aed67cbd-3f3c-4de1-b57d-31256f7eaf8a" />


</p>

<p>

 Based on the server that Proton Connected you to you should see a change in IP addresses location. We can double check this by visiting Whatismyipadress.com to verify the change.

  Using the paper or document we used to write down all the IP address info we can also go back and see how our personal info changed through out the course of this demonstration. Continue to test for yourself different websites and see what differences you notice.

<br />

<p>

<h2>Things you can do with a VPN</h2>

</p>

<p>

Now that you have a VPN there is a lot of interesting things you can do with it besides just adding security to your browsing.


- Access global streaming libraries: Watch shows on Netflix, Hulu, or BBC iPlayer as if you were in the UK, US, or other countries. 

- Watch region-locked live sports: Bypass blackouts to catch local games or access international broadcasts. 

- Unblock social media & apps: Access sites like YouTube, Facebook, or WhatsApp in restrictive regions. 

- Get better deals on flights, hotels, subscriptions, and online purchases by connecting to servers in different countries.

- Avoid price discrimination: Stop websites from showing you higher prices based on your location. 


<br />

<p>

<h2>Conclusion</h2>

</p>

<p>

In conclusion, using a VPN is a simple way to stay safer and more private online. It helps protect personal information by hiding your IP address and securing your internet connection, especially on public Wi-Fi. Knowing how to use a VPN properly makes it easier to browse the internet with more confidence. Here is a simplified check list of the demonstration just incase you need a refresher.

1. (Create Virtual Machine in Azure)

-Browse to https://whatismyipaddress.com/ FROM WITHIN YOUR OWN MACHINE and take note of this in a text file

-Create a Resource Group

-Create a Windows 10 Virtual Machine in another geographic location (try a different country)

-Log into the VM with Remote Desktop

-Browse to https://whatismyipaddress.com/ and take note of this in a text file

2. (Sign up for ProtonVPN and test the VPN connection)

-On your actual computer, sign up for the free version of Proton VPN https://account.protonvpn.com/signup?plan=free&language=en  

-Back within your VM, download the Proton VPN client

-Login to the VPN (https://account.protonvpn.com/login) and choose a VPN server in yet another country (such as Japan)

-Browse to https://whatismyipaddress.com/  and take note of this in a text file

Try browsing to Google, Disney, and/or Amazon and see if there is anything different about the sites in relation to the location of your VPN server. For example, the language or URL may be different.

<br />

<p>

<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

<p>

Lorem ipsum dolor

<br />

<p>

<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

<p>

Lorem ipsum dolor

<br />

<p>

<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

<p>

Lorem ipsum dolor

<br />

<p>

<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

<p>

Lorem ipsum dolor

<br />

<p>

<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

<p>

Lorem ipsum dolor

<br />

<p>

<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

<p>

Lorem ipsum dolor

<br />

<p>

<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

<p>

Lorem ipsum dolor

<br />

<p>

<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

<p>

Lorem ipsum dolor

<br />

<p>

<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

<p>

Lorem ipsum dolor

<br />

<p>

<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

<p>

Lorem ipsum dolor

<br />

<p>

<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

<p>

Lorem ipsum dolor

<br />

<p>

<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

<p>

Lorem ipsum dolor

<br />

<p>

<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

<p>

Lorem ipsum dolor

<br />

<p>

<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

<p>

Lorem ipsum dolor

<br />

<p>

<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

<p>

Lorem ipsum dolor

<br />

<p>

<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

<p>

Lorem ipsum dolor

<br />

<p>

<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

<p>

Lorem ipsum dolor

<br />

<p>

<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

<p>

Lorem ipsum dolor











































