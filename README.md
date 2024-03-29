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
- We can also give other users access to her OneDrive files and email

  ![image](https://github.com/chriskhawaja/office365admin/assets/153021794/aa87166b-bd65-437b-a26e-a9c323ec97f1)

  If we go back to our Active Users, we can create a new user by selecting the "Add user" option

  ![image](https://github.com/chriskhawaja/office365admin/assets/153021794/65c7b559-ddab-47fe-b552-56d7d05fef15)

- We can begin to create an account for Jane Doe
- We can assign her a license and choose what applications should be available with the license
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

Each user on Office 365 will have their own inbox
  - However, users that are part of the same team can have access to a shared mailbox
  - External customers can send information to the email of the shared mailbox
  - Members of the group can also communicate to other members within the shared mailbox
  - Having a shared mailbox allows department spefic questions to go to a particular mailbox

Under Teams and Groups, select "Shared Mailboxes"
  - Click "Add a shared mailbox"
  - Create a name and an email for the shared mailbox
  - Select "Save changes" when done
![image](https://github.com/chriskhawaja/office365admin/assets/153021794/66074964-aeb7-43aa-8281-9bdde2cb97a2)

Our newly created Engineering Department has a shared mailbox
  - Now it's time to add members
      - On the right side of the screen, under members, select "edit"
  ![image](https://github.com/chriskhawaja/office365admin/assets/153021794/a1a4de1c-b2a9-4afe-96e9-baf37cfc7f48)
![image](https://github.com/chriskhawaja/office365admin/assets/153021794/ca95c098-6e58-4764-a63f-e2d36ef98260)

To see if our shared mailbox is properly configured, click on the rows of dots in the top left corner, and select "Outlook"
  - You can see that I am part of the Engineering Department group
  - Additionally, I have a shared mailbox, along with my normal mailbox for myself

    
    ![image](https://github.com/chriskhawaja/office365admin/assets/153021794/f1c89017-143d-4f6a-84e7-ec55701837d4)
    ![image](https://github.com/chriskhawaja/office365admin/assets/153021794/ec61e2cb-71ec-4c5f-a8f2-61c900a824a4)

    In Office 365, we can also troubleshoot Microsoft Outlook email messages
      - End-users might have trouble receiving or sending messages, and Microsoft Exchange can help us trace these messages
      - Under the Admin center, we will select "Exchange"
      - From there, on the left side, we will click "Mail flow", and select "Mail trace"
      - Select the "Start a trace" button
      - On the right, enter the sender and recipient email address to trace the message
      - Select "Search"
      - Select the message under results to bring up any diagnostic information
          - If there is an issue, select "Report Message" at the bottom to submit to Microsoft for Analysis
       
    ![image](https://github.com/chriskhawaja/office365admin/assets/153021794/04830c1a-e640-4749-9509-fee2547e3144)
        ![image](https://github.com/chriskhawaja/office365admin/assets/153021794/4ad91c62-598a-4c4b-a5b2-02376dc88c3a)
![image](https://github.com/chriskhawaja/office365admin/assets/153021794/9814a815-2051-47f6-bb24-a16cc495a260)

We will now access Microsoft Sharepoint
  - Sharepoint can be used to recover deleted emails from end-users
  - To do this, click "More features" when on Sharepoint, and select "Open" under User profiles
  - Select "Manage user profiles"
  - Search the name of the user who wants to recover their deleted document
  - Click with your cursor under account name and select "Manage personal site"
  - Under Site Collection Administration, select "Recycle bin"
  - If end-user emptied the recycle bin, select "second-stage recycle bin" at the bottom
  - Deleted document should appear and now be able to be restored

    ![image](https://github.com/chriskhawaja/office365admin/assets/153021794/68bac8f1-bf5d-4336-9e7e-ffba4edf3ccd)
    ![image](https://github.com/chriskhawaja/office365admin/assets/153021794/474d3bca-8a32-48b9-954d-432062cb5cf5)
    ![image](https://github.com/chriskhawaja/office365admin/assets/153021794/8652bb75-dc1c-49f0-9ea4-caf17160ffc1)

Under SharePoint, you can also create different sites for departments
  - These sites are where departments can communicate and collaborate on different projects
  - Click "Active sites" and then select "Create"
  - From there, we can choose the site name and address, assign owners and members, and include information about the site
  - As administrators, we can help edit department sites if need be
      - We can also delete sites for departments
  - Within the site, departments can also access OneNote for detailed information that can be edited by site members 
![image](https://github.com/chriskhawaja/office365admin/assets/153021794/aefb0d50-300f-48d8-83d8-56248b009ea1)
    ![image](https://github.com/chriskhawaja/office365admin/assets/153021794/e5950843-7653-45ae-8d93-a9fd63546648)
![image](https://github.com/chriskhawaja/office365admin/assets/153021794/9a8673fb-f9d6-456a-8162-4e579d36a6f6)
![image](https://github.com/chriskhawaja/office365admin/assets/153021794/15759041-4b74-42ea-a9e1-9aed868ca785)
![image](https://github.com/chriskhawaja/office365admin/assets/153021794/6526bde5-9ebe-4edc-a566-4ad61db092c3)




**** Picture used at the top of personal project is not mine (taken from Google)
