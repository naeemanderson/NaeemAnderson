<h1>Hi, I'm Naeem, an <a href=https://www.linkedin.com/feed/>IT Professional</a>☺</h1>

<h2>👨‍💻 Information Technology Projects:</h2>

- <b>osTicket (Help Desk Ticketing System)</b>
  - [osTicket: Prerequisites and Installation](https://github.com/NaeemAnderson/osticket-prereqs)
  - [osTicket: Post-Installation Configuration](https://github.com/joshmadakorcc/post-install-config)
  - [osTicket: Ticket Lifecycle Examples](https://github.com/joshmadakorcc/ticket-lifecycle)
- <b>Microsoft Azure</b>
  - [Configuring On-premises Active Directory within Azure VMs](https://github.com/joshmadakorcc/configure-ad)
  - [Network Security Groups (NSGs) and Inspecting Network Protocols](https://github.com/joshmadakorcc/azure-network-protocols)

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Access the VM through Remote Desktop.
- install PHP Manager
- install the Rewrite Module
- install VC_redist.x86.exe
- install MySQL 5.5.62
- install HeidiSQL
- complete instillation

<h2>Installation Steps</h2>

<p>
<img <img width="1470" alt="Screen Shot 2025-03-11 at 10 01 53 AM" src="https://github.com/user-attachments/assets/1e6d460d-943c-4f23-add2-f55ca2a04073" />

</p>
<p>
Access the VM through Remote Desktop.

After logging in to the VM (osticket-vm), download the osTicket-Installation-Files.zip file and unzip it on your desktop. You’ll find a folder labeled osTicket-Installation-Files.
</p>
<br />

<p>
<img <img width="1470" alt="Screen Shot 2025-02-22 at 6 45 52 PM" src="https://github.com/user-attachments/assets/2538888e-e7cc-4c7a-bb01-94924336a5e4" />



</p>
<p>
 install PHP Manager for IIS (PHPManagerForIIS_V1.5.0.msi)

</p>
<br />

<p>
<img <img width="1470" alt="Screen Shot 2025-02-22 at 6 46 37 PM" src="https://github.com/user-attachments/assets/45295106-d0a2-4ea6-99f5-c087d0d35048" />

</p>
<p>
In the osTicket-Installation-Files folder, run the rewrite_amd64_en-US.msi installer to install the Rewrite Module.
<br />

<img width="1470" alt="Screen Shot 2025-02-22 at 7 40 09 PM" src="https://github.com/user-attachments/assets/03913fff-8804-4477-95cc-50baed85b356" />

From the “osTicket-Installation-Files” folder, install VC_redist.x86.exe.


<img width="1470" alt="Screen Shot 2025-02-22 at 7 41 08 PM" src="https://github.com/user-attachments/assets/c0edffe7-ad59-4ad5-ada4-8887ecaeb8e9" />

From the “osTicket-Installation-Files” folder, install MySQL 5.5.62 (mysql-5.5.62-win32.msi)

<img width="1470" alt="Screen Shot 2025-02-22 at 8 23 40 PM" src="https://github.com/user-attachments/assets/51c296f5-4400-4700-9bbf-2cb69c56b319" />

From the “osTicket-Installation-Files” folder, install HeidiSQL.
Open Heidi SQL
Create a new session, root/root
Connect to the session
Create a database called “osTicket”

<img width="1470" alt="Screen Shot 2025-02-22 at 8 27 17 PM" src="https://github.com/user-attachments/assets/73a95e1d-750c-47ab-821f-e856fa4cb416" />

  Proceed with the osTicket setup in your browser.

MySQL Database: osTicket

MySQL Username: root

MySQL Password: root

Once you've entered the details, click "Install Now" to complete the osTicket installation
