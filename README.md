# Active Directory Security Monitoring Lab

## Project Status
🚧 Completed

## Objective
Build a Windows Active Directory lab to practice identity management, authentication monitoring, security log analysis, and investigation of suspicious login activities.

## Tools
- Windows Server
- Active Directory Domain Services (AD DS)
- Windows Event Viewer
- PowerShell

## Lab Activities
- Create and manage users and groups
- Configure Active Directory accounts
- Monitor successful and failed logins
- Analyze Windows security events
- Investigate suspicious authentication activity
- Practice basic account security and access control

## Skills Practiced
- Active Directory
- Windows Security
- Identity and Access Management
- Log Analysis
- Threat Detection
- PowerShell

## Documentation
### Lab Summary

This lab simulates common Active Directory identity and authentication security activities in a Windows Server environment.

### Activities Performed

- Created and managed the SOCTest Active Directory user account
- Created the SOC Analysts security group
- Added and removed the user from the security group
- Enabled and disabled the user account
- Performed password reset and account changes
- Generated multiple failed login attempts
- Investigated authentication and account activity using Windows Event Viewer

### Security Events Investigated

| Event ID | Description |
|----------|-------------|
| 4625 | Failed logon attempt |
| 4720 | User account created |
| 4722 | User account enabled |
| 4724 | Password reset attempt |
| 4725 | User account disabled |
| 4738 | User account changed |

### Failed Login Investigation

Multiple failed authentication attempts were intentionally generated for the SOCTest account.

Event ID 4625 was identified in Windows Security logs. The investigation showed multiple failed logon events associated with the test account, demonstrating how a SOC analyst can identify and investigate suspicious authentication activity.

### Key Findings

- Multiple failed logins can indicate suspicious authentication activity.
- Windows Event IDs provide important information for security investigations.
- Active Directory account and group changes can be monitored through Security logs.
- Event Viewer can help SOC analysts investigate identity-related security events.

### Conclusion

This lab provided hands-on experience with Active Directory administration, Windows Security event analysis, identity monitoring, and investigation of suspicious login activity.

## Lab Evidence

### 1. Audit Policy Configuration

![Audit Policy Configuration](IT_Shared_test.png)

### 2. Group Policy Application

![Group Policy Application](IT_Shared_test%201.png)

### 3. Active Directory User Creation

![Active Directory User Creation](IT_Shared_test%202.png)

### 4. Active Directory User Management

![Active Directory User Management](IT_Shared_test%203.png)

### 5. Active Directory Group Management

![Active Directory Group Management](IT_Shared_test%204.png)

### 6. Active Directory Group Membership

![Active Directory Group Membership](IT_Shared_test%205.png)

### 7. Active Directory Account Monitoring

![Active Directory Account Monitoring](IT_Shared_test%206.png)

### 8. Security Event Monitoring

![Security Event Monitoring](IT_Shared_test%207.png)

### 9. Windows Security Log Analysis

![Windows Security Log Analysis](IT_Shared_test%208.png)

### 10. Failed Login Monitoring

![Failed Login Monitoring](IT_Shared_test%209.png)

### 11. Security Log Investigation

![Security Log Investigation](IT_Shared_test%2010.png)

### 12. Account Creation Monitoring

![Account Creation Monitoring](IT_Shared_test%2011.png)

### 13. Account Enable Monitoring

![Account Enable Monitoring](IT_Shared_test%2012.png)

### 14. Password Reset Monitoring

![Password Reset Monitoring](IT_Shared_test%2013.png)

### 15. Account Disable Monitoring

![Account Disable Monitoring](IT_Shared_test%2014.png)

### 16. Account Change Monitoring

![Account Change Monitoring](IT_Shared_test%2015.png)

### 17. Security Event Investigation

![Security Event Investigation](IT_Shared_test%2016.png)

### 18. Security Event Analysis

![Security Event Analysis](IT_Shared_test%2017.png)

### 19. Security Event Review

![Security Event Review](IT_Shared_test%2018.png)

### 20. Security Monitoring Evidence

![Security Monitoring Evidence](IT_Shared_test%2019.png)

### 21. Advanced Security Monitoring

![Advanced Security Monitoring](IT_Shared_test%2020.png)

### 22. Final Security Monitoring Review

![Final Security Monitoring Review](IT_Shared_test%2021.png)

### 23. Final Lab Evidence

![Final Lab Evidence](IT_Shared_test%2022.png)






