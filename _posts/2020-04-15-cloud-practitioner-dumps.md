---
layout: post
title:  "Cloud Practitioner Dumps"
date:   2020-04-15T16:25:52-00:00
author: dhp.lee
categories: Aws
tags: lorem
---

### AWS Dumps Note

출처 : https://free-braindumps.com/amazon/free-aws-certified-cloud-practitioner-braindumps.html

- AWS Organizations has four main benefits
1) Centrally manage access polices across multiple
2) Automate AWS account creation and management
3) Control access to AWS services
4) Enable consolidated billing across multiple AWS accounts

- EC2 instance, charged for
charged per second, based on an hourly rate, and there are no termination fees

Spot instances offer cheapest option of all EC2's buying options


What are the four primary benefits of using the cloud/AWS ?
- Elasticity, Scalability, Fault Tolerance, High Availability


Karen is building a website that is expected to have a minimum of 1000 users continally over
the course of 24 hours. For 8 hours each day, traffic is expected to be at about 1800 users
What EC2 buying options should she use to handle all the traffic and be moust cost-effective?

C. Karen should buy reserved instances with enough capacity to cover the baseline of 1000
users, then rely on on-demand instances for the 8 hour period of increased traffic each day.
- Reserved instances (in 1/3 year term) can be purchased as a significant discount over on-demand instance


What are the TWO main security layers (firewalls) used inside a VPC
- Network Access Control List, Security Group
Network Access Control List(NACL) act as a firewall on the subnet level, and Security Groups act as a firewall on the instance level

What is a main benefit of CloudFront?
- Built-in DDoS protection

What TWO services/features are required to have available and fault tolerent architecture in AWS
- Elastic Load Balancer
- Auto Scaling

Which S3 Storage class has lowest object availablity rating ?
- infrequent Access
Infrequent access has the lowest availability rating(99.90%). Standard and Reduced Redundancy have an
availability rating of 99.99

Your company's upper management is getting very nervous about managing governance, compliance, and
risk auditing in AWS. What service should you enable
and inform upper management about?
- AWS CloudTrail is designed to log all actions taken
in your AWS account. This provides a great
resource for governance, compliance, and risk auditing


which of the following will effect how much you are
charged for storing object in S3?
- The storage class used for the objects stored
- The total size in gigabytes of all objects stored

What are the benefits of DynamoDB
- Automatic scaling of throughput capacity
- Single-digit milisecond latency
- Supports both document and key-value store data models
- DynamoDB's built-in engine

what best describes penetration testing ?
- Testing your own network/application for vulnerabilities

what is one benefit AND one drawback of buying a reserved EC2 instance ?
- Reserved instances can be purchased as a significant 
discount over on-demand instances
- You are locked in to either a one of thres-year pricing commitment

Reserved instances require a one-year or three-year
purchase term, so you are committing to paying for that
much compute capacity for that full time period.
However, in exchange for the long-term commitment,
you will receive a discount(of up to 75%) over using an on-demand instance (for that same time period)

before moving and/or storing object in AWS Glacier,
what considerations should you make regarding the data
you want to store.
- Make sure you are ok with it taking at minimum a few 
minutes to retrieve the data once stored in Glacier
) Objects stored in Glacier take time to retrieve.
You can pay for expedited retrieval, which will take
several minutes- OR wait several hours

which of the follwing will effect price you pay
an EC2 instance
- Instance Type
- How long you use the instance of
- Amazon Machine Image

AWS Services with build-in DDoS migigation/protection
include: 1) Route 53 2) CloudFront 3) WAF 4)ELB
5) VPCs and Security Groups

under what circumstances would someone want to use
ElasticCache
- The need improved improve the performance of their web application
- They need in-memory data store service

What are the benefits of AWS Organizations?
- TCO, which is not part of AWS Organizations


If you are using an on-demand EC2 instance,
how are you being charged for it?
- You are charged per second, based on an hourly rate,
and there are no termination fees.
- There are no upfront or termination fees, and you are
charged for each second of usage

EC2에 Spot은 interruptions 이 생겼을때
Spot instances offer the cheapest option of all
EC2's buying optios. However, spot instances should
only be used wher there are can be interruptions in processing job being conducted


Redshift is a database offering that is fully-managed
and used for data warehousing and analytics, including
compatibility with existing business intelligence tools.


what are the TWO main security layers use inside VPC
- Network Access Control List(NACL)
- Security Group

NACL act as a firewall on the subnet level, and Security Groups act as a firewall on the instance level