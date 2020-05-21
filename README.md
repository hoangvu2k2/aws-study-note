# [AWS Certified Solution Architect - Associate](https://aws.amazon.com/training/path-architecting/) 2020 Study Notes

![Course_year](https://img.shields.io/badge/Course%20Year-2020-brightgreen.svg)


```
Invention requires two thing:
1. The ability to try a lot of experiments
2. Not having to live with the collateral damage of failed experiments

 Andy Jassy - CEO AWS  
```
## Overview
### `What you need to know to pass the exam`
 * AWS Global Infastructure
 * Compute
 * Storage
 * Databases
 * Network and Content Delivery
 * Security, Identity & Compliance
### `Global infastructure`
* Availability Zone
    * A data center or multiple data centers which are close enough
    * ~ 76 AZs
* Region: Geographical area
    * Physical location in the world, consists of 2 or more AZ
    * ~ 24 regions 
* Edge location 
    * Endpoints for AWS which are used for caching content (Cloud Front)
    * ~ 150 Edge locations

### `S3`
#### `Overview`
* Object based storage (vs. block based storage)
* Unlimitted storage
* File can be from 0 to 5TB
* S3 is universial namespace. Bucket name is unique glocally 
* REST call PUT to upload file --> receive HTTP 200 if the upload was successful
* An object in S3
    * Key
    * Value
    * Version ID
    * Metadata
    * Sub-resources
* Read after write consistency: Can read an object right after uploaded
* Eventual Consistency for overwrite PUTS or DELETE
* 99.99 availibility, 99.(11x9) durability 

#### `Features`
* Tiered Storage Available
* Lifecycle management
* Encryption
* MFA Delete
Secure your data using ACL and Policy

#### `S3 standard`

 
## `References`
* [Study node from AlessioCasco](https://github.com/AlessioCasco/AWS-CSA-2019-study-notes)