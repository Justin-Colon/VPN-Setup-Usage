<p align="center">
<img src="https://cdn.pixabay.com/photo/2019/11/19/08/44/map-4636843_640.jpg"alt="osTicket logo"/>
</p>

<h1>VPN Setup and Usage</h1>
This tutorial outlines VPN setup and usage from within a vm in a different geographical area and my very own machine. <br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Azure Account 
- Region Selection
- Resource Group
- Virtual Network
- VM Image
- VM Size
- Authentication Method
- Storage Type
- Public IP Address(Optinal)
- Inbound Port Rules

<h2>VPN setup and Usage Steps</h2>

<p>
<img src="https://github.com/Justin-Colon/VPN-Setup-Usage/blob/ac1b2f558e614fb2c2a489b783baa399a0eaa826/vpn/vpn1%20.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First I start by configuring my windows 10 vm with the basics. 
</p>
<br />

<p>
<img src="https://github.com/Justin-Colon/VPN-Setup-Usage/blob/9cc93bada740c7d6b72a3077a48616211f52cef5/vpn/vpn3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here is where we search https://whatismyipaddress.com/ just to get the IP address of our personal computer.
</p>
<br />

<p>
<img src="https://github.com/Justin-Colon/VPN-Setup-Usage/blob/5bd98f4418a52f75fce756bec083167f16cf5d49/vpn/vpn4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I did the samething in our VM this time and as you can see our IP address and region is different from our actual computer. We have established a tunnel between our computer and the vm using a non vpn connection. 
</p>
<br />

<p>
<img src="https://github.com/Justin-Colon/VPN-Setup-Usage/blob/74e8d6a079e848329393848d0471de1999570fa2/vpn/vpn5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now I have gone ahead and downloaded proton vpn onto my vm only.
</p>
<br />

<p>
<img src="https://github.com/Justin-Colon/VPN-Setup-Usage/blob/7d37defcbd12b33be0da4ee42d1ee9620c9a821f/vpn/vpn7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once proton vpn aplication is fully downloaded onto my vm I will click connect which then the system will place me anywhere in the world with one of their free auto selected servers.
</p>
<br />

<p>
<img src="https://github.com/Justin-Colon/VPN-Setup-Usage/blob/dfc9cade11a926a3a6d99e0f8fd6434677159714/vpn/vpn8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Looks like I got placed in Japan, awesome!
</p>
<br />

<p>
<img src="https://github.com/Justin-Colon/VPN-Setup-Usage/blob/bf01e8f8025c26c8345391307e6fd24e2b66e2e1/vpn/vpn9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I used the same website that used previously to grab the IP address of my computer and my vm to discover my now new IP address using a vpn connection since I have been placed on a Japan server. 
</p>
<br />

<p>
<img src="https://github.com/Justin-Colon/VPN-Setup-Usage/blob/ac765766c32dbaec4cd56bcfb1d6d1b1dd627628/vpn/vpn10.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now to recap this project. I created a vm with the purpose of observing vpn traffic. I started the project by establishing a tunnel between my actual operating machine and the azure vm that I created from scratch. From that tunnel I had two different IP addresses. Then I created a tunnel on my vm with the server in Japan using a vpn connection which allowed me to use the Japan server as if I physically was behind a desk in Japan using the internet. Proton vpn connections are used commonly because it hides your actual IP address which encrypts your internet traffic, which then also allows you to bypass censorship and geo blocks. 
</p>
<br />



