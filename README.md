# Google Cybersecurity Certificate Project: Analyze a Vulnerable System for a Small Business
### Scenario
I am a newly hired cybersecurity analyst for an e-commerce company. The company stores information on a remote database server, since many of the employees work remotely from locations all around the world. Employees of the company regularly query, or request, data from the server to find potential customers. The database has been open to the public since the company's launch three years ago. As a cybersecurity professional, you recognize that keeping the database server open to the public is a serious vulnerability.

I am tasked with completing a vulnerability assessment of the situation to communicate the potential risks to decision makers at the company. I need to create a written report that explains how the vulnerable server is a risk to business operations and how it can be secured.

## Vulnerability Assessment Report
### System Description

The server hardware consists of a powerful CPU processor and 128GB of memory. It runs on the latest version of Linux operating system and hosts a MySQL database management system. It is configured with a stable network connection using IPv4 addresses and interacts with other servers on the network. Security measures include SSL/TLS encrypted connections.

### Scope
The scope of this vulnerability assessment relates to the current access controls of the system. The assessment will cover a period of three months, from June 20XX to August 20XX. NIST SP 800-30 Rev. 1 is used to guide the risk analysis of the information system.
### Purpose
The database contains personal identifiable information of customers. A breach in this data may lead to customer’s private information being exposed and exploited. This event will lead to damages to the company’s reputation and as well as heavy fines from regulatory authorities. 
### Risk Assessment
![image](https://github.com/user-attachments/assets/4a6316e9-62a0-49d3-97dc-26ddc5dfbd34)

### Approach
Risks that were measured considered the data storage and management procedures of the business. Potential threat sources and events were determined using the likelihood of a security incident given the open access permissions of the information system and the international workforce. The severity of potential incidents were weighed against the impact on day-to-day operational needs.

### Remediation Strategy
To mitigate access risks and ensure the integrity of the database server, it is essential to implement a comprehensive security framework. This includes enforcing strong authentication protocols, such as complex password policies and multi-factor authentication (MFA), to prevent unauthorized login attempts. Role-based access control (RBAC) should be used to enforce the principle of least privilege, ensuring that users only have access to the data and resources necessary for their role. Additionally, IP allow-listing should be configured to restrict database access to trusted corporate networks, reducing exposure to external threats. Regular auditing and monitoring of user activities will further enhance visibility and early detection of potential security breaches. To ensure business continuity, a secondary backup database should be established to maintain operations in case the primary database is compromised or becomes unavailable.

