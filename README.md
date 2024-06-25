# Active-Directory-Permissions
![Active Directory](https://github.com/colemccannon/Active-Directory-Permissions/blob/main/Screenshot%202024-06-25%20141441.png)

## Outline

In this project, I practiced both share and NTFS permissions in Active Directory.
Using the Domain Controller and the Client from my first Active Directory lab, I created two test users, two groups and two folders.
One group was for "employees" which contained both users, and one group was called "BAD" which contained one of the two users.
This can emulate an employee who is under investigation, and should not have permission to private resources.
I created a "public" and "private" folder within the share, and gave the employees access to the share, but used NTFS permissions to deny the "BAD" group access to "private".
I then logged in with both test users on my Windows computer to see how the permissions blocked the "BAD" user from seeing the private folder.

I will continue playing with these virtual machines to familiarize myself with Active Directory.
