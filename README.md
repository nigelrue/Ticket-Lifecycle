<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tuttorial will outline the lifecycle of a ticket from end-user creation to agent resolution within the osTicket ticketing system.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>
<img src="https://i.postimg.cc/NG6NpyLw/temp-Image7a-S9z-U.avif" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 1: Navigate to the homepage: "localhost/osTicket" and click on Open A New Ticket.
</p>
<br />

<p>
<img src="https://i.postimg.cc/rmLHw5zQ/temp-Image-UJ8k7q.avif" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 2: Enter in the contact information using the information from User 1 that was created in the previous lab <a href="https://github.com/nigelrue/post-install-config">osTicket Post Install</a> and choose a Help Topic.
</p>
<br />

<p>
<img src="https://i.postimg.cc/L6q3Gn8X/temp-Imageieyi-Hu.avif" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 3: Enter in an Issue Summary and a breif description of the ticket. Click Create Ticket.
</p>
<br />

<p>
<img src="https://i.postimg.cc/5yj9sc1H/temp-Image6-I9-ILl.avif" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.postimg.cc/6qSWSH5M/temp-Imagesi-G1-KY.avif" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 4: Create a second ticket using user 1 again and a third ticket using user 2.
</p>
<br />

<p>
<img src="https://i.postimg.cc/5yfKJ1j0/temp-Image-S3laxn.avif" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 5: Navigate back to the homepage by typing "local/osTicket/scp/index.php" into the browser and login using User 1's information.
</p>
<br />

<p>
<img src="https://i.postimg.cc/CLzHqzy0/temp-Imagei-A0lqe.avif" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.postimg.cc/MKN0bqxQ/temp-Image26kobj.avif" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 6: Select the first ticket that we created earlier, "Entire mobile website is down". Observe how the ticket creation process is setup from the user's perspective.
</p>
<br />

<p>
<img src="https://i.postimg.cc/rwhDC95Y/temp-Imagequa0-VI.avif" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 7: Update the Priority. Change from Normal to Emergency. Add notes explaining the reason for changing the priority. Click Update.
</p>
<br />

<p>
<img src="https://i.postimg.cc/VvRfsYRH/temp-Imaget-HN1-Jv.avif" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 8: Assign the ticket to a specific agent. In this case, Patrick Mahomes. Click Assign. 
</p>
<br />

<p>
<img src="https://i.postimg.cc/1zwZ5mRc/temp-Image-OCi-N6-R.avif" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 9: Update the SLA Plan. Select SEV-A and create a note explaining the reason for the update.  
</p>
<br />

<p>
<img src="https://i.postimg.cc/XvpkwqBd/temp-Image-J3-Kj-Ja.avif" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 10: Assign the ticket to the appropriate department, in our case "System Administrators" and leave a note to explain the reason for this update.   
</p>
<br />

<p>
<img src="https://i.postimg.cc/NFJ07sH2/temp-Image3-ZCLke.avif" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 11: Post a reply explaining the course of action used to resolve the ticket. Change ticket status to "Resolved" and click Post Reply.   
</p>
<br />

<p>
<img src="https://i.postimg.cc/vBWMXW4V/temp-Image-Bsm-Dxz.avif" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.postimg.cc/xjxjZdXc/temp-Image-EFMEV8.avif" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.postimg.cc/d3wFfLCS/temp-Image-Sf52-E3.avif" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 12: Repeat steps 6-11 to resolve the other two tickets that were created.
</p>
<br />

<p>
<img src="https://i.postimg.cc/Wz8VcT6p/temp-Image8-Senoc.avif" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 13: The ticket dashboard should be cleared of all support tickets if all of the steps were completed correctly.
</p>
<br />

