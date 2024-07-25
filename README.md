# Applying-User-Authentication-and-Access-Controls

## Objective
In this lab, I will use the Active Directory Users and Computers utility to create several new users and groups. I will then create a folder structure that aligns with the new groups and assign permissions that restrict user access to each folder based on group membership. Finally, I will verify authentication and access controls by logging in as each user and attempting to access each folder.

### Skills Learned
- Understand how Microsoft’s Active Directory Domain Services can be used to implement an authentication and access control framework.
- Create new user accounts and security groups in a Windows environment.

- Create access control lists to protect objects and folders from unauthorized access in a Windows environment.
- Distinguish Windows Security permissions from Windows Share permissions.
- Configure access controls for a remote file server using Active Directory Security Groups.

### Tools and Software Used
- Active Directory Users and Computers
- PowerShell
- TrueNAS

### Topology
- vWorkstation (Windows: Server 2022)
- pfSense-office (FreeBSD: pfSense)
- pfSense-dc (FreeBSD: pfSense)
- DomainController01 (Windows: Server 2019)
- FileServer01 (FreeBSD: TrueNAS)


### Lab Overview
STEP 1 of this lab has three parts, which should be completed in the order specified.
 
- I will create users and groups in a Windows environment.
- I will create folders and assign security permissions.
- I will test your security controls.

STEP 2
- You will create additional shared folders for your security groups on a TrueNAS file server.



<h2>Program walk-through:</h2>

## STEP 1
### Part 1: Create Users and Security Groups

<p align="center">

</p>

### Part 2: Create Folders and Configure Security Permissions
<p align="center">

</p>


### Part 3: Verify Authentication and Access Controls
<p align="center">

</p>



## STEP 2
### Part 1: Create an SMB Share

<p align="center">

</p>

### Part 2: Create Shared Folders and Configure ACLs
<p align="center">

</p>


### Part 3: Verify Access Controls
<p align="center">

</p>
