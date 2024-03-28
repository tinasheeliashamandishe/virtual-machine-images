<h1>Virtual machine Images</h1>

<h2>Description</h2>
<br />
This lab will create a virtual machine. Create an Image out of the virtual machine, and use that Images to create more identical virtual machines,<br />
There are two types of virtual machines. Specialized virtual machines and Generalized vrtual machines.<br />
In Specialized virtual machines the information about specific users and machine informaition(from the primary machine) is retained.<br />
In Generalized virtual machines the information about specific users and machine informaition(from the primary machine) is not retained.<br /><br />

This lab will create a virtual machine, install Internet Information Services on it. Create an image of that virtual machine and use that image to create another virtual machine.<br />


<h2>Environments Used </h2>

- <b>Microsoft Azure</b>

<h2>Lab walk-through:</h2>

<p align="center">
<h4>Step 1</h4>
Create a Vitual machine and install IIS.<br/>
<img src="https://i.imgur.com/kuHEwPw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Access IIS through a web browswer.<br/>
<img src="https://i.imgur.com/3PFrg20.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>
<br />

<h4>Step 2</h4> 
Create an image from the VM, and specify if the image is Specialized or Generalized.<br/>
<img src="https://i.imgur.com/x52dmZ3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>
<br />

<h4>Step 3</h4>
<br />
Create a virtual machine using the image you just created.<br/>
<img src="https://i.imgur.com/a59kqKq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>
<br />
Access IIS through a web browswer.br/>
<img src="https://i.imgur.com/uBmwpbR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/><br/>


You have successfully created a VM image abd used it in creating a seperate Virtual machine.
