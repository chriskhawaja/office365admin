![image](https://github.com/chriskhawaja/office365admin/assets/153021794/774d50df-ec9c-45c8-b44a-53672e14cbc2)



<h2>Learning Microsoft Office 365 Administration</h2>

<p>
Once you are in the Administration Center of Office 365, click "Users" and select "Active Users"
  - 

  
![image](https://github.com/chriskhawaja/office365admin/assets/153021794/07dfdc42-8a95-4578-bb3e-50432f5bb64b)
![image](https://github.com/chriskhawaja/office365admin/assets/153021794/7d943fbe-ed6e-4ebe-abdb-faa48b9031d1)

Lets practice resetting Adele's password to her Office 365 account 
- Select "Reset password" under her name
  - We can choose to automatically create a password for her, create a password on our own, force her to change the password upon logging on, and emailing ourselves her login information
    
![image](https://github.com/chriskhawaja/office365admin/assets/153021794/c22e54c4-b18b-4772-be65-dabbab50e7f4)

Additionally, if we go back to Adele's profile, we can block her from signing-in 
- This is important if we believe that a user's account has been compromised
- To accomplish this action, we select the "Block sign-in" button, which is right next to "Reset password"
  
![image](https://github.com/chriskhawaja/office365admin/assets/153021794/1f7f5545-bf58-4ee5-93d8-3990e8703acb)

We can also delete Adele's profile by selecting the "Delete user" option on her profile
- Deleting her account will unassign her license and make it available to others
- We can also give other users access to her OneDrive files and emal

  ![image](https://github.com/chriskhawaja/office365admin/assets/153021794/aa87166b-bd65-437b-a26e-a9c323ec97f1)

  If we go back to our Active Users, we can create a new user by selecting the "Add user" option

  ![image](https://github.com/chriskhawaja/office365admin/assets/153021794/65c7b559-ddab-47fe-b552-56d7d05fef15)

- We can begin to create an account for Jane Doe
- We can add assing her a license and choose what application should be available with the license
- We can assign Jane Administrator acces or configure her as a standard user (no access)
- We can configure Jane's work information
  ![image](https://github.com/chriskhawaja/office365admin/assets/153021794/9ea9f407-9e91-4841-bd20-521b259e78ae)
  ![image](https://github.com/chriskhawaja/office365admin/assets/153021794/3e82591b-ef2d-452d-a1f8-fa992913ce98)
![image](https://github.com/chriskhawaja/office365admin/assets/153021794/8735d7f8-c45c-4ada-a24d-aeeae5576b90)
![image](https://github.com/chriskhawaja/office365admin/assets/153021794/b1db9d0f-7381-4fea-bf05-1931bfea9bc4)

- Once we select "finish", Jane Doe's account has been created, and she has been assigned the proper license
![image](https://github.com/chriskhawaja/office365admin/assets/153021794/55701fa5-a962-4cf6-9899-b41f341162fd)

If we want to create a Team in Office 365, we click "Teams and Groups" on the left 
  - Select "Active Teams and Groups"
  - Select "Add a Team"
  - Begin to create the name of the team, assign owners, and add members 
  - Create the email address of the team and select "Add team"
    ![image](https://github.com/chriskhawaja/office365admin/assets/153021794/7680f5d0-a437-4057-8a22-6476494f43c6)
![image](https://github.com/chriskhawaja/office365admin/assets/153021794/2e15c51d-9fe2-4090-a2d5-799b263d83ba)
![image](https://github.com/chriskhawaja/office365admin/assets/153021794/71fbed8f-4faf-46c1-81ee-dd6e5d74d6f5)
- We can now see the Engineering Department team under Active Teams and Groups
  - If we click on the team, we wil be able to see the owners and members of the team, general information, and be able to change settings of the Team
![image](https://github.com/chriskhawaja/office365admin/assets/153021794/63a3ad9b-3198-4b69-aa2b-582522f5afe1)

- We will now block this connection by going back to Microsoft Azure, and typing in "Network Security Groups" into the search bar
- On the left, we can click the "Inbound Security Rules" tab, and click the add button - this tab is selected because we want to block any ICMP traffic coming into VM2, hence the word "inbound"
- Be sure to select ICMP as the protocol and the deny option
  - ICMP stands for Internet Control Message Protocol, and is the protocol that is used when using the ping command
- Lastly, select the add button, and the security rule will be created

![image](https://github.com/chriskhawaja/azure-network-protocols/assets/153021794/ca61784b-48d5-4c3d-86fc-db57538c90a9)
- Now, we can observe that any traffic being sent to VM2 is being blocked

  ![image](https://github.com/chriskhawaja/azure-network-protocols/assets/153021794/25ae8002-6238-4782-bf84-f59863d0d4a3)
- We can reverse this process by going back to our NSG for VM2, selecting the rule we created, and clicking the allow button under ICMP
- Be sure to press "save" and the rule will be created

  ![image](https://github.com/chriskhawaja/azure-network-protocols/assets/153021794/7d98f982-45f0-4928-8eb8-1af9450b4d3b)
- We can see the replies from VM2 coming back after we changed the inbound rule 

![image](https://github.com/chriskhawaja/azure-network-protocols/assets/153021794/dcaf8831-58c9-4eee-8774-a0f187424535)
- Utilizing SSH, we can also acces the Linux terminal of VM2 from VM1
  - To access VM2 using VM1, be sure to input SSH Username@IP Address
    - The username and IP address of the VM that you are trying to access
   
![image](https://github.com/chriskhawaja/azure-network-protocols/assets/153021794/dcec2035-05ec-472a-8a8f-12645b2a06fc)
- Once we filter for Remote Desktop Protocol traffic, we can see the inundation of traffic
  - This is because we are literally using RDP to access our VM
 
  ![image](https://github.com/chriskhawaja/azure-network-protocols/assets/153021794/20ff0139-ebf7-4af2-b4e8-7e5ab8ac5f94)
- After visiting different websites on our VM, we can see all the DNS information on Wireshark
- Additionally after utilizing the command "ipconfig /displaydns", we can see that our cache is full of information

  ![image](https://github.com/chriskhawaja/azure-network-protocols/assets/153021794/4f6a5650-6f0a-46c3-ba8b-602a661b59c9)
- To flush our DNS cache, we can use the "ipconfig /flushdns" command
  - This command is really important when users are experiencing a multitude of DNS issues
 
![image](https://github.com/chriskhawaja/azure-network-protocols/assets/153021794/67e1cf2c-17f3-4859-8201-12f1d177169b)
- To view our DHCP and DNS servers, we can type the command "ipconfig /all" into command prompt

  ![image](https://github.com/chriskhawaja/azure-network-protocols/assets/153021794/e20a6d00-e5f7-4516-9a66-daf11afcfbaf)
- DHCP traffic can be analyzed by using the "ipconfig /release" and "ipconfig /renew" commands
  - The release command will tell our DHCP server to get rid of our current IP address, which was given to us via DHCP
  - The renew command will give us a new allocated IP address that is dynamically given via DHCP
  - Note that when you use these commands, your connection may be lost since we have "released" the VM's current IP address
 
  ![image](https://github.com/chriskhawaja/azure-network-protocols/assets/153021794/cad81990-28a6-4ddd-aea6-5eee091ed677)
  - You can now see in Wireshark, the steps of DHCP release and renewal
    - The DORA process highlights how a Client and DHCP Server communicate
      - Discovery, Offer, Request, and Acknowledge 
      
