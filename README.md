<h1>Setting up a firewall with pfsense on a Debian machine</h1>

<h2>Environments used:</h2>

- Oracle VirtualBox
- Debian
- pfsense

<h2>Project walk-through:</h2>

<p align="center">
I made a Debian vm to install pfsense onto and attached the network adapter 1 to NAT: <br/>
<img src="https://i.imgur.com/8ABfoDR.jpg" height="80%" width="80%"/>
<br />
<br />
<p align="center">
Attached the second adapter to the internal network: <br/>
<img src="https://i.imgur.com/7sZaLe0.jpg" height="80%" width="80%"/>
<br />
<br />
<p align="center">
I then made a second Debian vm to connect to the pfsense firewall and connected this one's first network adapter to the internal network: <br/>
<img src="https://i.imgur.com/9Rq55OU.jpg" height="80%" width="80%"/>
<br />
<br />
<p align="center">
On the *host* Debian vm I configured the pfsense LAN settings: <br/>
<img src="https://i.imgur.com/HRIccwu.jpg" height="80%" width="80%"/>
<br />
<br />
<p align="center">
On the *client* Debian vm, I went to the pfsense webconfigurator at 192.168.1.1, to choose the basic firewall settings: <br/>
<img src="https://i.imgur.com/o3a909h.jpg" height="80%" width="80%"/>
<br />
<br />
<p align="center">
followed the setup wizard: <br/>
<img src="https://i.imgur.com/2CSXLzf.jpg" height="80%" width="80%"/>
<br />
<br />
<p align="center">
<br/>
<img src="https://i.imgur.com/ZXTPZMN.jpg" height="80%" width="80%"/>
<br />
<br />
<p align="center">
<br/>
<img src="https://i.imgur.com/UuPynpQ.jpg" height="80%" width="80%"/>
<br />
<br />
<p align="center">
<br/>
<img src="https://i.imgur.com/or1VPr3.jpg" height="80%" width="80%"/>
<br />
<br />
<p align="center">
<br/>
<img src="https://i.imgur.com/Er5sc9h.jpg" height="80%" width="80%"/>
<br />
<br />
<p align="center">
<br/>
<img src="https://i.imgur.com/QbE5Fna.jpg" height="80%" width="80%"/>
<br />
<br />
<p align="center">
Successful login message on the *host* client:<br/>
<img src="https://i.imgur.com/lfcFQiF.jpg" height="80%" width="80%"/>
<br />
<br />
</p>
