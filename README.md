# AWS Certified Cloud Practitioner Notes

Target Exam Date: Feb 14, 2026

## What is Cloud Computing?
- How websites work: both client and server have IP addresses and client will send a request to server IP address and server knows where to find the client back. It is just like the network of your mail.
- What is a server composed of:
  &emsp;- Compute: CPU, to do some calculations and find results
  &emsp;- Memory: RAM, a very fast memory to allow storing of information
  &emsp;- Storage: Data, special storage to store data
  &emsp;- Database: store data in a structured way
  &emsp;- Network: routers, switch, DNS server
- IT terminology:
  &emsp;- Network: cables, routers and servers connected with each other
  &emsp;- Router: a networking device that forwards data packet between computer networks. They know where to send your packets on the internet.
  &emsp;- Switch: takes a packet and send it to the correct server/client on your network
<img width="371" height="136" alt="image" src="https://github.com/user-attachments/assets/71c33ee5-4f37-4399-996d-6563c4b6f025" />
- Cloud Computing: the on-demand delivery of compute power, database storage, applications, and other IT resources.
- Pros:
  &emsp;- Through a cloud services platform with pay-as-you-go pricing
  &emsp;- You can provision exactly the right type and size of computing resources you need
  &emsp;- You can access as many resources as you need almost instantly
  &emsp;- Simple way to access servers, storage, databases and a set of application services
- Amazon Web Services (AWS) owns and maintains the network-connected hardware required for these application services, while you provision and use what you need via a web application

## The Deployment Models of the Cloud
1. Private Cloud:
   &emsp;- Cloud services used by a single organization, not exposed to the public
   &emsp;- Complete control
   &emsp;- Security for sensitive applications
   &emsp;- Meet specific business needs
   &emsp;- e.g., rackspace
2. Public Cloud:
   &emsp;- Cloud resources owned and operated by a third-party cloud service provider delivered over the Internet
   &emsp;- Able to request what we need whenever we want it
   &emsp;- There are six advantages of cloud computing
   &emsp;- e.g., Microsoft Azure, Google Cloud, AWS
3. Hybrid Cloud:
   &emsp;- Mix of private and public
   &emsp;- Keep some servers on premises and extend some capabilities to the Cloud
   &emsp;- Control over sensitive assets in your private infrastructure
   &emsp;- Flexibility and cost-effectiveness of the public cloud

## Five Characteristics of Cloud Computing
1. On-demand self service: users can provision resources and use them without human interaction from the service provider
2. Broad network access: resources available over the network, and can be accessed by diverse client platforms
3. Multi-tenancy and resource pooling: multiple customers can share the same infrastructure and applications with security and privacy, multiple customers are serviced from the same physical resources
4. Rapid elasticity and scalability: automatically and quickly acquire and dispose resources when needed, quickly and easily scale based on demand
5. Measured service: usage is measured, users pay correctly for what they have used

## Six Advantages of Cloud Computing
1. Trade capital expense (CAPEX) for operational expense (OPEX): pay on-demand do not own hardware, reduce Total Cost of Ownership (TCO) & Operational Expense (OPEX)
2. Benefit from massive economies of scale: prices are reduced as AWS is more efficient due to large scale
3. Stop guessing capacity: scale based on actual measured usage
4. Increase speed and agility
5. Stop spending money running and maintaining data centers
6. Go global in minutes: leverage the AWS global infrastructure 

## Problems Solved by the Cloud
1. Flexibility: change resource types when needed
2. Cost-Effectiveness: pay as you go, for what you use
3. Scalibility: accommodate larger loads by making hardware stronger or adding additional nodes
4. Elastiity: ability to scale out and scale-in when needed
5. High-Availablity and Fault-Tolerance: build across data centers
6. Agility: rapidly develop, test and launch software applications

## Types of Cloud Computing
1. Infrastructure as a Service (IaaS)
  &emsp;- provide building blocks for cloud IT   
  &emsp;- provides networking, computers, data storage space in thei raw form
  &emsp;- highest level of flexibility
  &emsp;- easy parallel with traditional on-premises IT
  &emsp;- e.g., Amazon EC2 (on AWS), GCP, Azure, Rackspace, Digital Ocean, Linode
2. Platform as a Service (PaaS)
   &emsp;- removes the need for your organisation to manage the underlying infrastructure
   &emsp;- focus on the deployment and management of your applications
   &emsp;- e.g., Elastic Beanstalk (on AWS), Heroku, Google App Engine (GCP), Windows Azure (Microsoft)
4. Software as a Service (SaaS)
   &emsp;- completed product that is run and managed by the service provider
   &emsp;- e.g., many AWS services like Rekognition for Machine Learning, Google Apps (Gmail), Dropbox, Zoom
<img width="800" height="511" alt="image" src="https://github.com/user-attachments/assets/80057190-ea52-461f-9633-4f3070b6e90a" />

## Pricing of the Cloud
- AWS has 3 pricing fundamentals, following the pay-as-you-go pricing model
- Compute: pay for compute time
- Storage: pay for data stored in the Cloud
- Data transfer OUT of the cloud: data transfer IN is free
- Solves the expensive issue of Traditional IT
