# Active-Directory-Configuration


<h1>Active-Directory-CONFIGURATION</h1>

<img src="https://imgur.com/2MAimNF.png" height="80%" width="80%" alt="diagram"/>



<h2>Description</h2>
In the Simulation below, We will : <br>
    <b> 1. Deploy Virtual Machines</b><br>
    <b> 2. Configure DNS</b><br>
    <b> 3. Configure NAT</b><br>
    <b> 4. Configure DHCP</b><br>
    <b> 5. Auto Add 100 users using Powershell Scripting(....In Progress)</b><br>    
<br />


<h2>Environments Used </h2>

- <b>Windows Server 2019</b>
- <b>Windows Host PC</b>

<h2>Program walk-through:</h2>

<p align="center">
1. Install the Virtual Machines and Deploy them. Change Adapter Settings to communicate both with Internal and External Network <br/>

<img src="https://imgur.com/5f9QSEx.png" height="80%" width="80%" alt="diagram"/>
<br />
<img src="https://imgur.com/F3WVrx5.png" height="80%" width="80%" alt="diagram"/>
<img src="https://imgur.com/Cz1jLqr.png" height="80%" width="80%" alt="diagram"/>
<br /><br />

2. Configure the Domain Controller :<br />
     Changed Server name to DC (Domain Controller)<br />
     Assigned the Server an IP address<br />
     Loopback address to the server<br />
     The server itself is the DNS Server!<br />
 <br/>
<img src="https://imgur.com/jzdf5i2.png" height="80%" width="80%" alt="set up"/>
<br />
<br />


3. Install Domain Services and apply configurations: <br/>
<img src="https://imgur.com/lANoz5M.png" height="80%" width="80%" alt="set up"/>
<img src="https://imgur.com/0fJleHF.png" height="80%" width="80%" alt="set up"/>
<img src="https://imgur.com/5BVzdSk.png" height="80%" width="80%" alt="set up"/>
<br />
<br />


4. Create an OU (Organizational Unit) to put an Admin Account <br/>
<img src="https://imgur.com/hS66YUC.png" height="80%" width="80%" alt="set up"/>
<br />
<br />

5. Install NAT. Setup Routing <br/>
<img src="https://imgur.com/JYGe70b.png" height="80%" width="80%" alt="set up"/>
<img src="https://imgur.com/O4sSppD.png" height="80%" width="80%" alt="set up"/>
<br />
<br />

6. Install DHCP. Establish scope for 100 users. Configure DHCP accordingly. Configure DC as Router and Default Gateway :   <br/>
<img src="https://imgur.com/BaK779d.png" height="80%" width="80%" alt="set up"/>
<img src="https://imgur.com/UUgkHK1.png" height="80%" width="80%" alt="set up"/>
<img src="https://imgur.com/KoFenoz.png" height="80%" width="80%" alt="set up"/>
<img src="https://imgur.com/gx31nmp.png" height="80%" width="80%" alt="set up"/>
<img src="https://imgur.com/gx31nmp.png" height="80%" width="80%" alt="set up"/>
<br />
<br />



8. Adding 100 users using Powershell ..... in Progress <br/>
<img src="https://imgur.com/PGj1Afd.png" height="80%" width="80%" alt="set up"/>
<br />
<br />

<br />
This Concludes The AD Configuration Project!
NOTE: You can add onto this and make it more complex, or use these methonds to automate other tasks!  <br/>
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
