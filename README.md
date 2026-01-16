# AWS Certified Cloud Practitioner Notes

Target Exam Date: Feb 14, 2026

## What is Cloud Computing?
- How websites work: both client and server have IP addresses and client will send a request to server IP address and server knows where to find the client back. It is just like the network of your mail.<br>
- What is a server composed of:<br>
  &emsp;- Compute: CPU, to do some calculations and find results.<br>
  &emsp;- Memory: RAM, a very fast memory to allow storing of information.<br>
  &emsp;- Storage: Data, special storage to store data.<br>
  &emsp;- Database: store data in a structured way.<br>
  &emsp;- Network: routers, switch, DNS server.<br>
- IT terminology:<br>
  &emsp;- Network: cables, routers and servers connected with each other.<br>
  &emsp;- Router: a networking device that forwards data packet between computer networks. They know where to send your packets on the internet.<br>
  &emsp;- Switch: takes a packet and send it to the correct server/client on your network.<br>
<img width="371" height="136" alt="image" src="https://github.com/user-attachments/assets/71c33ee5-4f37-4399-996d-6563c4b6f025" /><br>
- Cloud Computing: the on-demand delivery of compute power, database storage, applications, and other IT resources.<br>
- Pros:<br>
  &emsp;- Through a cloud services platform with pay-as-you-go pricing.<br>
  &emsp;- You can provision exactly the right type and size of computing resources you need.<br>
  &emsp;- You can access as many resources as you need almost instantly.<br>
  &emsp;- Simple way to access servers, storage, databases and a set of application services.<br>
- Amazon Web Services (AWS) owns and maintains the network-connected hardware required for these application services, while you provision and use what you need via a web application.<br>

## The Deployment Models of the Cloud
1. Private Cloud:<br>
   &emsp;- Cloud services used by a single organization, not exposed to the public.<br>
   &emsp;- Complete control.<br>
   &emsp;- Security for sensitive applications.<br>
   &emsp;- Meet specific business needs.<br>
   &emsp;- e.g., rackspace.<br>
2. Public Cloud:<br>
   &emsp;- Cloud resources owned and operated by a third-party cloud service provider delivered over the Internet.<br>
   &emsp;- Able to request what we need whenever we want it.<br>
   &emsp;- There are six advantages of cloud computing.<br>
   &emsp;- e.g., Microsoft Azure, Google Cloud, AWS.<br>
3. Hybrid Cloud:<br>
   &emsp;- Mix of private and public.<br>
   &emsp;- Keep some servers on premises and extend some capabilities to the Cloud.<br>
   &emsp;- Control over sensitive assets in your private infrastructure.<br>
   &emsp;- Flexibility and cost-effectiveness of the public cloud.<br>

## Five Characteristics of Cloud Computing
1. On-demand self service: users can provision resources and use them without human interaction from the service provider.<br>
2. Broad network access: resources available over the network, and can be accessed by diverse client platforms.<br>
3. Multi-tenancy and resource pooling: multiple customers can share the same infrastructure and applications with security and privacy, multiple customers are serviced from the same physical resources.<br>
4. Rapid elasticity and scalability: automatically and quickly acquire and dispose resources when needed, quickly and easily scale based on demand.<br>
5. Measured service: usage is measured, users pay correctly for what they have used.<br>

## Six Advantages of Cloud Computing
1. Trade capital expense (CAPEX) for operational expense (OPEX): pay on-demand do not own hardware, reduce Total Cost of Ownership (TCO) & Operational Expense (OPEX).<br>
2. Benefit from massive economies of scale: prices are reduced as AWS is more efficient due to large scale.<br>
3. Stop guessing capacity: scale based on actual measured usage.<br>
4. Increase speed and agility.<br>
5. Stop spending money running and maintaining data centers.<br>
6. Go global in minutes: leverage the AWS global infrastructure.<br>

## Problems Solved by the Cloud
1. Flexibility: change resource types when needed.<br>
2. Cost-Effectiveness: pay as you go, for what you use.<br>
3. Scalibility: accommodate larger loads by making hardware stronger or adding additional nodes.<br>
4. Elastiity: ability to scale out and scale-in when needed.<br>
5. High-Availablity and Fault-Tolerance: build across data centers.<br>
6. Agility: rapidly develop, test and launch software applications.<br>

## Types of Cloud Computing
1. Infrastructure as a Service (IaaS).<br>
  &emsp;- provide building blocks for cloud IT.<br>
  &emsp;- provides networking, computers, data storage space in their raw form.<br>
  &emsp;- highest level of flexibility.<br>
  &emsp;- easy parallel with traditional on-premises IT.<br>
  &emsp;- e.g., Amazon EC2 (on AWS), GCP, Azure, Rackspace, Digital Ocean, Linode.<br>
2. Platform as a Service (PaaS).<br>
   &emsp;- removes the need for your organisation to manage the underlying infrastructure&emsp;-
   &emsp;- focus on the deployment and management of your applications.<br>
   &emsp;- e.g., Elastic Beanstalk (on AWS), Heroku, Google App Engine (GCP), Windows Azure (Microsoft).<br>
4. Software as a Service (SaaS).<br>
   &emsp;- completed product that is run and managed by the service provider.<br>
   &emsp;- e.g., many AWS services like Rekognition for Machine Learning, Google Apps (Gmail), Dropbox, Zoom.<br>
<img width="800" height="511" alt="image" src="https://github.com/user-attachments/assets/80057190-ea52-461f-9633-4f3070b6e90a" /><br>

## Pricing of the Cloud
- AWS has 3 pricing fundamentals, following the pay-as-you-go pricing model.<br>
- Compute: pay for compute time.<br>
- Storage: pay for data stored in the Cloud.<br>
- Data transfer OUT of the cloud: data transfer IN is free.<br>
- Solves the expensive issue of Traditional IT.<br>

## AWS Cloud Use Cases
- AWS enables you to build sophisticated, scalable applications.<br>
- Applicable to a diverse set of industries.<br>
- Use cases include:<br>
  &emsp;- enterprise IT, backup and storage, big data analytics.<br>
  &emsp;- Website hosting, mobile and social apps.<br>
  &emsp;- Gaming.<br>

## AWS Global Infrastructure
- AWS Regions.<br>
- AWS Availability Zones.<br>
- AWS Data Centers.<br>
- AWS Edge Locations/Points of Presence.<br>

## AWS Regions
- AWS has Regions all around the world.<br>
- Names can be us-east-1, eu-west-3....<br>
- A region is a cluster of data centers.<br>
- Most AWS services are region-scoped > if we use a service in one region and we try to use it in a different region, it will be like a new time of using the service.<br>
- e.g., Amazon EC2 (IaaS), Elastic Beanstalk (PaaS), Lambda (Function as a Service), Rekognition (SaaS)

## How to Choose an AWS Region?
- If you need to launch a new application, where should you do it?<br>
- Compliance with data governance and legal requirements: data never leaves a region without your explicit permission.<br>
- Proximity to customers: reduced latency.<br>
- Available services within a Region: new services and new features aren't available in every Region.<br>
- Pricing: pricing varies region to region and is transparent in the service pricing page.<br>

## AWS Availability Zones (AZ)
- What actually are going into the region.<br>
- Each region has many AZ (usually 3, min is 3, max is 6).<br>
- Each AZ is one or more discrete data centers with redundant power, networking, and connectivity.<br>
- These AZ are separate from each other, so that they are isolated from disasters.<br>
- AZ connected with high bandwith, ultra-low latency networking.<br>

## AWS Edge Locations/Points of Presence (POP)
- Amazon has 400+ POP (400+ edge locations & 10+ regional caches) in 90+ cities across 40+ countries.<br>
- Content is delivered to end users with lower latency.<br>

## AWS has Global Services
- Identity and Access Management (IAM).<br>
- Route 53 (DNS Service).<br>
- CloudFront (Content Delivery Network).<br>
- Web Application Firewall (WAF).<br>

## Shared Responsibility Model Diagram
- Customers are responsible for the security **IN** the cloud > whatever you used and however you configure it is your responsibility that includes security, data, network and firewall configuration.<br>
- AWS are responsible for the security **OF** the cloud > all the infrastructure, internal security, hardware and software.<br>
<img width="284" height="178" alt="image" src="https://github.com/user-attachments/assets/bbb3de20-7c99-413b-8b3e-2ed7679f9087" />


## IAM Section
- Identity and Access Management.<br>
- It is a **Global Service**, no region to be selected.<br>
- In IAM we are going to create a user and groups that are available everywhere.<br>
- Root account created by default and should not be used or shared.<br>
- Users arepeople within your organization and can be grouped.<br>
- Groups only contain users, not other groups.<br>
- Users do not have to belong to a group (not the best practice).<br>
- User can belong to multiple groups.<br>

## IAM Permissions
- Users or Groups can be assigned JSON documents called policies.<br>
- These policies define the permissions of the users.<br>
- We are allowing our users to use some services in AWS.<br>
- In AWS, we do not allow everyone to do everything.<br>
- In AWS you apply the **least privilege principle**, do not give more permissions than a user needs.<br>
- Tags are optional, but they allow you to give metadata to many of your resources.<br>

## IAM Policies Inheritance
- a policy will be inherited by that specific group.<br>
- Inline Policy: a policy that is attached to a user.<br>

## IAM Policies Structure
- Consists of:<br>
  &emsp;- Version: policy language version, always included "2012-10-07".<br>
  &emsp;- Id: an identifier for the policy (optional).<br>
  &emsp;- Statement: one or more individual statements (optional).<br>
- Statement consists of:<br>
  &emsp;-Sid: an identifier for the statement (optional).<br>
  &emsp;- Effect: whether the statement allows or denies access (Allow, Deny).<br>
  &emsp;- Principal: account/user/role to which this policy applied to.<br>
  &emsp;- Action: list of actions this policy allows or denies.<br>
  &emsp;- Resource: list of resources to which the actions applied to.<br>
  &emsp;- Condition: conditions for when this policy is in effect.<br>
<img width="800" height="515" alt="image" src="https://github.com/user-attachments/assets/cb235b5e-5bd6-450e-9aa2-94d96c2c90c4" />

## IAM Password Policy
- Strong passwords = higher security for your account.<br>
- In AWS, you can setup a password policy:<br>
  &emsp;- Set a min password length.<br>
  &emsp;- Require specific character types:<br>
      &emsp;&emsp;- uppercase letters.<br>
      &emsp;&emsp;- lowercase letters.<br>
      &emsp;&emsp;- numbers.<br>
      &emsp;&emsp;- non-alphanumeric characters.<br>
  &emsp;- Allow all IAM users to change their own passwords.<br>
  &emsp;- Require users to change their password after some time (password expiration).<br>
  &emsp;- Prevent password re-use.<br>
- A password policy is helpful against a brute-force attack.<br>

## Multi Factor Authentication - MFA
- Users have access to your account and can possibly change configurations or delete resources in your AWS account.<br>
- You want to protect your Root Accounts and IAM users.<br>
- MFA = password you know + security device you own
- Main benefit: if a password is stolen or hacked, the account is not compromised.<br>

## MFA Devices
- Virtual MFA Devices:<br>
  &emsp;- Google Authenticator (phone only), Authy (phone only) > support for multiple tokens in a single device.<br>
  &emsp;- Universal 2nd Factor (U2F) Security Key: A physical device, YubiKey by Yubico (3rd party) > support multiple roots and IAM users using a single security key<br>
- Hardware Key Fob MFA Device:<br>
  &emsp;- Hardware Key Fob MFA Device, provided by Gemalto (3rd party). <br>
  &emsp;- Hardware Key Fob MFA Device for AWS GovCloud (US), provided by SurePass (3rd party).<br>

## How Users Can Access AWS?
1. AWS Management Console (protected by password + MFA).<br>
2. AWS Command Line Interface (CLI) (protected by access keys).<br>
3. AWS Software Development Kit (SDK) - for code (protected by access keys).<br>
- Access Keys are generated through the AWS Console.<br>
- Users manage their own Access Keys.<br>
- Access Keys are secret, do not share them.<br>

## What is AWS CLI?
- A tool that enables you to interact with AWS services using commands in your command-line shell.<br>
- Direct access to the public APIs of AWS services.<br>
- You can develop scripts to manage your resources.<br>
- It is an open-source.<br>
- Alternative to using AWS Management Console.<br>
- Cloud shell is only available in certain region.<br>

## What is AWS SDK?
- AWS Software Development Kit (AWS SDK).<br>
- Language-specific APIs (set of libraries).<br>
- Enables you to access and manage AWS services programmatically.<br>
- Embedded within your application.<br>
- Supports:<br>
  &emsp;- SDKs (JavaScript, Python, PHP, .NET, Ruby, Java, Go, Node.js, C++).<br>
  &emsp;- Mobile SDKs (Android, iOS).<br>
  &emsp;- IoT Device SDKs (Embedded C, Arduino).<br>

## IAM Roles for Services
- Some AWS service will need to perform actions on your behalf.<br>
- To do so, we will assign permissions to AWS services with IAM Roles.<br>
- Common Roles:<br>
  &emsp;- EC2 Instance Roles.<br>
  &emsp;- Lambda Function Roles.<br>
  &emsp;- Roles for CloudFormation.<br>

## IAM Security Tools
- IAM Credentials Report (account-level).<br>
    &emsp;- a report that lists all your account's users and the status of their various credentials.<br>
- IAM Access Advisor (user-level).<br>
    &emsp;- access advisor shows the service permissions granted to a user and when those services were last accessed.<br>
    &emsp;- You can use this info to revise your policies.<br>

## IAM Guidelines & Best Practices
- Do not use the root account except for AWS account setup.<br>
- One physical user = One AWS user.<br>
- Assign users to groups and assign permissions to groups.<br>
- Create a strong password policy.<br>
- Use and enforce the use of MFA.<br>
- Create and use Roles for giving permissions to AWS services.<br>
- Use Access Keys for Programmatic Acces (CLI/SDK).<br>
- Audit permissions of your account using IAM Credentials Report & IAM Access Advisor.<br>
- Never share IAM users and Access Keys.<br>

## Shared Responbility Model
- AWS:<br>
    &emsp;- Infrastructure (global network security).<br>
    &emsp;- Configuration and vulnerability analysis.<br>
    &emsp;- Compliance validation.<br>
- You:<br>
    &emsp;- Users, groups, roles, policies management and monitoring.<br>
    &emsp;- Enable MFA aon all accounts.<br>
    &emsp;- Rotate all your keys often.<br>
    &emsp;- Use IAM tools to apply appropriate permissions.<br>
    &emsp;- Analyze access patterns and review permissions.<br>


### EC2
## Amazon EC2
- EC2 is one of the most popular of AWS' offering.<br>
- EC2 = Elastic Compute Cloud = Infrastructure as a Service (IaaS).<br>
- It mainly consists in the capability of:<br>
  &emsp;- Renting virtual machines (EC2).<br>
  &emsp;- Storing data on virtual drives (EBS).<br>
  &emsp;- Distributing load across machines (ELB).<br>
  &emsp;- Scaling the services using an auto-scaling group (ASG).<br>
- Knowing EC2 is fundamental to understand how the Cloud works..<br>

## EC2 Sizing & Configuration Options
- OS: Linux, Windows, or Mac OS.<br>
- How much computer power & cores (CPU).<br>
- How much random-access memory (RAM).<br>
- How much storgae space.<br>
- Network card: speed of the card, public IP address.<br>
- Firewall rules: security group.<br>
- Bootstrap script (configure at first launch): EC2 user data

## EC2 User Data
- It is possible to bootstrap our instances using an EC2 User Data script.<br>
- Bootstrapping: launching commands when a machine starts.<br>
- That script is only run once at the instance first start.<br>
- EC2 user data is used to automate boot tasks such as:<br>
  &emsp;- installing updates.<br>
  &emsp;- installing software.<br>
  &emsp;- downloading common files from the internet.<br>
- The EC2 User Data Script runs with the root user.<br>

## EC2 Instance Types
- AWS naming convention: m5.2xlarge.<br>
  &emsp;- m: instance class.<br>
  &emsp;- 5: generation (AWS imporves them over time).<br>
  &emsp;- 2xlarge: size within the instance class.<br>
- General Purpose:<br>
  &emsp;- Greate for a diversity of workloads such as web servers or code repositories.<br>
  &emsp;- Balance between compute, networking, memory.<br>
  &emsp;- e.g.: t2.micro.<br>
- Compute Optimized: great for compute-intensive tasks that require high performance processors.<br>
  &emsp;- batch proceeding workloads.<br>
  &emsp;- media transcoding.<br>
  &emsp;- high performance web servers.<br>
  &emsp;- high performance computing (HPC).<br>
  &emsp;- scientific modeling and machine learning.<br>
  &emsp;- dedicated gaming servers.<br>
- Memory Optimized: fast performance for workloads that process large data sets in memory.<br>
  &emsp;- high performance, relational/non-relational databases.<br>
  &emsp;- distibuted web scale cache stores.<br>
  &emsp;- in-memory databases optimized for business intelligence (BI).<br>
  &emsp;- applications performing real-time processing of big unstructured data.<br>
- Storage Optimized: great for storage-intenive tasks that require high, sequential read and write access to large data sets on local storage.<br>
  &emsp;- high frequency online transaction processing (OLTP) systems.<br>
  &emsp;- relational & NoSQL databases.<br>
  &emsp;- cache for in-memory databases (e.g., Redis).<br>
  &emsp;- data warehousing applications.<br>
  &emsp;- distributed file systems.<br>
- Example:<br>
  ![image](https://github.com/user-attachments/assets/0a01afb1-7b0c-4daf-9ee6-b6c1b222f493)
