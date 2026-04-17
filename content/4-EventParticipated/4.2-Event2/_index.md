---
title: "Event 2"
date: 2024-04-04
weight: 1
chapter: false
pre: " <b> 4.2. </b> "
---

# Event Report: “Cloud Mastery Series #2: DevOps Fundamentals & Infrastructure”

### Event Objectives

* **Systematize IaC Knowledge:** Provide a comprehensive overview of Infrastructure as Code and practical implementation using Terraform on AWS.
* **Master Container Orchestration:** Introduce Kubernetes (K8s) architecture and modern application management in Cloud-native environments.
* **Optimize Operations with Elixir:** Explore Elixir/Erlang solutions as a unified tool for high-availability and fault-tolerant DevOps systems.
* **Hands-on Practice:** Demonstrate infrastructure and application deployment techniques through live demos.

### Speakers

* **Thinh Nguyen** – FCAJ Cloud Engineer Trainee (IaC & Terraform Expert).
* **Bao Huynh** – Junior Cloud Native Developer at Endava / Founder of ITea Lab (Kubernetes Expert).
* **Nguyen Ta Minh Triet** – R&D Member at ITea Lab / SAP Developer Intern at Bosch GSV (Elixir Expert).

### Key Highlights

#### Infrastructure as Code (IaC) with Terraform
* Analyzed the shift from "ClickOps" to infrastructure automation to eliminate human error and increase consistency.
* Compared AWS CloudFormation, AWS CDK, and Terraform (HCL).
* Deep dive into State file management and core execution commands (`plan`, `apply`, `destroy`).

#### Kubernetes (K8s) Architecture
* Addressing the challenge of managing thousands of containers: self-healing and auto-scaling.
* Detailed breakdown of components: Control Plane, Worker Nodes, Pods, Deployments, and Services.
* Introduction to supporting tools: **Helm** (package management) and **K9s** (intuitive terminal UI).

#### Elixir in DevOps Pipeline
* The power of the BEAM virtual machine in handling millions of concurrent connections with minimal overhead.
* The "Let it crash" philosophy: Utilizing Supervision Trees for self-healing systems without manual intervention.
* **Case study:** Transitioning from Serverless (Node.js/Lambda) to Elixir reduced costs from \$30,000/month to under \$400/month.

### Key Takeaways

* **Automation Mindset:** Infrastructure is no longer just individual servers but versionable and reusable blocks of code.
* **Efficient Cluster Management:** Identified Amazon EKS as the optimal enterprise solution to offload the management burden of the Kubernetes Control Plane.
* **Fault-Tolerance:** Designing systems for self-recovery (as seen in Elixir) is more critical than attempting to write "perfect" bug-free code.
* **Cost Optimization:** Selecting the right technology (like Elixir for parallel computing tasks) can deliver superior ROI compared to traditional models.

### Professional Application

* **EduTrust Project Strategy:** Implement Terraform to standardize AWS infrastructure, ensuring seamless replication across environments (Dev/Staging/Prod).
* **Application Deployment:** Consider containerizing EduTrust microservices using Docker and orchestrating them with Kubernetes to ensure high availability.
* **Performance Improvement:** Further explore event-driven architecture through Elixir’s process handling to apply to real-time features.

### Event Experience

The workshop series offered a very logical journey from infrastructure to application:
* **In-depth Content:** Beyond theory, the Terraform and K9s demos provided a clear vision of a Cloud Engineer's daily operations.
* **Multi-dimensional Perspectives:** The combination of mainstream technologies (AWS, K8s) and high-performance niche solutions (Elixir) expanded my solution-design thinking.
* **Networking:** Opportunity to engage with speakers possessing real-world experience from major corporations like Endava and Bosch.

### Lessons Learned

* Modernizing infrastructure must be accompanied by IaC to ensure speed and security.
* Kubernetes is the "Operating System" of the cloud, but requires auxiliary tools like Helm and K9s for effective management.
* Do not hesitate to experiment with new languages/platforms (like Elixir) if they solve cost and reliability problems better than conventional solutions.

### Event Photos

![event2](3.jpg?width=600px&height=400px)

### Summary

The event series provided a solid knowledge framework for modern DevOps. This serves as a vital foundation for me to professionally build and operate the **EduTrust** project, ensuring it is ready for large-scale cloud challenges.