---
title: "Create Your Own VPN Server"
categories:
tags:
  - In-Progress Projects
---

In this guide, I will show you how to create your own free (kind of) VPN server.

I used this [video][vpn-server-guide] as a guide on how to create your own VPN server.

<h2>Things we will be using:</h2>
 <ul>
  <li><a href="https://www.raspberrypi.org/products/raspberry-pi-3-model-b/">Raspberry Pi 3</a></li>
  <li><a href="https://www.noip.com/">No-IP</a></li>
  <li><a href="https://www.pivpn.io/">PiVPN</a></li>
</ul> 

<h3>Why are you using a Raspberry Pi?</h3>
We are using a Raspberry Pi because it will act as our server that hosts and runs everything we need to create our own VPN server.

<h3>What is No-IP?</h3>
According to this [article][noip-article] from No-IP:

<i>The No-IP Free Dynamic DNS service takes your dynamic IP address and makes it act as though it is static by pointing a static hostname to it and checking every 5 minutes for changes to your IP address.
If your IP address changes, our Dynamic Update Client updates your hostname with the current IP address. 
This means you can run a server from home and access your computer, or IP camera remotely.</i>

<h3>Why do we need No-IP?</h3>
[No-IP][noip] is needed because most people do not have static IP's set up at home which means our public IP is dynamic (constantly changing).
We would need to manually update our hostname file to reflect the public IP each time it changes or we could use a service like No-IP which can automatically update our hostname file to reflect the current IP address instead.

<h3>What is PiVPN?</h3>
[PiVPN][pivpn] Is a very simple script that helps you install [OpenVPN][openvpn] on a Raspberry Pi.
While simple, PiVPN is still very flexible, manageable and secure.

<h3>What is OpenVPN? Matter of fact, what even is a VPN?</h3>
[OpenVPN][openvpn] is a free (personal license, not commerical) and open source Virtual Private Network (VPN)



















[vpn-server-guide]: https://www.youtube.com/watch?v=HxpgbZZk1Rw&feature=youtu.be
[noip-article]: https://www.noip.com/support/knowledgebase/what-does-no-ip-do/
[noip]: https://www.noip.com/
[pivpn]: https://www.pivpn.io/
[openvpn]: https://openvpn.net/


