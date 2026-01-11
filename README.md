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
- AWS are responsible for the security **OF** the cloud > all the infrasturcture, internal security, hardware and software.<br>
<img width="284" height="178" alt="image" src="https://github.com/user-attachments/assets/bbb3de20-7c99-413b-8b3e-2ed7679f9087" />

