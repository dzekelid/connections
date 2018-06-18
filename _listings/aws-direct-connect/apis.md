---
name: AWS Direct Connect
x-slug: aws-direct-connect
description: AWS Direct Connect makes it easy to establish a dedicated network connection
  from your premises to AWS. Using AWS Direct Connect, you can establish private connectivity
  between AWS and your datacenter, office, or colocation environment, which in many
  cases can reduce your network costs, increase bandwidth throughput, and provide
  a more consistent network experience than Internet-based connections.AWS Direct
  Connect lets you establish a dedicated network connection between your network and
  one of the AWS Direct Connect locations. Using industry standard 802.1q VLANs, this
  dedicated connection can be partitioned into multiple virtual interfaces. This allows
  you to use the same connection to access public resources such as objects stored
  in Amazon S3 using public IP address space, and private resources such as Amazon
  EC2 instances running within anAmazon Virtual Private Cloud (VPC)using private IP
  space, while maintaining network separation between the public and private environments.
  Virtual interfaces can be reconfigured at any time to meet your changing needs.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AWSDirectConnect.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Connections
created: "2018-06-18"
modified: "2018-06-18"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/aws-direct-connect/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Direct Connect API Allocate Connection On Interconnect
  x-api-slug: aws-direct-connect-api
  description: Creates a hosted connection on an interconnect.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AWSDirectConnect.png
  humanURL: https://aws.amazon.com/directconnect/
  baseURL: ://///?Action=AllocateConnectionOnInterconnect
  tags: Connections
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/aws-direct-connect/actionallocateconnectiononinterconnect-get-openapi.md
- name: AWS Direct Connect API Confirm Connection
  x-api-slug: aws-direct-connect-api
  description: Confirm the creation of a hosted connection on an interconnect.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AWSDirectConnect.png
  humanURL: https://aws.amazon.com/directconnect/
  baseURL: ://///?Action=ConfirmConnection
  tags: Connections
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/aws-direct-connect/actionconfirmconnection-get-openapi.md
- name: AWS Direct Connect API Create Connection
  x-api-slug: aws-direct-connect-api
  description: Creates a new connection between the customer network and a specific
    AWS Direct Connect location.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AWSDirectConnect.png
  humanURL: https://aws.amazon.com/directconnect/
  baseURL: ://///?Action=CreateConnection
  tags: Connections
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/aws-direct-connect/actioncreateconnection-get-openapi.md
- name: AWS Direct Connect API Delete Connection
  x-api-slug: aws-direct-connect-api
  description: Deletes the connection.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AWSDirectConnect.png
  humanURL: https://aws.amazon.com/directconnect/
  baseURL: ://///?Action=DeleteConnection
  tags: Connections
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/aws-direct-connect/actiondeleteconnection-get-openapi.md
- name: AWS Direct Connect API Describe Connection Loa
  x-api-slug: aws-direct-connect-api
  description: Returns the LOA-CFA for a Connection.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AWSDirectConnect.png
  humanURL: https://aws.amazon.com/directconnect/
  baseURL: ://///?Action=DescribeConnectionLoa
  tags: Connections
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/aws-direct-connect/actiondescribeconnectionloa-get-openapi.md
- name: AWS Direct Connect API Describe Connections
  x-api-slug: aws-direct-connect-api
  description: Displays all connections in this region.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AWSDirectConnect.png
  humanURL: https://aws.amazon.com/directconnect/
  baseURL: ://///?Action=DescribeConnections
  tags: Connections
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/aws-direct-connect/actiondescribeconnections-get-openapi.md
- name: AWS Direct Connect API Describe Connections On Interconnect
  x-api-slug: aws-direct-connect-api
  description: Return a list of connections that have been provisioned on the given
    interconnect.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AWSDirectConnect.png
  humanURL: https://aws.amazon.com/directconnect/
  baseURL: ://///?Action=DescribeConnectionsOnInterconnect
  tags: Connections
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/aws-direct-connect/actiondescribeconnectionsoninterconnect-get-openapi.md
- name: AWS Direct Connect API
  x-api-slug: aws-direct-connect-api
  description: AWS Direct Connect makes it easy to establish a dedicated network connection
    from your premises to AWS. Using AWS Direct Connect, you can establish private
    connectivity between AWS and your datacenter, office, or colocation environment,
    which in many cases can reduce your network costs, increase bandwidth throughput,
    and provide a more consistent network experience than Internet-based connections.AWS
    Direct Connect lets you establish a dedicated network connection between your
    network and one of the AWS Direct Connect locations. Using industry standard 802.1q
    VLANs, this dedicated connection can be partitioned into multiple virtual interfaces.
    This allows you to use the same connection to access public resources such as
    objects stored in Amazon S3 using public IP address space, and private resources
    such as Amazon EC2 instances running within anAmazon Virtual Private Cloud (VPC)using
    private IP space, while maintaining network separation between the public and
    private environments. Virtual interfaces can be reconfigured at any time to meet
    your changing needs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AWSDirectConnect.png
  humanURL: https://aws.amazon.com/directconnect/
  baseURL: :///
  tags: Connections
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/aws-direct-connect/openapi.md
x-common:
- type: x-change-log
  url: http://aws.amazon.com/releasenotes/AWS-Direct-Connect
- type: x-console
  url: https://console.aws.amazon.com/directconnect/
- type: x-documentation
  url: http://docs.aws.amazon.com/directconnect/latest/APIReference/Welcome.html
- type: x-faq
  url: https://aws.amazon.com/directconnect/faqs/
- type: x-forum
  url: https://forums.aws.amazon.com/forum.jspa?forumID=126
- type: x-getting-started
  url: https://aws.amazon.com/directconnect/getting-started/
- type: x-partner-bundles
  url: ttps://aws.amazon.com/directconnect/directconnectbundles/
- type: x-partners
  url: https://aws.amazon.com/directconnect/partners/
- type: x-pricing
  url: https://aws.amazon.com/directconnect/pricing/
- type: x-website
  url: https://aws.amazon.com/directconnect/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---