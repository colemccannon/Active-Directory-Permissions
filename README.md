# Active-Directory-Permissions
![Active Directory](https://github.com/Coleyboii/Active-Directory-Lab/blob/main/Screenshot%202024-05-18%20165031.png)

## Outline

In this project, I downloaded a Windows 10 ISO and a Server ISO, and put them into Virtualbox. 
I used the server as a domain controller to house active directory with two network adapters.
One was connected to the outside internet, and one to the Virtualbox internal network. 
I assigned IP addressing for the internal network, then set up Active Directory, NAT, routing and DHCP.
I then ran a Powershell script that created 1,000 users in Active Directory.
Then, I joined the other virtual machine to the domain and named it Client1 and logged in with a user account.

This was a nice lab to set up a basic corporate network, and I will repeat it many times to make this skill second-nature.
