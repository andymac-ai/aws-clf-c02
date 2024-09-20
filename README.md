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
            <td colspan=3><h3></h3></td>
        </tr>
        <tr>
            <td><img src="" width="50"/></td>
            <td><h4></h4></td>
            <td></td>
        </tr>
        <tr>
            <td><img src="" width="50"/></td>
            <td><h4></h4></td>
            <td></td>
        </tr>
    </tbody>
</table>

* Networking

<h2 id="2-security-compliance">Security and Compliance</h2>

<h2 id="3-cloud-tech-services">Cloud Technology & Services</h2>

<h2 id="4-billing-pricing-support">Billing, Pricing, & Support</h2>

### Special Thanks

[Stephane Maarek's course on Udemy](https://www.udemy.com/course/aws-certified-cloud-practitioner-new/)

[Tutorial Dojo](https://tutorialsdojo.com/)
