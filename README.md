# AWS-Practical-Documentation
### Definition : deploy build on Amazon S3

### Live Link : [https://d3sbgnc0zt8wcq.cloudfront.net](https://d3sbgnc0zt8wcq.cloudfront.net)
---
### Popular Services of AWS:

  1. Amazon S3 (Simple Storage Service)
  2. Amazon EC2 (Elastic Compute Cloud)
  3. Amazon RDS (Relational Database Service)
  4. Amazon DynamoDB
  5. AWS IAM (Identity and Access Management)
  6. Amazon CloudFront
     
### Services Used for deployment:
- **S3 Bucket**

    Amazon S3 is object storage built to store and retrieve any amount of data from anywhere. S3 is a simple storage service that offers industry leading durability, availability, performance, security, and virtually unlimited scalability at very low costs.
  
- **Amazon CloudFront:**
  
    As mentioned earlier, Amazon CloudFront is a content delivery network (CDN) that accelerates the distribution of your content to users worldwide. It caches and delivers content from edge locations, reducing latency and improving the performance of web applications and websites.
  
### Procedure :

  1. Create AWS Account.
  2. Create a S3 bucket.
  3. create build of the Project.
  4. Upload build files in the S3 bucket.
  5. Create Cloud Front Distribution and add domain name of S3 bucket.
  6. Update policy of S3 bucket in permissions.
  7. Create customized Error page for 403 access denied error on Page refresh in CloudFront.
  8. Use CloudFront Distribution domain name as public URL
---
### SnapShots :

  1. Create S3 Bucket using unique name.

     ![S3 bucket](https://github.com/vanshitaa-shah/AWS-Practical-Documentation/assets/125017039/c5e1731e-51dd-4bf8-ae8b-8c025b89cd5d)

  2. Upload Index.html and Assets from build in S3 Bucket.

     ![Build Upload](https://github.com/vanshitaa-shah/AWS-Practical-Documentation/assets/125017039/792b008c-5cb5-4914-acd3-64b652d81ef6)
  
  3. Create CloudFront distribution and add s3 bucket domain name.

     ![Distribution](https://github.com/vanshitaa-shah/AWS-Practical-Documentation/assets/125017039/9249317d-c6ec-438b-bbef-de5460467bd0)

  4. After creating distribution, copy the policy and update in S3 bucket permissions.

     ![policy](https://github.com/vanshitaa-shah/AWS-Practical-Documentation/assets/125017039/a0665b10-33b1-4984-8525-a1a58a0ce719)

  5. For handling 403 access denied error on page refresh, create Customized Error page.
     ![policy](https://cdn-images-1.medium.com/v2/resize:fit:880/1*YUafE4xmfw34buLoHP9mtw.png)

     

