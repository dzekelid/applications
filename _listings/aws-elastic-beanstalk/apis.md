---
name: AWS Elastic Beanstalk
x-slug: aws-elastic-beanstalk
description: AWS Elastic Beanstalk is an easy-to-use service for deploying and scaling
  web applications and services developed with Java,.NET, PHP, Node.js, Python, Ruby,
  Go, andDockeron familiar servers such as Apache, Nginx, Passenger, andIIS.You can
  simply upload your code and Elastic Beanstalk automatically handles the deployment,
  from capacity provisioning, load balancing, auto-scaling to application health monitoring.
  At the same time, you retain full control over the AWS resources powering your application
  and can access the underlying resources at any time.There is no additional charge
  for Elastic Beanstalk - you pay only for the AWS resources needed to store and run
  your applications.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Applications
created: "2018-06-17"
modified: "2018-06-17"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/aws-elastic-beanstalk/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Elastic Beanstalk API Create Application
  x-api-slug: aws-elastic-beanstalk-api
  description: |-
    Creates an application that has one configuration template named default
          and no application versions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=CreateApplication
  tags: Applications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/aws-elastic-beanstalk/actioncreateapplication-get-openapi.md
- name: AWS Elastic Beanstalk API Create Application Version
  x-api-slug: aws-elastic-beanstalk-api
  description: Creates an application version for the specified application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=CreateApplicationVersion
  tags: Applications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/aws-elastic-beanstalk/actioncreateapplicationversion-get-openapi.md
- name: AWS Elastic Beanstalk API Delete Application
  x-api-slug: aws-elastic-beanstalk-api
  description: |-
    Deletes the specified application along with all associated versions and
          configurations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=DeleteApplication
  tags: Applications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/aws-elastic-beanstalk/actiondeleteapplication-get-openapi.md
- name: AWS Elastic Beanstalk API Describe Applications
  x-api-slug: aws-elastic-beanstalk-api
  description: Returns the descriptions of existing applications.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=DescribeApplications
  tags: Applications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/aws-elastic-beanstalk/actiondescribeapplications-get-openapi.md
- name: AWS Elastic Beanstalk API Update Application
  x-api-slug: aws-elastic-beanstalk-api
  description: Updates the specified application to have the specified properties.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=UpdateApplication
  tags: Applications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/aws-elastic-beanstalk/actionupdateapplication-get-openapi.md
- name: AWS Elastic Beanstalk API Update Application Version
  x-api-slug: aws-elastic-beanstalk-api
  description: Updates the specified application version to have the specified properties.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=UpdateApplicationVersion
  tags: Applications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/aws-elastic-beanstalk/actionupdateapplicationversion-get-openapi.md
- name: AWS Elastic Beanstalk API
  x-api-slug: aws-elastic-beanstalk-api
  description: AWS Elastic Beanstalk is an easy-to-use service for deploying and scaling
    web applications and services developed with Java,.NET, PHP, Node.js, Python,
    Ruby, Go, andDockeron familiar servers such as Apache, Nginx, Passenger, andIIS.You
    can simply upload your code and Elastic Beanstalk automatically handles the deployment,
    from capacity provisioning, load balancing, auto-scaling to application health
    monitoring. At the same time, you retain full control over the AWS resources powering
    your application and can access the underlying resources at any time.There is
    no additional charge for Elastic Beanstalk - you pay only for the AWS resources
    needed to store and run your applications.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: :///
  tags: Applications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/aws-elastic-beanstalk/openapi.md
x-common:
- type: x-change-log
  url: http://aws.amazon.com/releasenotes/AWS-Elastic-Beanstalk
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/elasticbeanstalk/latest/dg/eb-cli3.html
- type: x-documentation
  url: http://docs.aws.amazon.com/elasticbeanstalk/latest/api/Welcome.html
- type: x-faq
  url: https://aws.amazon.com/elasticbeanstalk/faqs/
- type: x-forum
  url: https://forums.aws.amazon.com/forum.jspa?forumID=86
- type: x-getting-started
  url: https://aws.amazon.com/elasticbeanstalk/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/elasticbeanstalk/pricing/
- type: x-website
  url: https://aws.amazon.com/elasticbeanstalk/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---