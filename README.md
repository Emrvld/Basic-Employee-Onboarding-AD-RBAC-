# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
So Northstar Medical group had a huge HIPAA violation where they  was no structure. In correspondence with no Active Directory, no Organizational Units or access for the different departments and secuirty groups within the company. Terrible Role base access control, meaning employee's had different roles or access within their departments. The risk for being audited was high, and since their was no centralized system to organize everything and manage the access. Everything was done manually which was the cause of a lot of mistakes and human error.

## Solution Overview
I built a active directory system that created 4 OU's that was able to organize and structure the different departments. Within that the domain NMG.com was created and houses all of the users and their information. Securely splitting them up within access of their respective security groups. The company's Role based access control is now secured and everything is automatic, if a user is transferred to a different department, there will not need to be many manaual changes, once a user is placed in a new OU, and its corresponding security group all of that access will be transferred correctly and smoothly.

## Video Walkthrough
[Add your video walkthrough link placeholder here. You will record this tomorrow and update this link so visitors can see a live demonstration of your lab environment.]

## Tools Used
* Windows Server
* Active Directory Domain Services
* VirtualBox
* UTM
* RBAC
* GitHub

## Project Timeline
* Day 1: Domain creation and domain controller promotion
* Day 2: Organizational unit and security group design
* Day 3: User provisioning and RBAC implementation
* Day 4: Incident response and resolution (NMG-0047)
* Day 5: Documentation and case study packaging

## Key Accomplishments
* Built NMG.com domain from scratch
* Was able to successfully create all the user accounts and OU's and security groups.
* Being able to fully understand and comprehend the structural need of why North star Medical group needed this upgrade and why fixing the issue was very important to the protection of the company internally and externally. 
