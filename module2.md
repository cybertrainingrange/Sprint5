
# Module 2: SIEM Architecture and Components



|  ![SIEM](https://drive.google.com/uc?export=view&id=1yLRT7nI3qqsHuDdnb-i8KptK6jfDVOIg)  |
| ----------------------- |





SIEM (Security Information and Event Management) architecture in AWS involves the integration of various components to collect, analyze, and respond to security events and incidents.  

**Here are the key components and their roles in an AWS SIEM architecture.**

- Data Sources: These are the various AWS services and resources that generate security-relevant logs and events. Examples include AWS CloudTrail for API activity logs, Amazon VPC Flow Logs for network traffic, Amazon GuardDuty for threat intelligence, and AWS Config for resource configuration changes. Data sources provide the raw data needed for analysis and monitoring.
- Log Collection: Log collection tools or services gather and aggregate logs from different data sources. In AWS, you can use services like Amazon CloudWatch Logs, AWS CloudTrail, and AWS Config to collect and centralize logs. These services allow you to stream logs to a central repository for storage and analysis.
- Log Storage: The logs collected from various data sources need to be stored securely for long-term retention and analysis. AWS offers services like Amazon S3 (Simple Storage Service) and Amazon Glacier for scalable and durable log storage. You can choose the appropriate storage service based on your retention and access requirements.
- Log Parsing and Normalization: Logs collected from different sources may have different formats and structures. Log parsing and normalization tools or services help standardize the logs into a common format, making it easier to analyze and correlate events. You can use tools like AWS Lambda functions or third-party log parsing tools to perform this task.
- Threat Detection and Analysis: This component involves the use of security analytics tools and techniques to analyze the collected logs and detect security threats and anomalies. AWS services like Amazon GuardDuty, AWS Security Hub, and third-party solutions can perform real-time analysis using machine learning, anomaly detection, and rule-based detection mechanisms.
- Incident Response and Automation: When security events or incidents are detected, an incident response process is triggered. Automation tools and playbooks can help streamline and automate incident response activities. AWS provides services like AWS Systems Manager Automation, AWS Step Functions, and AWS Lambda for automating incident response workflows and executing predefined actions.
- Visualization and Reporting: The SIEM architecture should include components for visualizing and reporting security events and incidents. This can include using tools like AWS CloudWatch Dashboards, AWS QuickSight, or third-party visualization tools to create dashboards, reports, and metrics for better visibility into the security posture of your AWS environment.
- Integration with Security Orchestration, Automation, and Response (SOAR): SOAR platforms integrate with SIEM solutions to enable automated incident response, coordination of security workflows, and integration with third-party security tools. By integrating SIEM with a SOAR platform, you can enhance your incident response capabilities and streamline security operations.

![SIEM](https://drive.google.com/uc?export=view&id=1JJz-dCCwIliXfE2CB0bzIbX-gzYx71jt) 



It's important to note that the specific components and their configuration may vary based on the SIEM solution you choose, as well as the requirements and complexities of your AWS environment. Selecting the right combination of services, tools, and solutions that align with your security needs is crucial for an effective SIEM architecture in AWS.


## Technical Documentation 🤖

[SIEM Architecture and Components](https://docs.google.com/document/d/1zTjHRLag1NCbmbPf59g8oWAgamhB6Tfkbh3LnbbCb2U/edit?usp=drive_link)


## 🔗 Authors: 👐
### Alena 👩‍💻
<p>
  <a href="https://www.linkedin.com/in/alena-puzach-b999801a7/">
    <img src="https://skillicons.dev/icons?i=linkedin" />
  </a>  
    <a href="https://github.com/alenapuzach">
    <img src="https://skillicons.dev/icons?i=github" />
  </a>
</p>

### Volha 👩‍💻
<p>
  <a href="https://www.linkedin.com/in/volha-t-59b7725b/">
    <img src="https://skillicons.dev/icons?i=linkedin" />
  </a>  
    <a href="https://github.com/voliatalatynik">
    <img src="https://skillicons.dev/icons?i=github" />
  </a>
</p>






