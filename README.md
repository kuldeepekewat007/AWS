# AWS

    Why learn aws
Fastest Growing Cloud Computing platform on the planet 
largest public cloud platform on the planet
most of major organization are moving to Amazon hosting and othere services
secure and stable platform for it services deployment 
Cost effective 
Flexibility and Openness 
Elasticity and scalability
  
  What is AWS 
AWS is a cloud provider

cloud provider provides server and services that is based on 
on demand and easily Scalable 

AWS has revolutionized IT over time 

AWS Power some of world biggest websites like
amazon 
netflix 

    Important services for amazon 

  Cumpute 
  
AWS Fargate
      AWS Fargate is a serverless compute engine compatible with Amazon ECS or 
	  Amazon EKS that allows you to run containers without having to manage servers or clusters.
	  Run containers without managing servers
	  
EC2 (Elastic Compute Cloud)
        Amazon Elastic Compute Cloud (Amazon EC2) offers the broadest and deepest compute platform, 
		with over 600 instances and choice of the latest processor, storage, networking, 
		operating system,and purchase model to help you best match the needs of your workload. 
		We are the first major cloud provider that supports Intel, AMD, and Arm processors, 
		the only cloud with on-demand EC2 Mac instances, and the only cloud with 400 Gbps Ethernet networking. 
		We offer the best price performance for machine learning training, 
		as well as the lowest cost per inference instances in the cloud. More SAP, 
		high performance computing (HPC),ML,and Windows workloads run on AWS than any other cloud.
		
ECS (Elastic Container Service)
     Amazon Elastic Container Service (Amazon ECS) is a fully managed container
	 orchestration service that simplifies your deployment, management, and 
	 scaling of containerized applications.Simply describe your application and the resources required, 
	 and Amazon ECS will launch, monitor, and scale 
	 your application across flexible compute options with automatic integrations to 
	 other supporting AWS services that your application needs. 
	 Perform system operations such as creating custom scaling and capacity rules, 
	 and observe and query data from application logs and telemetry.

Lambda 
       AWS Lambda is a serverless, event-driven compute service 
	   that lets you run code for virtually any type of application 
	   or backend service without provisioning or managing servers. 
	   You can trigger Lambda from over 200 AWS services
	   and software as a service (SaaS) applications, and only pay for what you use

  Storage 
  
Amazon Elastic File System
         Amazon Elastic File System (EFS) automatically grows and
		 shrinks as you add and remove files with no need for management or provisioning.
		 
AWS Storage Gateway
          AWS Storage Gateway is a set of hybrid cloud storage services
		  that provide on-premises access to virtually unlimited cloud storage.

Amazon EKS (Elastic Kubernetes Service)
      Amazon Elastic Kubernetes Service (Amazon EKS) is a managed Kubernetes service
	  to run Kubernetes in the AWS cloud and on-premises data centers. 
	  In the cloud, Amazon EKS automatically manages the availability and
	  scalability of the Kubernetes control plane nodes responsible for scheduling containers,
	  managing application availability, storing cluster data, and other key tasks.
	  With Amazon EKS, you can take advantage of all the performance, scale, reliability,
	  and availability of AWS infrastructure, as well as integrations with AWS networking and
	  security services. On-premises, EKS provides a consistent, fully-supported Kubernetes solution
	  with integrated tooling and simple deployment to AWS Outposts, virtual machines, or bare metal servers.

	  
S3 (Simple Storage Service)
      Amazon Simple Storage Service (Amazon S3) is an object storage service 
	  offering industry-leading scalability, data availability, security,
	  and performance. Customers of all sizes and industries can store
	  and protect any amount of data for virtually any use case, such as data lakes,
	  cloud-native applications, and mobile apps. With cost-effective storage classes
	  and easy-to-use management features, you can optimize costs, organize data,
	  and configure fine-tuned access controls to meet specific business, organizational,
	  and compliance requirements.

DynamoDB
      Amazon DynamoDB is a fully managed, serverless, key-value NoSQL database designed to run
	  high-performance applications at any scale. DynamoDB offers built-in security, 
	  continuous backups, automated multi-Region replication,
	  in-memory caching, and data import and export tools.
	  
RDS (Relational DataBase Service)
      Amazon Relational Database Service (Amazon RDS) is a collection of
	  managed services that makes it simple to set up, operate,
	  and scale databases in the cloud. Choose from seven popular engines —
	  Amazon Aurora with MySQL compatibility, Amazon Aurora with PostgreSQL compatibility,
	  MySQL, MariaDB, PostgreSQL, Oracle, and SQL Server — 
	  and deploy on-premises with Amazon RDS on AWS Outposts.

  Security 

IAM (Identity and Access Manager)
     AWS IAM Identity Center (successor to AWS Single Sign-On) helps 
	 you securely create or connect your workforce identities 
	 and manage their access centrally across AWS accounts and applications. 
	 IAM Identity Center is the recommended approach for workforce authentication 
	 and authorization on AWS for organizations of any size and type.

Secrets Manager 
     AWS Secrets Manager helps you manage, retrieve, 
	 and rotate database credentials, API keys, and other secrets throughout their lifecycles.


 
AWS Key Management Service
     AWS Key Management Service (AWS KMS) lets you create, manage,
	 and control cryptographic keys across your applications and AWS services.


  Logging 
  
Cloud Watch
      Amazon CloudWatch collects and visualizes real-time logs, metrics,
	  and event data in automated dashboards to streamline your infrastructure and application maintenance.

   Developer Tools
   
AWS CLI(Command Line Interface)
     The AWS Command Line Interface (AWS CLI) is a unified tool to manage your AWS services.
	 With just one tool to download and configure, 
	 you can control multiple AWS services from the command line and automate them through scripts.
 
The AWS CLI v2 offers several new features including improved installers,
 new configuration options such as AWS IAM Identity Center (successor to AWS SSO),
 and various interactive features. 

CodePipeline
     AWS CodePipeline is a fully managed continuous delivery service that helps
	 you automate your release pipelines for fast and reliable application and infrastructure updates.

CodeBuild
     AWS CodeBuild is a fully managed continuous integration service that
	 compiles source code, runs tests, and produces ready-to-deploy software packages.

CodeDeploy
     AWS CodeDeploy is a fully managed deployment service that 
	 automates software deployments to various compute services,
	 such as Amazon Elastic Compute Cloud (EC2), Amazon Elastic Container Service (ECS), 
	 AWS Lambda, and your on-premises servers.
	 Use CodeDeploy to automate software deployments, eliminating the need for error-prone manual operations.
	 
CodeCommit
     AWS CodeCommit is a secure, highly scalable,
	 fully managed source control service that hosts private Git repositories.

CloudFormation
     AWS CloudFormation lets you model, provision, and manage AWS and 
	 third-party resources by treating infrastructure as code.


   Networking And Content Delivery
   
AWS VPC
     Amazon Virtual Private Cloud (Amazon VPC) gives you full control over your virtual networking environment,
	 including resource placement, connectivity, and security. 
	 Get started by setting up your VPC in the AWS service console.
	 Next, add resources to it such as Amazon Elastic Compute Cloud (EC2)
	 and Amazon Relational Database Service (RDS) instances. Finally,
	 define how your VPCs communicate with each other across accounts, Availability Zones, or AWS Regions.
	 In the example below, network traffic is being shared between two VPCs within each Region.

  End User Computing

Amazon AppStream 2.0
     AppStream 2.0 is an AWS End User Computing (EUC) service that can be configured 
	 for SaaS application streaming or delivery of virtual desktops with selective persistence.
	 When AppStream 2.0 is used for virtual desktops, saved files
	 and application settings remain persistent between user sessions,
	 and a fresh virtual desktop is assigned to the user every time they log on.


AWS Api gateway
     Amazon API Gateway is a fully managed service that makes 
	 it easy for developers to create, publish, maintain, monitor, 
	 and secure APIs at any scale. APIs act as the "front door" 
	 for applications to access data, business logic, or functionality from
	 your backend services. Using API Gateway, you can create RESTful APIs and WebSocket APIs
	 that enable real-time two-way communication applications. API Gateway supports containerized
	 and serverless workloads, as well as web applications.

API Gateway handles all the tasks involved in accepting and
 processing up to hundreds of thousands of concurrent API calls,
 including traffic management, CORS support, authorization and access control,
 throttling, monitoring, and API version management. API Gateway has no minimum
 fees or startup costs. You pay for the API calls you receive and the amount of data
 transferred out and, with the API Gateway tiered pricing model, you can reduce
 your cost as your API usage scales.

