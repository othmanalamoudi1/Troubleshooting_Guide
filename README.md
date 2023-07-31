# Troubleshooting Guide

In this repository, I intend to showcase a variety of IT support issues that I encountered during my time at Providence Health and Services. I will also outline the step-by-step troubleshooting processes that I utilized to resolve these issues.
## Issue: Unable to login to the computer due to incorrect username and/or password

Often, employees are confident that they are entering the correct username and password, yet they still encounter login difficulties. To troubleshoot this problem, the following steps are taken:

- Verify Account Status: Firstly, I check whether their account is locked. If it is, I proceed to unlock it using the Active Directory system.

- Check Domain Usage: If the account is not locked, the next common issue is users inadvertently logging into a different domain. For example, in Providence Health and Services, we had multiple domains for different states (Washington, Oregon, South California, North California, and Texas). Occasionally, the computer login page displays the incorrect domain for certain employees. In such cases, I advise them to input their username as "domainname/their username" in the Username section. This solution resolves the majority of login issues.

- In rare instances, I have come across situations where employees are unable to log in due to the CAPS LOCK and NUM LOCK being activated. I always remind them that, for security purposes, the login system is case-sensitive. Therefore, it is essential to ensure that both the CAPS LOCK and NUM LOCK keys are in the correct state while entering their login credentials.
