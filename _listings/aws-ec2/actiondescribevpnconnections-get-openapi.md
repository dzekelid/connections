---
swagger: "2.0"
x-collection-name: AWS EC2
x-complete: 0
info:
  title: AWS EC2 API Describe Vpn Connections
  version: 1.0.0
  description: Describes one or more of your VPN connections.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeVpcPeeringConnections:
    get:
      summary: Describe Vpc Peering Connections
      description: Describes one or more of your VPC peering connections.
      operationId: describevpcpeeringconnections
      x-api-path-slug: actiondescribevpcpeeringconnections-get
      parameters:
      - in: query
        name: AccepterPeeringConnectionOptions
        description: The VPC peering connection options for the accepter VPC
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the operation,
          without actually making the request,       and provides an error response
        type: string
      - in: query
        name: RequesterPeeringConnectionOptions
        description: The VPC peering connection options for the requester VPC
        type: string
      - in: query
        name: VpcPeeringConnectionId
        description: The ID of the VPC peering connection
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC Peering Connections
  /?Action=DescribeVpnConnections:
    get:
      summary: Describe Vpn Connections
      description: Describes one or more of your VPN connections.
      operationId: describevpnconnections
      x-api-path-slug: actiondescribevpnconnections-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,             and provides an error response
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC
        type: string
      - in: query
        name: VpnGatewayId
        description: The ID of the virtual private gateway
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPN Connections
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---