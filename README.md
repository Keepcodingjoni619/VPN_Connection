# VPN_Connection

<p>🛜 VPNs is a way to connect/link devices on the network together across an insecure network allowing to encapsulate and encrypt data between each other</p>
<p>This is done usually from your home</p>
<p>VPN from home ---------------- VPN Server allowing to send traffic through a private network</p>

![VPN_02](https://github.com/Keepcodingjoni619/VPN_Connection/assets/82996237/96e89afc-6699-4981-82c7-e6c3d3a42d9a)

<h5>VPN Setup</h5>
<ol>
  <li>Install Azure</li>
  <li>Create virtual machine inside Azure</li>
  <li>Use Proton VPN through Azure</li>
  <li>Establish connection remotely</li>
</ol>

<h2>Create A Virtual Machine through Azure</h2>

![06](https://github.com/Keepcodingjoni619/VPN_Connection/assets/82996237/1bc7eca7-7514-4c94-82d8-64e482d1dc95)

<h2>Establish connection using Remote Desktop Connection</h2>
<p>In Azure we assigned VM to be located in London</p>
<p>Connect the VM public IP</p>

![vpn03](https://github.com/Keepcodingjoni619/VPN_Connection/assets/82996237/084a4d25-ea07-44a9-bf5d-05ec03b30b65)

<h2>Download Proton VPN and establish connection</h2>

![vpn04](https://github.com/Keepcodingjoni619/VPN_Connection/assets/82996237/b3ed66d1-6937-4283-be9b-16b6c659d284)

<h2>Check to see if VPN remote is connected</h2>

![vpn05](https://github.com/Keepcodingjoni619/VPN_Connection/assets/82996237/7679bcd5-c9db-49e3-95db-e45c4588e57e)

<ol>
  <li>VM (no vpn): 20.77.67.219 London</li>
  <li>VM (w / vpn): 37.19.205.193 New York</li>
</ol>
