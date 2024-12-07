# Managing Microsoft Entra ID Identities

## Objective

This is the first in a series of labs for Azure Administrators. In this lab, you learn about users and groups. Users and groups are the basic building blocks for an identity solution.
This lab requires an Azure subscription. Your subscription type may affect the availability of features in this lab. You may change the region, but the steps are written using East US.

*Ref 1: Architecture diagram*
 ![image](https://github.com/user-attachments/assets/fcc1f05d-7d59-48ff-825b-ab15d56bca9a)


### Job Skills Learned

- Creating and configure user accounts.
- Creating groups and add members.

### Tools Used

- Azure portal - https://portal.azure.com

## Steps

Task 1: Create and configure user accounts

In this task, you will create and configure user accounts. User accounts will store user data such as name, department, location, and contact information.
Create a new user
1.	Select Users, then in the New user drop-down select Create new user.
2.	Create a new user with the following settings (leave others with their defaults). On the Properties tab notice all the different types of information that can be included in the user account.
![image](https://github.com/user-attachments/assets/40a4507e-80ee-467c-be14-df8efa189ee1)
 
3.	Once you have finished reviewing, select Review + create and then Create.
4.	Refresh the page and confirm your new user was created.
![image](https://github.com/user-attachments/assets/8d4ceab9-6b5c-45ee-b5b2-3b6727b228d2)


Invite an external user
1.	In the New user drop-down select Invite an external user.
![image](https://github.com/user-attachments/assets/2b90544b-1697-4bee-ba2d-ae34c2ae28bd)

2.	Move to the Properties tab. Complete the basic information, including these fields.
![image](https://github.com/user-attachments/assets/b36b6f43-b6ed-4297-a193-a4e339b9bc35)

3.	Select Review + invite, and then Invite.
4.	Refresh the page and confirm the invited user was created. You should receive the invitation email shortly.
![image](https://github.com/user-attachments/assets/76c586fe-6cb9-4b4d-b5e6-8da038e3c374)


## Task 2: Create groups and add members

In this task, you create a group account. Group accounts can include user accounts or devices. These are two basic ways members are assigned to groups: Statically and Dynamically. Static groups require administrators to add and remove members manually. Dynamic groups update automatically based on the properties of a user account or device. For example, job title.

1.	In the Azure portal, search for and select Microsoft Entra ID. In the Manage blade, select Groups.
2.	Take a minute to familiarize yourself with the group settings in the left pane.
o	Expiration lets you configure a group lifetime in days. After that time the group must be renewed by the owner.
o	Naming policy lets you configure blocked words and add a prefix or suffix to group names.
3.	In the All groups blade, select + New group and create a new group.
![image](https://github.com/user-attachments/assets/1b84171b-b90d-4819-aa08-ce8a5574b968)

4.	Select No owners selected.
5.	In the Add owners page, search for and select yourself (shown in the top right corner) as the owner. Notice you can have more than one owner.
![image](https://github.com/user-attachments/assets/c3ce35ed-80ec-4ebe-9281-b5ab7c41afb6)

6.	Select No members selected.
7.	In the Add members pane, search for and select the az104-user1 and the guest user you invited. Add both of the users to the group.
![image](https://github.com/user-attachments/assets/d4d00192-f9f5-4ca3-9724-9bc195b197bd)
  
8.	Select Create to deploy the group.
9.	Refresh the page and ensure your group was created.
![image](https://github.com/user-attachments/assets/9b428ec0-456a-4095-9228-8fac4cb12bc3)
 
11.	Select the new group and review the Members and Owners information.
![image](https://github.com/user-attachments/assets/16524e78-1489-471a-ac91-6fce262af70a)



