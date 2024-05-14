# Application-Security-DevSecOps-Project


## Application Security Assessment README

## Overview
This document outlines the methodology and objectives for conducting application security assessments within the company. The process includes conducting a critical asset list, followed by in-depth analysis and implementation of security measures for one selected application.

## Reason for Conducting Application Security Assessments
Application security assessments are crucial for safeguarding sensitive data, ensuring regulatory compliance, and fortifying defenses against cyber threats. By identifying vulnerabilities and implementing robust security measures, the company can effectively mitigate risks and bolster its overall cybersecurity posture.

## Process

**Critical Asset List**: I conducted a comprehensive critical asset list for three applications to identify and prioritize key assets within the company's infrastructure.

![Critical Asset List](https://github.com/AgbiiEmmanuel/Application-Security-DevSecOps-Project/assets/159606680/774a6927-187e-447c-aa3a-e506e3c124a4)

**Selection of Focus Application**: I Choosed one application for detailed analysis and security enhancement based on the critical asset list findings.

**Data Flow Diagram and High-Level Diagram**: I Developed a detailed data flow diagrams and high-level architectural diagrams to visualize the application's infrastructure and data flow patterns.

**Threat Modeling**: I Employed tools such as MITRE ATT&CK and other threat modeling techniques to identify potential threats and vulnerabilities throughout the application's lifecycle.

Inherent Risk Assessment: I Performed an inherent risk assessment to evaluate the initial risk level associated with the selected application, considering its vulnerabilities and potential impact.

**Cyber Kill Chain**: I Formulated a Cyber Attack Kill Chain to delineate the stages of a potential cyber attack and identify potential points of intervention and defense.

**AWS EC2 Infrastructure Diagram**: I Created an AWS EC2 infrastructure diagram, detailing the region, VPC, subnet, security group, and Elastic Block Store (EBS) configuration to ensure a secure cloud environment.

![AWS EC2](https://github.com/AgbiiEmmanuel/Application-Security-DevSecOps-Project/assets/159606680/7f089b59-74e9-48ba-abe6-414859f86c30)

**Security Measures Implementation**: I Designed and implemented a range of security measures, including access controls, continuous monitoring, threat detection or intrusion detection systems, and incident response plans, to enhance the application's security posture.

![Security controls](https://github.com/AgbiiEmmanuel/Application-Security-DevSecOps-Project/assets/159606680/37f8bf18-2499-43dc-ba34-80fcce72f89a)


## Here's an explanation of why each of those security controls was implemented for the application, along with why email was attached as part of the process:

**Amazon GuardDuty**: Amazon GuardDuty is a threat detection service that continuously monitors for malicious activity and unauthorized behavior within AWS environments. It was implemented to provide real-time threat detection and automated responses to potential security threats, helping to protect the application from various attacks such as account compromise, privilege escalation, and malicious activity.

**AWS Security Hub**: AWS Security Hub provides a comprehensive view of security alerts and compliance status across AWS accounts. By aggregating findings from various security services and third-party tools, Security Hub helps to prioritize and remediate security issues efficiently. It was implemented to centralize security monitoring and streamline the management of security incidents for the application.

**Amazon SNS (Simple Notification Service)**: Amazon SNS is a fully managed messaging service that enables the sending of notifications and alerts to a variety of endpoints, including email, SMS, and HTTP. It was implemented to facilitate timely communication of security alerts and notifications to relevant stakeholders, ensuring that security incidents are promptly addressed and mitigated.

**Amazon Inspector**: Amazon Inspector is an automated security assessment service that helps identify security vulnerabilities and compliance issues in EC2 instances and applications. It was implemented to conduct automated security assessments of the application's infrastructure and code, providing insights into potential security risks and vulnerabilities that need to be addressed.

**Lambda Functions**: AWS Lambda allows for the execution of code in response to events, such as changes in AWS resources or incoming data. Lambda functions were implemented to automate security response actions based on predefined rules and triggers, enabling rapid incident response and mitigation without manual intervention.

**Amazon CloudWatch**: Amazon CloudWatch provides monitoring and observability for AWS resources and applications. It was implemented to monitor the performance, logs, and metrics of the application and its underlying infrastructure, facilitating proactive detection and resolution of security issues and anomalies.

**Email**: Email was attached as part of the security controls implementation to serve as a notification mechanism for security alerts and findings generated by the aforementioned security services. Upon detection of security threats or vulnerabilities, alerts are sent via email to designated recipients, enabling prompt action and remediation.

### By implementing these security controls and integrating email notifications, the application benefits from continuous monitoring, threat detection, and automated response capabilities, ensuring robust security posture and timely incident response.

# Usage

This document serves as a comprehensive guide for security analysts and stakeholders involved in the application security assessment process. It outlines the steps to be followed and the objectives to be achieved at each stage of the assessment, facilitating a systematic approach to improving application security.

