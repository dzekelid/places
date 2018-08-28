---
name: AWS EC2
x-slug: aws-ec2
description: Amazon Elastic Compute Cloud is a web service that provides resizable
  compute capacity in the cloud. It is designed to make web-scale cloud computing
  easier for developers. Amazon EC2s simple web service interface allows you to obtain
  and configure capacity with minimal friction. It provides you with complete control
  of your computing resources and lets you run on Amazon&rsquo;s proven computing
  environment. Amazon EC2 reduces the time required to obtain and boot new server
  instances to minutes, allowing you to quickly scale capacity, both up and down,
  as your computing requirements change. Amazon EC2 changes the economics of computing
  by allowing you to pay only for capacity that you actually use. Amazon EC2 provides
  developers the tools to build failure resilient applications and isolate themselves
  from common failure scenarios.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Places
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/aws-ec2/apis.md
specificationVersion: "0.14"
apis:
- name: AWS EC2 API - Create Placement Group
  x-api-slug: actioncreateplacementgroup-get
  description: Creates a placement group that you launch cluster instances into.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/aws-ec2/actioncreateplacementgroup-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/aws-ec2/actioncreateplacementgroup-get-openapi.md
- name: AWS EC2 API - Delete Placement Group
  x-api-slug: actiondeleteplacementgroup-get
  description: Deletes the specified placement group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/aws-ec2/actiondeleteplacementgroup-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/aws-ec2/actiondeleteplacementgroup-get-openapi.md
- name: AWS EC2 API - Describe Placement Groups
  x-api-slug: actiondescribeplacementgroups-get
  description: Describes one or more of your placement groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/aws-ec2/actiondescribeplacementgroups-get-openapi.md
- name: AWS EC2 API - Modify Instance Placement
  x-api-slug: actionmodifyinstanceplacement-get
  description: |-
    Set the instance affinity value for a specific stopped instance and modify the
                instance tenancy setting.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/aws-ec2/actionmodifyinstanceplacement-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/aws-ec2/actionmodifyinstanceplacement-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.dynamodb.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.ec2.stack.network
- type: x-code
  url: http://aws.amazon.com/code/Amazon-EC2/
- type: x-documentation
  url: http://docs.aws.amazon.com/AWSEC2/latest/APIReference/Welcome.html
- type: x-faq
  url: https://aws.amazon.com/ec2/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/ec2/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/ec2/pricing/
- type: x-sla
  url: https://aws.amazon.com/ec2/sla/
- type: x-website
  url: https://aws.amazon.com/ec2/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---