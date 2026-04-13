**Company Name**  
FastCart.Inc

**Company Overview**  
FastCart is a mid-size E-commerce company that sells products online to consumers. These include physical goods such as clothing, electronics, and household items. All necessary information is stored in Amazon AWS for hosting infrastructure. That includes processing customer orders, storing personal information, and handling online payments using third party payment processors.

**Company Size**  
80 total employees, with 8 IT professionals on staff.

**Technology Stack**  
Cloud Platform: Amazon AWS for hosting infrastructure  
OS: Linux servers for backup servers, Windows laptops and desktops for employee endpoints  
Database: MySQL  
Logging/Monitoring: Splunk

**Key Assets**

- Passwords  
- Customer database (PII and payment data)  
- Web applications  
- Administrative accounts  
- Employee Endpoints (laptops/desktops)

**Data Types:**

- Personally Identifiable Information  
- Email addresses  
- Payment information

**User Access**

- Customers access company through the website  
- Employees access the internal systems through login portal  
- Admins have elevated privileges

**Security Assumptions and Posture**

- No MFA implemented  
- No centralized IAM policy  
- No endpoint detection (EDR)  
- Weak passwords  
- Limited logging review process

FastCart.Inc operates with a basic security level. The organization lacks advanced security controls such as Multi-factor Authentication, centralized identity management, and endpoint detection response.  
