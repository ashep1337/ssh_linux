<p align="center">
<img src="ur_in.png"/>
</p>
<br/>
<h1> Secure Shell (SSH) into Linux from Windows 11</h1><br/>
This will outline how to SSH into a linux environment from Windows using your command line<br/>

<h2> Skills Demonstrated</h2><br/>
-Linux<br/>
-SSH<br/>
-Command Line <br/> <br/>
------------------------------------------------------------<br/>
-First we have to install our SSH client on Windows by going to the start menu and typing "optional features" <br/><br/>
-Install "OpenSSH Client" and "OpenSSH Server" this allows the "SSH" command in your terminal window <br/>
<img src="SSH_enable.png"/>
<img src="add_ssh.png"/><br/>
-You will need the IP address of the computer you are attempting to log into. In this instance I am already logged into a linux environment via SSH. <br/>
-Use commands "ifconfig" and "whoami" to find your IP address and username of computer if you do not know. <br/><br/>
<img src="linux_ifconfig_whoami.png"/>
-Now that you have your credentials open windows powershell by going into the start menu and typing "powershell" <br/>
type "ssh user@i.p address" making sure to substitue your username and IP address accordingly <br/><br/>
<img src="logon_ssh.png"/>
Congratulations you are operating a linux computer from your command line in windows! <br/>
