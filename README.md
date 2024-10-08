# AWS Certified Cloud Practitioner
<img src="https://d1.awsstatic.com/training-and-certification/certification-badges/AWS-Certified-Cloud-Practitioner_badge.634f8a21af2e0e956ed8905a72366146ba22b74c.png" width="100" />

Learning materials for the AWS Certified Cloud Practitioner Certification (AWS-CLF-C02).

Information on the exam can be found [here](https://aws.amazon.com/certification/certified-cloud-practitioner/).

Domains of material covered in the exam: 
* Cloud Concepts
* Security and Compliance
* Cloud Technology & Services
* Billing, Pricing, & Support

<table>
    <thead>
        <tr>
            <th>Icon</th>
            <th>Name</th>
            <th>Description</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td colspan=3><h2>Cloud Concepts</h2></td>
        </tr>
        <tr>
            <td colspan=3><h3>Deployments and Managing Infrastucture at Scale</h3></td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/CloudFormation.png" width="50"/></td>
            <td><h4>Cloud Formation</h4></td>
            <td>a service that enables users to model and manage infrastructure resources in an automated and secure manner, developers can define and provision AWS infrastructure resources using a JSON- or YAML-formatted infrastructure as code template</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Cloud-Development-Kit.png" width="50"/></td>
            <td><h4>CDK (Cloud Development Kit)</h4></td>
            <td>open-source software development framework for defining cloud infrastructure in code and provisioning it through AWS CloudFormation</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Elastic-Beanstalk.png" width="50"/></td>
            <td><h4>Elastic Beanstalk</h4></td>
            <td>PaaS, runs application code and handles deployment and serving to users</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/CodeDeploy.png" width="50"/></td>
            <td><h4>CodeDeploy</h4></td>
            <td>automates code deployments to any instance, including Amazon EC2 instances and instances running on-premises</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/CodeCommit.png" width="50"/></td>
            <td><h4>CodeCommit</h4></td>
            <td>a scalable versioning control system for developers, similar to git (obsoleted 2024)</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/CodeBuild.png" width="50"/></td>
            <td><h4>CodeBuild</h4></td>
            <td>a fully managed continuous integration service that compiles source code, runs tests, and produces software packages that are ready to deploy</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/CodePipeline.png" width="50"/></td>
            <td><h4>CodePipeline</h4></td>
            <td>a continuous delivery service that enables you to model, visualize, and automate the steps required to release your software</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/CodeArtifact.png" width="50"/></td>
            <td><h4>CodeArtifact</h4></td>
            <td>a secure, highly scalable, managed artifact repository service that helps organizations to store and share software packages for application development</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Systems-Manager.png" width="50"/></td>
            <td><h4>SSM (Systems Manager)</h4></td>
            <td>manage servers running on AWS and in your on-premises data center through a single interface</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Systems-Manager_Session-Manager.png" width="50"/></td>
            <td><h4>SSM Session Manager</h4></td>
            <td>manage your Amazon Elastic Compute Cloud (Amazon EC2) instances, edge devices, on-premises servers, and virtual machines (VMs)</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Systems-Manager_Parameter-Store.png" width="50"/></td>
            <td><h4>SSM Parameter Store</h4></td>
            <td>provides secure, hierarchical storage for configuration data management and secrets management</td>
        </tr>
        <tr>
            <td colspan=3><h3>Global Infrastructure</h3></td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Route-53.png" width="50"/></td>
            <td><h4>Route 53</h4></td>
            <td>a highly available and scalable cloud Domain Name System (DNS) web service</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/CloudFront.png" width="50"/></td>
            <td><h4>CloudFront</h4></td>
            <td>web service that speeds up distribution of your static and dynamic web content, such as .html, .css, .js, and image files, to your users</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/s3-transfer-acceleration.png" width="50"/></td>
            <td><h4>S3 Transfer Acceleration</h4></td>
            <td>shortens the distance between client applications and AWS servers that acknowledge PUTS and GETS to Amazon S3 using our global network of hundreds of CloudFront Edge Locations</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Global-Accelerator.png" width="50"/></td>
            <td><h4>AWS Global Accelerator</h4></td>
            <td>terminates TCP connections from clients at AWS edge locations and, almost concurrently, establishes a new TCP connection with the endpoints, maximizing the time that traffic is on the AWS network and  ensureing that traffic is always routed over the optimum network path.</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Outposts-servers.png" width="50"/></td>
            <td><h4>AWS Outposts</h4></td>
            <td>a pool of AWS compute and storage capacity deployed at a customer site</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Wavelength.png" width="50"/></td>
            <td><h4>AWS WaveLength</h4></td>
            <td>a type of AWS infrastructure designed to run workloads that require low latency or edge resiliency</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Local-Zones.png" width="50"/></td>
            <td><h4>AWS Local Zones</h4></td>
            <td>allow for the placement of resources near end users</td>
        </tr>
        <tr>
            <td colspan=3><h3>Cloud Integrations</h3></td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Simple-Queue-Service.png" width="50"/></td>
            <td><h4>SQS (Simple Queue Service)</h4></td>
            <td>a service to send, store, and receive messages between software components at any volume, without losing messages or requiring other services to be available</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Kinesis.png" width="50"/></td>
            <td><h4>Kinesis</h4></td>
            <td>process real-time data, such as video, audio, application logs, website clickstreams, and IoT telemetry data, for machine learning (ML), analytics, and other applications</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Simple-Notification-Service.png" width="50"/></td>
            <td><h4>SNS (Simple Notification Service)</h4></td>
            <td>a service that makes it easy to set up, operate, and send notifications from the cloud</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Amazon-MQ.png" width="50"/></td>
            <td><h4>Amazon MQ</h4></td>
            <td>a managed message broker service for Apache ActiveMQ Classic and RabbitMQ that streamlines setup, operation, and management of message brokers on AWS</td>
        </tr>
        <tr>
            <td colspan=3><h3>Cloud Monitoring</h3></td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/CloudWatch.png" width="50"/></td>
            <td><h4>CloudWatch</h4></td>
            <td>a repository for metrics and logs</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/CloudWatch_Metrics.png" width="50"/></td>
            <td><h4>CloudWatch Metrics</h4></td>
            <td>essential for ensuring optimal performance and efficient resource utilization, provides insights to AWS Services allowing for real time tracking of health/performance/usage patterns</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/CloudWatch_Alarms.png" width="50"/></td>
            <td><h4>CloudWatch Alarms</h4></td>
            <td>a monitoring tool that helps you create alarms on your AWS Resouces and AWS Services</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/CloudWatch_Logs.png" width="50"/></td>
            <td><h4>Cloudwatch Logs</h4></td>
            <td>centralizes the logs from all of your systems, applications, and AWS services that you use, in a single, highly scalable service</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/EventBridge.png" width="50"/></td>
            <td><h4>EventBridge</h4></td>
            <td>a service that provides real-time access to changes in data in AWS services, your own applications, and software as a service (SaaS) applications without writing code</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/CloudTrail.png" width="50"/></td>
            <td><h4>CloudTrail</h4></td>
            <td>a service that enables governance, compliance, operational auditing, and risk auditing of your AWS account</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/X-Ray.png" width="50"/></td>
            <td><h4>X-Ray</h4></td>
            <td>helps developers analyze and debug production, distributed applications, such as those built using a microservices architecture</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/CodeGuru.png" width="50"/></td>
            <td><h4>CodeGuru</h4></td>
            <td>analyzes the application runtime performance and using machine learning, provides recommendations on ways that could speed up the application</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Health-Dashboard.png" width="50"/></td>
            <td><h4>AWS Health Dashboard</h4></td>
            <td>can be used to learn about AWS Health events that affect AWS services or the AWS account</td>
        </tr>
        <tr>
            <td colspan=3><h3>Networking</h3></td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Virtual-Private-Cloud.png" width="50"/></td>
            <td><h4>Amazon VPC (Virtual Private Cloud)</h4></td>
            <td>a logically isolated section of the AWS Cloud where you can launch AWS resources in a virtual network that you define</td>
        </tr>
        <tr>
            <td></td>
            <td></td>
            <td>usecase: manage components of VPC (Subnet, Internet Gateway, NAT Gateways, Elastic IPs, Flow Logs, Peering); control the security of your VPC by configuring the Network ACLs and Security Groups</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Network-Access-Control-List.png" width="50"/></td>
            <td><h4>NACL (Network Access Control List)</h4></td>
            <td>an optional layer of security for your VPC that acts as a firewall for controlling traffic in and out of one or more subnets</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/PrivateLink.png" width="50"/></td>
            <td><h4>PrivateLink</h4></td>
            <td>provides private connectivity between VPCs, supported AWS services, and your on-premises networks without exposing your traffic to the public internet</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Client-VPN.png" width="50"/></td>
            <td><h4>Client VPN</h4></td>
            <td>a fully-managed remote access VPN solution used by your remote workforce to securely access resources within both AWS and your on-premises network</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Transit-Gateway.png" width="50"/></td>
            <td><h4>Transit Gateway</h4></td>
            <td>connects your Amazon VPCs and on-premises networks through a central hub, simplifies the network and prevents complex peering relationships, Transit Gateway acts as a highly scalable cloud router—each new connection is made only once</td>
        </tr>
        <tr>
            <td colspan=3><h2>Security and Compliance</h2></td>
        </tr>
        <tr>
            <td colspan=3><h3>Shared Responcibility Model</h3></td>
        </tr>
        <tr>
            <td colspan=3><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/images/Shared_Responsibility_Model.jpg" /></td>
        </tr>
        <tr>
            <td colspan=3><h3>Identity Access Management</h3></td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Identity-and-Access-Management.png" width="50"/></td>
            <td><h4>IAM (Identity and Access Management)</h4></td>
            <td>manage users access, controls, and permissions for users within the organization</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Identity-Access-Management_MFA.png" width="50"/></td>
            <td><h4>IAM MFA (Multi-Factor Authorization)</h4></td>
            <td>makes a user have multiple devices to prove their identity</td>
        </tr>
        <tr>
            <td></td>
            <td><h4>AWS Access Keys</h4></td>
            <td>Long-term credentials for individual IAM accounts</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Command-Line-Interface.png" width="50"/></td>
            <td><h4>CLI (Command Line Interface)</h4></td>
            <td>tool to manage AWS tools, provides a command line interface to configure and control multiple services</td>
        </tr>
        <tr>
            <td></td>
            <td><h4></h4></td>
            <td>usecase: requires Access keys for users to access</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/SDK.png" width="50"/></td>
            <td><h4>SDK (Software Development Kit)</h4></td>
            <td>contains tools to develop applications with AWS with different programming languages (eg JS, Java, React, Python, etc.)</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/CloudShell.png" width="50"/></td>
            <td><h4>CloudShell</h4></td>
            <td>online command line shell environment, preloaded with tools and automatically updated</td>
        </tr>
        <tr>
            <td colspan=3><h3>Security Tools</h3></td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/WAF.png" width="50"/></td>
            <td><h4>WAF (web access firewall)</h4></td>
            <td>protect web applications from attacks by allowing you to configure rules that allow, block, or monitor (count) web requests based on conditions that you define</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Shield.png" width="50"/></td>
            <td><h4>AWS Shield</h4></td>
            <td>a managed distributed denial of service (DDoS) protection service that safeguards applications running on AWS</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/AWS-Network-Firewall.png" width="50"/></td>
            <td><h4>AWS Network Firewall</h4></td>
            <td>a stateful, managed, network firewall and intrusion detection and prevention service for an Amazon VPC</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/AWS-Firewall-Manager.png" width="50"/></td>
            <td><h4>AWS Firewall Manager</h4></td>
            <td>a security management service which allows you to centrally configure and manage firewall rules across your accounts and applications in AWS Organization</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/AWS-Key-Management-Service.png" width="50"/></td>
            <td><h4>KMS (Key Management Service)</h4></td>
            <td>gives you centralized control over the cryptographic keys used to protect your data</td>
        </tr>
        <tr>
            <td></td>
            <td><h4>AWS CloudHSM (Cloud Hardware Security Module)</h4></td>
            <td>a cryptographic service for creating and maintaining hardware security modules</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/AWS-Certificate-Manager.png" width="50"/></td>
            <td><h4>ACM (AWS Certificate Manager)</h4></td>
            <td>a service that allows developers to provision, manage, and deploy public and private Secure Sockets Layer/Transport Layer Security (SSL/TLS) certificates for use with AWS services and internal connected resources</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/AWS-Secrets-Manager.png" width="50"/></td>
            <td><h4>Secrets Manager</h4></td>
            <td>encrypts at rest using encryption keys owned and stored in AWS KMS</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/AWS-Artifact.png" width="50"/></td>
            <td><h4>Artifact</h4></td>
            <td>contains compliance-related documents in AWS such as ISO certifications, Payment Card Industry (PCI), and Service Organization Control (SOC) reports</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Amazon-GuardDuty.png" width="50"/></td>
            <td><h4>AWS GuardDuty</h4></td>
            <td>automatically manage resource utilization based on the overall activity levels within AWS accounts, workloads, and data</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Amazon-Inspector.png" width="50"/></td>
            <td><h4>AWS Inspector</h4></td>
            <td>continually scans AWS workloads for software vulnerabilities and unintended network exposure</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/AWS-Config.png" width="50"/></td>
            <td><h4>AWS Config</h4></td>
            <td>helps user record configuration changes to software within EC2 instances in the AWS account and also virtual machines (VMs) or servers in the on-premises environment</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Macie.png" width="50"/></td>
            <td><h4>AWS Macie</h4></td>
            <td>a data security service that discovers sensitive data using machine learning and pattern matching, provides visibility into data security risks, and enables automated protection against those risks</td>
        </tr>
        <tr>
            <td></td>
            <td><h4>AWS SecurityHub</h4></td>
            <td>allows organizations to create custom insights and compliance checks specific to their environment</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Amazon-Detective.png" width="50"/></td>
            <td><h4>Amazon Detective</h4></td>
            <td>helps analyze, investigate, and quickly identify the root cause of security findings or suspicious activities</td>
        </tr>
        <tr>
            <td></td>
            <td><h4>AWS Abuse</h4></td>
            <td>addresses many different types of potentially abusive activity such as phishing, malware, spam, and denial of service (DoS)/ distributed denial of service (DDoS) incidents</td>
        </tr>
        <tr>
            <td></td>
            <td><h4>Root User Privileges</h4></td>
            <td>complete access to all AWS services and resources in your AWS account</td>
        </tr>
        <tr>
            <td></td>
            <td><h4></h4></td>
            <td>usecase: should only be used when absolutely necessary</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/IAM-Access-Analyzer.png" width="50"/></td>
            <td><h4>IAM Access Analyzer</h4></td>
            <td>gives visibility into unused access across your AWS organization and recommendations to help you remediate unused access</td>
        </tr>
        <tr>
            <td colspan=3><h3>Advanced Identity</h3></td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/STS.png" width="50"/></td>
            <td><h4>STS (Security Token Service)</h4></td>
            <td>a tool that provides temporary access to IAM roles with their own permissions</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Cognito.png" width="50"/></td>
            <td><h4>AWS Cognito</h4></td>
            <td>support federated authentication, profile data sync store and AWS access token distribution without writing any backend code</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Directory-Service.png" width="50"/></td>
            <td><h4>AWS Directory Services</h4></td>
            <td>provides multiple directory choices for customers who want to use existing Microsoft AD or Lightweight Directory Access Protocol (LDAP)–aware applications in the cloud</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Identity-Center.png" width="50"/></td>
            <td><h4>IAM Identity Center</h4></td>
            <td>streamlines and simplifies workforce user access to applications or AWS accounts </td>
        </tr>
        <tr>
            <td colspan=3><h2>Cloud Technology & Services</h2></td>
        </tr>
        <tr>
            <td colspan=3><h3>EC2</h3></td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/EC2.png" width="50"/></td>
            <td><h4>EC2 (Elastic Compute Cloud)</h4></td>
            <td>cloud-based cloud computation service, regional service</td>
        </tr>
        <tr>
            <td></td>
            <td></td>
            <td>usecase: can launch a new database in AWS where the customer assumes the responsibility and management of the guest operating system, including updates and security patches</td>
        </tr>
        <tr>
            <td></td>
            <td><h4>EC2 Instance Connect</h4></td>
            <td>tool to connect to an EC2 instance</td>
        </tr>
        <tr>
            <td></td>
            <td><h4>EC2 Dedicated Host</h4></td>
            <td>a physical server with EC2 instance capacity fully dedicated to your use</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/EC2_Spot-Instance.png" width="50"/></td>
            <td><h4>EC2 Spot Instances</h4></td>
            <td>instances from unused EC2 capacity in the AWS cloud</td>
        </tr>
        <tr>
            <td></td>
            <td></td>
            <td>usecase: 90% cheaper with less performance than On-Demand Instances </td>
        </tr>
        <tr>
            <td colspan=3 ><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/images/aws-compute-pricing.png" /></td>
        </tr>
        <tr>
            <td></td>
            <td><h4>EC2 Instance Storage</h4></td>
            <td>storage options to optimize performance vs. cost</td>
        </tr>
        </tr><tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Elastic-Block-Store.png" width="50"/></td>
            <td><h4>EBS (Elastic Block Store)</h4></td>
            <td>block level storage volumes to EC2 instances, multiple EBS volumes can be attached to each EC2 instance</td>
        </tr>
        </tr><tr>
            <td></td>
            <td></td>
            <td>usecase: rapidly changing data</td>
        </tr>
        </tr><tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/AMI.png" width="50"/></td>
            <td><h4>AMI (Amazon Machine Image)</h4></td>
            <td>creates images (templates) of AWS EC2 instances to be used as masters for instance pools</td>
        </tr>
        </tr><tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/EFS.png" width="50"/></td>
            <td><h4>EFS (Elastic File System)</h4></td>
            <td>auto-scaling file system that grows/shrinks as files are added/removed, regional service</td>
        </tr> 
        <tr>
            <td colspan=3><h3>Load Balancing</h3></td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Elastic-Load-Balancing.png" width="50"/></td>
            <td><h4>ELB (Elastic Load Balancing)</h4></td>
            <td>automatically balances application traffic to a different targets and appliances across multiple availabiliy zones</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Application-Load-Balancer.png" width="50"/></td>
            <td><h4>Application Load Balancer</h4></td>
            <td>best suited for load balancing of HTTP and HTTPS traffic and provides advanced request routing targeted at the delivery of modern application architectures, including microservices and containers</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Network-Load-Balancer.png" width="50"/></td>
            <td><h4>Network Load Balancer</h4></td>
            <td>best suited for load balancing of Transmission Control Protocol (TCP), User Datagram Protocol (UDP), and Transport Layer Security (TLS) traffic where extreme performance is required</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Gateway-Load-Balancer.png" width="50"/></td>
            <td><h4>Gateway Load Balancer</h4></td>
            <td>provides both Layer 3 gateway and Layer 4 load balancing capabilities. It is a transparent bump-in-the-wire device that does not change any part of the packet</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Auto-Scaling-Group.png" width="50"/></td>
            <td><h4>ASG (Auto Scaling Groups)</h4></td>
            <td>each group contains multiple EC2 instances and provides autoscaling based on needs, only horizontal (number of instances, not performance of instances)</td>
        </tr>
        <tr>
            <td colspan=3><h3>Object Storage</h3></td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/S3.png" width="50"/></td>
            <td><h4>Amazon S3 (Simple Storage Service)</h4></td>
            <td>object storage service, designed for 99.999999999% (11 9's) of durability and stores millions of customers data</td>
        </tr>
        <tr>
            <td></td>
            <td></td>
            <td>usecase: Bucket Policy allows specific users access to bucket</td>
        </tr>
        <tr>
            <td></td>
            <td><h4>AWS Snow</h4></td>
            <td>provides computation at the edge or migration from edge devices to the cloud</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Snowcone.png" width="50"/></td>
            <td><h4>AWS Snowcone</h4></td>
            <td>small, portable device for local transfer and physical shipment an AWS facility</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Snowball.png" width="50"/></td>
            <td><h4>AWS Snowball</h4></td>
            <td>larger, portable device can be optimized for storage or compute</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Snowball-Edge.png" width="50"/></td>
            <td><h4>AWS Snowball Edge</h4></td>
            <td>an edge computing and data transfer device provided by the AWS Snowball service</td>
        </tr>
        <tr>
            <td></td>
            <td><h4>AWS Snowmobile</h4></td>
            <td>an exabyte-scale data transfer service that is used to move large volumes of data to Amazon Web Services</td>
        </tr>
        <tr>
            <td colspan=3><h3>Databases</h3></td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/RDS.png" width="50"/></td>
            <td><h4>RDS (Relational Database Services)</h4></td>
            <td>managed relational database service for MySQL, PostgreSQL, MariaDB, Oracle BYOL, or SQL server</td>
        </tr>
        <tr>
            <td></td>
            <td></td>
            <td>usecase: simplifies the management of time-consuming database administration tasks; Makes it easy to set up, operate, and scale a relational database</td>
        </tr>
        <tr>
            <td></td>
            <td></td>
            <td>usecase: rapidly changing data</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/ElastiCache.png" width="50"/></td>
            <td><h4>ElastiCache</h4></td>
            <td>fast, in-memory data store for use as a database, cache, message broker</td>
        </tr>
        <tr>
            <td></td>
            <td></td>
            <td>usecase: store the results of I/O-intensive SQL database queries to improve application performance</td>
        </tr>
        <tr>
            <td></td>
            <td></td>
            <td>usecase: lets you deploy and run Memcached or Redis cache server nodes in the cloud</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/DynamoDB.png" width="50"/></td>
            <td><h4>DynamoDB</h4></td>
            <td>fully managed proprietary NoSQL database</td>
        </tr>
        <tr>
            <td></td>
            <td></td>
            <td>usecase: highly scalable, used for nonrelational data</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Redshift.png" width="50"/></td>
            <td><h4>Redshift</h4></td>
            <td>petabyte-scale data warehouse and exabyte-scale data lake analytics</td>
        </tr>
        <tr>
            <td></td>
            <td></td>
            <td>usecase: best used for OLAP (online analytical processing) workloads</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/EMR.png" width="50"/></td>
            <td><h4>EMR (Elastic MapReduce)</h4></td>
            <td>petabyte data processing, interactive analytics and machine learning, uses open source frameworks including Apache Spark, Apache Hive, and Presto</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/QuickSight.png" width="50"/></td>
            <td><h4>Quicksight</h4></td>
            <td>business analytics tool</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/DocumentDB.png" width="50"/></td>
            <td><h4>DocumentDB</h4></td>
            <td>JSON document database</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Neptune.png" width="50"/></td>
            <td><h4>Neptune</h4></td>
            <td>graph database for billions of relationships</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Timestream.png" width="50"/></td>
            <td><h4>Timestream</h4></td>
            <td>time series database</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Quantum-Ledger-Database.png" width="50"/></td>
            <td><h4>QLDB (Quantum Ledger Database)</h4></td>
            <td>ledger database that provides transparent, immutable, and cryptographically verifiable transaction log</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Managed-Blockchain.png" width="50"/></td>
            <td><h4>Managed Blockchain</h4></td>
            <td>allows user to build resilient Web3 application on both public and private blockchains</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Glue.png" width="50"/></td>
            <td><h4>Glue</h4></td>
            <td>serverless data integration service, allows users to discover, prepare, move, and integrate data from multiple sources</td>
        </tr>
        <tr>
            <td></td>
            <td></td>
            <td>usecase: create workflows in ETL</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Database-Migration-Service.png" width="50"/></td>
            <td><h4>DMS (Database Migration Service)</h4></td>
            <td>assists in moving databases and workloads into AWS</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Aurora.png" width="50"/></td>
            <td><h4>Aurora</h4></td>
            <td>A fully managed relational database engine that’s compatible with MySQL and PostgreSQL</td>
        </tr>
        <tr>
            <td></td>
            <td></td>
            <td>usecase: 5x faster than standard MySQL and 3x faster than PostgreSQL, highly scalable</td>
        </tr>
        <tr>
            <td colspan=3><h3>Machine Learning</h3></td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Rekognition.png" width="50"/></td>
            <td><h4>Rekognition</h4></td>
            <td>an image recognition service that detects objects, scenes, activities, landmarks, faces, dominant colors, and image quality</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Transcribe.png" width="50"/></td>
            <td><h4>Transcribe</h4></td>
            <td>an automatic speech recognition service that uses machine learning models to convert audio to text</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Polly.png" width="50"/></td>
            <td><h4>Polly</h4></td>
            <td>a service that converts text into lifelike speech</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Translate.png" width="50"/></td>
            <td><h4>Translate</h4></td>
            <td>a service that translates text between languages</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Lex.png" width="50"/></td>
            <td><h4>Lex</h4></td>
            <td>a voice based virtual assitant or chat bot</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Connect.png" width="50"/></td>
            <td><h4>Connect</h4></td>
            <td>acts as a link between different Machine Learning services to to provide infrastructure</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Comprehend.png" width="50"/></td>
            <td><h4>Comprehend</h4></td>
            <td>sort or collect text documents by subjects or tags</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/SageMaker.png" width="50"/></td>
            <td><h4>SageMaker</h4></td>
            <td>build, train and deploy ML models at scale using tools like notebooks, debuggers, profilers, pipelines, MLOps, and more – all in one integrated development environment (IDE)</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Forecast.png" width="50"/></td>
            <td><h4>Forecast</h4></td>
            <td>a service that handles time series data and predicts future trends</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Kendra.png" width="50"/></td>
            <td><h4>Kendra</h4></td>
            <td>a search service that uses Natural Language Processing and machine learning to return more complex queries</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Personalize.png" width="50"/></td>
            <td><h4>Personalize</h4></td>
            <td>uses your data to generate item recommendations for your users</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Textract.png" width="50"/></td>
            <td><h4>Textract</h4></td>
            <td>extracts content and context from text data</td>
        </tr>
        <tr>
            <td colspan=3><h3>Other Compute Services</h3></td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Elastic-Container-Service.png" width="50"/></td>
            <td><h4>ECS (Elastic Container Service)</h4></td>
            <td>allows for managed container orchestration to easliy deploy, manage, and scale containerized applications</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Lambda.png" width="50"/></td>
            <td><h4>Lambda</h4></td>
            <td>serveless computing, runs code in many different languages (Node.js, Python, Go, Java, etc) and manages resources, scaling to deploy the functions</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/API-Gateway.png" width="50"/></td>
            <td><h4>API Gateway</h4></td>
            <td>fully managed service to allow developers to create, publish, maintain, monitor, and secure API's at any scale</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Batch.png" width="50"/></td>
            <td><h4>Batch</h4></td>
            <td>plans, schedules, and runs containerized batch ML, simulation, and analytics workloads across the full range of AWS compute offerings</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Lightsail.png" width="50"/></td>
            <td><h4>Lightsail</h4></td>
            <td>a virtual private server used to store data, run code, build web-based applications</td>
        </tr>
        <tr>
            <td colspan=3><h3>Other Services</h3></td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/WorkSpaces.png" width="50"/></td>
            <td><h4>AWS WorkSpaces</h4></td>
            <td>a cloud-based virtual desktop that can act as a replacement for a traditional desktop</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/AppStream-2.png" width="50"/></td>
            <td><h4>AppStream 2.0</h4></td>
            <td>a fully managed application streaming service that provides users instant access to their desktop applications from anywhere</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/IoT-Core.png" width="50"/></td>
            <td><h4>AWS IoT Core</h4></td>
            <td>a fully integrated feature that enables IoT developers to easily provision, onboard, and monitor Amazon Sidewalk devices through AWS IoT Core</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Elastic-Transcoder.png" width="50"/></td>
            <td><h4>Elastic Transcoder</h4></td>
            <td>media transcoding in the cloud and designed to be a highly scalable, easy to use and a cost effective way for developers and businesses to convert (or “transcode”) media files from their source format into versions that will playback on devices like smartphones, tablets and PCs</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/AppSync.png" width="50"/></td>
            <td><h4>AppSync</h4></td>
            <td>allows applications to access exactly the data needed</td>
        </tr>
        <tr>
            <td></td>
            <td></td>
            <td>usecase: create a flexible API to securely access, manipulate, and combine data from multiple sources and pay only for requests to your API and for real-time messages delivered to connected clients</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/AWS-Amplify.png" width="50"/></td>
            <td><h4>AWS Amplify</h4></td>
            <td>a unified development platform that provides a seamless bridge between front-end and back-end development</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/AWS-Application-Composer.png" width="50"/></td>
            <td><h4>AWS Application Composer</h4></td>
            <td>streamline and accelerate the architecture, development, and iteration of modern applications</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Device-Farm.png" width="50"/></td>
            <td><h4>AWS Device Farm</h4></td>
            <td>an application testing service that lets you improve the quality of your web and mobile apps by testing them across an extensive range of desktop browsers and real mobile devices</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Backup.png" width="50"/></td>
            <td><h4>AWS Backup</h4></td>
            <td>a fully-managed service that makes it easy to centralize and automate data protection across AWS services, in the cloud, and on premises</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Elastic-Disaster-Recovery.png" width="50"/></td>
            <td><h4>AWS DRS (Elastic Disaster Recovery)</h4></td>
            <td>automatically converts your servers to boot and run natively on AWS when you launch instances for drills or recovery</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/DataSync.png" width="50"/></td>
            <td><h4>AWS DataSync</h4></td>
            <td>a secure, online service that automates and accelerates moving data between on premises and AWS Storage services</td>
        </tr>
        <tr>
            <td></td>
            <td><h4>Cloud Migration Strategies (7R's)</h4></td>
            <td>refactor, replatform, repurchase, rehost, relocate, retain, and retire</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Application-Discovery-Service.png" width="50"/></td>
            <td><h4>Application Discovery Service</h4></td>
            <td>helps plan application migration projects by automatically identifying servers, virtual machines (VMs), and network dependencies in on-premises data centers</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Application-Migration-Service.png" width="50"/></td>
            <td><h4>Application Migration Service</h4></td>
            <td>allows you to migrate physical, virtual, and cloud source servers to AWS for a variety of supported operating systems (OS)</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Application-Migration-Service.png" width="50"/></td>
            <td><h4>AWS Migration Evaluator</h4></td>
            <td>gives a clear baseline of what an organization is running at present and what its projected AWS costs will be, measured on-premises provisioning and utilization</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Migration-Hub.png" width="50"/></td>
            <td><h4>AWS Migration Hub</h4></td>
            <td>provides a single place to discover existing servers, plan migrations, and track the status of each application migration</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Fault-Injection-Service.png" width="50"/></td>
            <td><h4>AWS Fault Injection Service (FIS)</h4></td>
            <td>a systematic and controlled process of introducing faults or errors into a system to observe its behavior under adverse conditions</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Step-Functions.png" width="50"/></td>
            <td><h4>Step Functions</h4></td>
            <td>a visual workflow service that helps developers use AWS services to build distributed applications, automate processes, orchestrate microservices, and create data and machine learning (ML) pipelines</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Ground-Station.png" width="50"/></td>
            <td><h4>AWS Ground Station</h4></td>
            <td>control satellite communications, process data, and scale your operations without having to worry about building or managing your own ground station infrastructure</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Pinpoint.png" width="50"/></td>
            <td><h4>AWS Pinpoint</h4></td>
            <td>an AWS service that you can use to engage with your customers across multiple messaging channels</td>
        </tr>
        <tr>
            <td></td>
            <td><h4>AWS Partner Network (APN)</h4></td>
            <td>network focused on helping partners build successful AWS-based businesses to drive superb customer experiences</td>
        </tr>
        <tr>
            <td></td>
            <td><h4>APN Consulting Partners</h4></td>
            <td>professional services firms that help customers of all sizes design, architect, migrate, or build new applications on AWS</td>
        </tr>
        <tr>
            <td></td>
            <td><h4>APN Technology Partners</h4></td>
            <td>provide software solutions that are either hosted on or integrated with the AWS platform</td>
        </tr>
        <tr>
            <td colspan=3><h2>Billing, Pricing, & Support</h2></td>
        </tr>
        <tr>
            <td colspan=3><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/images/aws-compare-support-plans.png" /></td>
        </tr>
        <tr>
            <td colspan=3><h3>Account Management</h3></td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Organizations.png" width="50"/></td>
            <td><h4>AWS Organizations</h4></td>
            <td>centrally manages and governs the environment as it grows and scales AWS resources</td>
        </tr>
        <tr>
            <td></td>
            <td><h4>Consolodated Billing</h4></td>
            <td>one bill for multiple accounts, share the volume pricing and Reserved Instance discounts by combining the usage across all accounts in the organization</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Control-Tower.png" width="50"/></td>
            <td><h4>AWS Control Tower</h4></td>
            <td>tool to create or manage multi-account AWS environments with best practices
usecase: an easy way to establish a landing zone that implements an AWS well-architected, multi-account environment and applies the AWS best practices</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Resource-Access-Manager.png" width="50"/></td>
            <td><h4>AWS RAM (Resource Access Manager)</h4></td>
            <td>helps securely share resources across AWS accounts, within an organization or organizational units (OUs) in AWS Organizations, and with IAM roles and IAM users for supported resource types</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Service-Catalog.png" width="50"/></td>
            <td><h4>AWS Service Catalog API</h4></td>
            <td>provides programmatic control over all end-user actions as an alternative to using the AWS Management Console</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Compute-Optimizer.png" width="50"/></td>
            <td><h4>Compute Optimizer</h4></td>
            <td>a service that analyzes your AWS resources' configuration and utilization metrics to provide you with rightsizing recommendations</td>
        </tr>
        <tr>
            <td></td>
            <td><h4>Pricing Calculator</h4></td>
            <td>estimate a bill by entering planned usages by service</td>
        </tr>
        <tr>
            <td></td>
            <td><h4>AWS Billing Dashboard</h4></td>
            <td>allows you to view all previous payments, access AWS credits, and consolidate bills</td>
        </tr>
        <tr>
            <td></td>
            <td><h4>Cost Allocation Tags</h4></td>
            <td>organizes resources, cost allocation tags to track AWS costs on a detailed level</td>
        </tr>
        <tr>
            <td></td>
            <td><h4>Cost and Usage Reports</h4></td>
            <td>tracks your AWS usage and provides estimated charges associated with your account</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Budgets.png" width="50"/></td>
            <td><h4>AWS Budgets</h4></td>
            <td>a tool to set custom budgets that alert you when your costs or usage exceed (or are forecasted to exceed) your budgeted amount</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Cost-Explorer.png" width="50"/></td>
            <td><h4>AWS Cost Explorer</h4></td>
            <td>lets you visualize, understand, and manage your AWS costs and usage over time</td>
        </tr>
        <tr>
            <td></td>
            <td><h4>AWS Cost Anomaly Detection</h4></td>
            <td>monitors spending patterns to detect anomalous spend and provide root cause analysis</td>
        </tr>
        <tr>
            <td></td>
            <td><h4>AWS Service Quotas</h4></td>
            <td>enables the view and manage your quotas from a central location</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Trusted-Advisor.png" width="50"/></td>
            <td><h4>AWS Trusted Advisor</h4></td>
            <td>an online tool that provides you with real-time guidance to help you provision your resources following AWS best practices</td>
        </tr>
        <tr>
            <td></td>
            <td><h4>5 categories:</h4></td>
            <td>Cost Optimization, Performance, Security, Fault Tolerance, Service Limits</td>
        </tr>
        <tr>
            <td></td>
            <td></td>
            <td>usecase: capable of inspecting your AWS environment and making recommendations to lower expenditures, improve system performance and reliability, and close security gaps</td>
        </tr>
        <tr>
            <td colspan=3><h3>Architecting</h3></td>
        </tr>
        <tr>
            <td colspan=3><h4>Well-Architected Framework</h4></td>
        </tr>
        <tr>
            <td colspan=3><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/images/AWS-WAF-Six-Pillars.png" /></td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Well-Architected-Tool.png" width="50"/></td>
            <td><h4>AWS Well-Architected Tool</h4></td>
            <td>provides a trusted framework for you to evaluate your cloud architecture and implement designs that will scale over time</td>
        </tr>
        <tr>
            <td></td>
            <td><h4>AWS Customer Carbon Footprint Tool</h4></td>
            <td>tool to analyze an organizations carbon footprint from its AWS service usage</td>
        </tr>
        <tr>
            <td></td>
            <td><h4>AWS CAF (Cloud Adoption Framework)</h4></td>
            <td>a comprehensive guide designed to help organizations effectively plan and implement their cloud adoption strategies</td>
        </tr>
        <tr>
            <td></td>
            <td><h4>Business Perspective Capabilities:</h4></td>
            <td>Strategy Management, Product Management, Business Insights, Portfolio Management, Strategic Partnership, Data Science, Innovation Management, Data Monetization</td>
        </tr>
        <tr>
            <td colspan=3><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/images/aws-caf-perspectives.png" /></td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Professional-Services.png" width="50"/></td>
            <td><h4>AWS Professional Services</h4></td>
            <td>shares a collection of offerings to help you achieve specific outcomes related to enterprise cloud adoption</td>
        </tr>
        <tr>
            <td></td>
            <td><h4>AWS Ecosystem</h4></td>
            <td>the collection of all AWS services</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/rePost.png" width="50"/></td>
            <td><h4>AWS re:Post</h4></td>
            <td>a cloud knowledge service that helps builders remove technical roadblocks, accelerate innovation, and operate efficiently</td>
        </tr>
        <tr>
            <td></td>
            <td><h4>AWS Knowledge Center</h4></td>
            <td>FAQ for AWS users</td>
        </tr>
        <tr>
            <td><img src="https://github.com/cgrundman/aws-clf-c02/blob/main/icons/Managed-Services.png" width="50"/></td>
            <td><h4>AWS Managed Services</h4></td>
            <td>services containing third party tools as part of the AWS Managed Services Advanced operating plan</td>
        </tr>
    </tbody>
</table>

### Special Thanks

[Stephane Maarek's course on Udemy](https://www.udemy.com/course/aws-certified-cloud-practitioner-new/)

[Tutorial Dojo](https://tutorialsdojo.com/)
