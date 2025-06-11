## Lab Objective: Implementing a Scalable, Highly Available Website in AWS

Objective:

To design, deploy, and validate a scalable, highly available, and secure web application using core AWS services. This lab aims to simulate real-world cloud architecture that ensures performance, reliability, and fault tolerance using AWS best practices.

---
Learning Outcomes:

By the end of this lab, students/participants will be able to:

- Provision EC2 instances to serve web content.

- Configure Elastic Load Balancing (ELB) for distributing incoming traffic.

- Set up Auto Scaling Groups to dynamically adjust capacity based on demand.

- Implement a highly available database using Amazon Dynamo DB (Multi-AZ)

- Configure Route 53 for domain name resolution and routing policies.

- Apply security best practices using Security Groups, IAM roles, and AWS WAF/Shield.

- Monitor system performance using Amazon CloudWatch and configure alerting.

- Test fault tolerance by simulating instance or AZ failures.

---

- Compute: Amazon EC2 with Auto Scaling

- Load Balancing: Elastic Load Balancer (ELB)

- Database: Dynamo DB (Multi-AZ) or Aurora

- DNS & Traffic Routing: Amazon Route 53

- Security: Security Groups, IAM, AWS WAF, AWS Shield

- Monitoring: Amazon CloudWatch (logs, alarms, dashboards)

---

Lab Tasks Overview:

 1. Launch a basic EC2 web server in one Availability Zone.

 2. Register and configure a domain in Route 53.

 3. Deploy a Load Balancer in front of EC2 instances.

 4. Set up Auto Scaling based on CPU utilization.

 5. Launch a multi-AZ Dynamo DB database for backend storage.

 6. Apply Security Groups and IAM roles for secure access.

 7. Enable WAF/Shield to protect against common web threats.

 8. Use CloudWatch to monitor metrics and set alerts.

 9. Perform failure testing by terminating instances or disabling AZs to verify HA.

---
![alt text](Scalable-Application.jpg)
---

Deliverables: 

- Deployed infrastructure (web app + Dynao DB + CDN + Auto-scaling).

- Screenshots of each step and CloudWatch metrics.

- Written summary/report explaining each AWS component used and its role.

- Fault tolerance test results.


