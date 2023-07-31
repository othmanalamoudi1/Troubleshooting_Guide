# Troubleshooting Guide

In this repository, I intend to showcase a variety of IT support issues that I encountered during my time at Providence Health and Services. I will also outline the step-by-step troubleshooting processes that I utilized to resolve these issues.
## Issue: Unable to login to the computer due to incorrect username and/or password

Often, employees are confident that they are entering the correct username and password, yet they still encounter login difficulties. To troubleshoot this problem, the following steps are taken:

- Verify Account Status: Firstly, I check whether their account is locked. If it is, I proceed to unlock it using the Active Directory system.

- Check Domain Usage: If the account is not locked, the next common issue is users inadvertently logging into a different domain. For example, in Providence Health and Services, we had multiple domains for different states (Washington, Oregon, South California, North California, and Texas). Occasionally, the computer login page displays the incorrect domain for certain employees. In such cases, I advise them to input their username as "domainname/their username" in the Username section. This solution resolves the majority of login issues.

- Check CAPS LOCK and NUM LOCK: In rare instances, I have come across situations where employees are unable to log in due to the CAPS LOCK and NUM LOCK being activated. I always remind them that, for security purposes, the login system is case-sensitive. Therefore, it is essential to ensure that both the CAPS LOCK and NUM LOCK keys are in the correct state while entering their login credentials.
## Issue: Employee unable to login to their VM remotely from their personal devices.


To resolve this problem, I follow these steps:

- Inquire About Previous Access:

    I start by asking the employee if they have ever been able to log in remotely before. This helps determine whether the issue is recent or if they have never had remote access.

  - If they have never had remote access, I proceed to check Active Directory to verify if they have been granted the privilege to log in remotely. If not, I advise them to contact their manager and request the necessary permissions.

  - If they previously had remote access and are now facing issues, I proceed with the following steps.

- Check Citrix Workspace Installation:

  I confirm that Citrix Workspace is installed on their personal device. If not, I guide them through the installation process or provide the necessary resources for installation.

- Verify Correct Site and Domain:

  Next, I ensure that they are accessing the correct site for their domain. If our organization has multiple domains, it's essential to use the appropriate one for their login.

## Issue: The user is unable to find the shared drive on their computer.

Steps to troubleshoot and resolve the issue:

1. Verify Previous Access:
- Firstly, ask the user if they have ever had access to the shared drive before.
  
2. Check with Colleagues:
 - If the user previously had access, inquire if any of their colleagues currently have access to the shared drive

3. Obtain the Shared Drive Path:

- If a colleague has access, ask the user to request the shared drive path address from them. The colleague can find it by:
    - Right-clicking on the shared drive.
    - Selecting "Properties."
    - Locating the "Network path" or "Location" field containing the sharing drive path address.
    - Once they have the path, ask them to copy it and share it with the user.

4. Map shared Drive:

- Next, instruct the user to follow these steps to map the shared drive on their computer:
    - Go to File Explorer.
    - Right-click on "This PC."
    - Select "Map network drive."
    - Paste the path address in the "Folder" section.
    - Click "Finish" to complete the mapping process.



