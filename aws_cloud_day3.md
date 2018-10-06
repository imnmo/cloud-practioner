# Chapter 3

- creating a s3 static website
  - hosting them on the S3 of the amazon using index and error.html
  - again no wordpress would be allowed as it not static - dynamic
- CloudFront:
  - Glossary: CDN-> is a system of distributed servers (network) that deliver webpages and web content based on the user based on the geo locations of the user, origin of webpage an server.

  - Edge location: Content is cached ; separate to AWS region

  - Origin- origin of all files that CDN will distribute , S3 bucket, EC2 instance, ELB or Route 53.

  - CloudFront can be used to deliver entire website(all dynamic, static, streaming, interactive content); it goes to the edge location and then served [best example is Netflix]

  - Distribution types:
    - Web distribution
    - RTMP - used for media streaming
    - Demo on the setup the cloudFront for the content we have and deploy an image

  - EC2 instance and everything related to that:

  - EC2 101:

    - on Demand: allows you to pay to fixed rate by the hour with no commitment
    - Reserved instances- discount on hourly charges 
    - Bid whatever price you want for 
    - Dedicated hosts- 
    - Spot instances are done by the Pharma and the other industries where they use the ton of computation at a given point in time
    - Dedicated host:
      - when no support for multi tenenant virtualization 
    - EBS:
      - EC2 is virtual server and EBS is the virtual Disk,
      - EBS  voulme is spread across  AZ to where they are automatically replicated to protect from  failure
      - EBS is the Disk in the  attached EC2 instances 
        - EBS attached to windows is called root volumes and 
        - Volume types: GP2 < 10,000 IOPS
        - Provisioned IOPS > 10,000 IOPS(NoSQL db)
    - Exam tips:
      - When spot instances are terminated you ll not be charged for partial usages.
      - FIGHT DR MC PX
    - 

    ​	

  - 