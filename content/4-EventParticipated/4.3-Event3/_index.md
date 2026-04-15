---
title: "Event 3"
date: 2024-04-11
weight: 1
chapter: false
pre: " <b> 4.3. </b> "
---

# Summary Report: "Cloud Mastery Series #3: Security"

### Event Information

- **Event Name:** Cloud Mastery Series #3: Security
- **Time:** 09:00 – 12:00, April 11, 2026
- **Location:** FPTU - Hall Academic A
- **Role:** Attendee

### Event Objectives

- Guide the setup and management of secure traffic within a VPC using Subnets, NAT Gateways, Security Groups, and NACLs.
- Introduce application and network layer protection solutions against web exploits and DDoS attacks.
- Deploy Identity and Access Management (IAM) in accordance with advanced security standards.

### Speakers

- **Lam An Thinh** – DataXight Security Engineer Intern
- **Nguyen Phan Quoc Viet** – Networking on AWS Speaker
- **Lam Tuan Kiet** – DevOps, Network & Application Protection Expert
- **Huynh Hoang Long** – FCAJ Cloud Engineer Ambassador
- **Dang Thi Minh Thu** – FCAJ Cloud Engineer Ambassador

### Key Highlights

#### VPC & Network Security

- **Subnets:** Dividing subnets is akin to deciding the dimensions of a room when constructing a system.
- **NAT Gateway:** An AWS-managed service that allows resources in a Private Subnet to connect to the Internet while preventing reverse connections.
- **Security Group (SG) vs. Network ACL (NACL):** SG operates at instance level and is Stateful; NACL operates at subnet level and is Stateless.

#### Application Protection Layers

- **AWS WAF:** Protects against SQL Injection and XSS attacks.
- **AWS Shield:** Provides Standard (free) and Advanced DDoS protection.
- **AWS Firewall Manager:** Centrally manages security policies across multiple AWS accounts.

#### Identity and Access Management (IAM)

- **Principle of Least Privilege:** Grant only minimum necessary permissions.
- **Governance Tools:** Use SCPs and Permission Boundaries.
- **Credential Security:** Enforce MFA and short-term credentials from STS.

### Key Takeaways

- Zero Trust Philosophy: Always authenticate every connection.
- Layered Design: Deploy security across Instance, Subnet, and Application layers.
- Centralized Management: Use SSO and Firewall Manager for multi-account consistency.

### Practical Applications

- Optimize network segmentation for the EduTrust Project.
- Review and remove redundant IAM permissions.
- Integrate AWS WAF in front of Application Load Balancer (ALB).

### Lessons Learned

- Security by Design: Architect security from the start.
- Stateful vs. Stateless: Key distinction for troubleshooting network connectivity.
- Automation: Use IAM Access Analyzer to detect unintended resource sharing.

### Conclusion

The Cloud Mastery Series #3 workshop provided a solid foundation for designing secure and scalable AWS systems.

