## Site-to-Site VPN connection

I recently implemented an AWS Site-to-Site VPN for Rano OIL, enabling a secure connection between their on-premises network and their newly established AWS account. This project is a collaborative effort with my colleague, whose remarkable expertise I am confident will contribute greatly to its successful completion.

AWS Site-to-Site VPN is a fully managed service that facilitates secure communication between data centers or branch offices and AWS resources. In line with Rano OIL’s requirements, we plan to migrate applications to the cloud using this enhanced and efficient technology. With AWS Site-to-Site VPN, it is possible to integrate Amazon VPCs behind a corporate firewall and seamlessly transfer IT resources without disrupting user access to applications.

During our initial team meeting, we reviewed the Company’s requirements and challenges, and developed a structured plan to ensure an equitable distribution of tasks among all members. I assigned my colleague the responsibility of writing infrastructure code with Terraform or CloudFormation, obtaining equipment quotations to support the project, and preparing a customer-facing presentation.

The project requirements include establishing network-level connectivity from Rano Oil’s on-premises network (via Unifi Security Gateway) to their management VPC. Additionally, it involves enabling shared file access across multiple EC2 instances or on-premise workstations, as well as facilitating the migration of applications.

![AA Rano Oil](https://github.com/azibat92/Aws-projects/blob/main/Site-to-Site/EFS-S2S-Diagram.pdf)

"From an AWS perspective, the setup was straightforward. Using CloudFormation, we deployed a Customer Gateway (CGW) with the IP address of their on-premises firewall, set up a Virtual Private Gateway (VPG), and then configured the VPN Gateway (VPN). While the on-premises configuration required some research to get it right, it functioned as expected once properly set up. My colleague recommended using a Unifi Router due to its well-designed interface and intuitive setup process, which aligned with the configuration steps at this stage of the project. Additionally, Unifi is widely regarded as one of the top networking device brands in the market."
