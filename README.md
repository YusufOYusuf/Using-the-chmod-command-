<h1>Using the chmod command</h1>


<h2>Description</h2>
In this lab, I learned to use the chmod command. Since Linux file permissions are based on DAC, you can use the chmod command to set permissions for any file or directory you own. One way to set permissions for a folder or file is with symbolic notation for user (u), group (g), and other (o).
<br />



<h2>Environments Used </h2>

- <b>Kali GNU Linux/Rolling</b> 

<h2>Utilities and Language </h2>

- <b>Terminal</b>

<h2>Program walk-through:</h2>

<p align="center">
From the left sidebar navigate to terminal<br/>
<img src="https://i.postimg.cc/VkZqhMbT/Screen-Shot-2023-02-23-at-4-31-37-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
  
  
<br />
Execute the following command "chmod g=r out.txt" to give the members of the group permission to read the file, but not write and execute<br>
<img src="https://i.postimg.cc/s28t3vbH/Screen-Shot-2023-02-23-at-4-37-38-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />



<br />
Execute the "chmod u=rwx,g=rx,o= out.txt" to give yourself full access to out.txt, let group members read and execute, and deny all access to anyone else  <br>
<img src="https://i.postimg.cc/1zJ3Bcnn/Screen-Shot-2023-02-23-at-4-45-50-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />



