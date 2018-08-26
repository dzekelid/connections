---
swagger: "2.0"
x-collection-name: AWS EC2
x-complete: 1
info:
  title: AWS EC2 API
  version: 1.0.0
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
  /?Action=AcceptVpcPeeringConnection:
    get:
      summary: Accept Vpc Peering Connection
      description: Accept a VPC peering connection request.
      operationId: acceptvpcpeeringconnection
      x-api-path-slug: actionacceptvpcpeeringconnection-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,       and provides an error response
        type: string
      - in: query
        name: PeerOwnerId
        description: The AWS account ID of the owner of the peer VPC
        type: string
      - in: query
        name: PeerVpcId
        description: The ID of the VPC with which you are creating the VPC peering
          connection
        type: string
      - in: query
        name: VpcId
        description: The ID of the requester VPC
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC Peering Connection
  /?Action=CreateVpcPeeringConnection:
    get:
      summary: Create Vpc Peering Connection
      description: 'Requests a VPC peering connection between two VPCs: a requester
        VPC that you own and a peer VPC with which to create the connection.'
      operationId: createvpcpeeringconnection
      x-api-path-slug: actioncreatevpcpeeringconnection-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,       and provides an error response
        type: string
      - in: query
        name: VpcPeeringConnectionId
        description: The ID of the VPC peering connection
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC Peering Connection
  /?Action=CreateVpnConnection:
    get:
      summary: Create Vpn Connection
      description: |-
        Creates a VPN connection between an existing virtual private gateway and a VPN customer
                    gateway.
      operationId: createvpnconnection
      x-api-path-slug: actioncreatevpnconnection-get
      parameters:
      - in: query
        name: DestinationCidrBlock
        description: The CIDR block associated with the local subnet of the customer
          network
        type: string
      - in: query
        name: VpnConnectionId
        description: The ID of the VPN connection
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC Connection
  /?Action=CreateVpnConnectionRoute:
    get:
      summary: Create Vpn Connection Route
      description: Creates a static route associated with a VPN connection between
        an existing virtual private gateway and a VPN customer gateway.
      operationId: createvpnconnectionroute
      x-api-path-slug: actioncreatevpnconnectionroute-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,             and provides an error response
        type: string
      - in: query
        name: VpnConnectionId
        description: The ID of the VPN connection
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC Connection Route
  /?Action=DeleteVpcPeeringConnection:
    get:
      summary: Delete Vpc Peering Connection
      description: Deletes a VPC peering connection.
      operationId: deletevpcpeeringconnection
      x-api-path-slug: actiondeletevpcpeeringconnection-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,       and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: VpcPeeringConnectionId.N
        description: One or more VPC peering connection IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC Peering Connection
  /?Action=DeleteVpnConnection:
    get:
      summary: Delete Vpn Connection
      description: Deletes the specified VPN connection.
      operationId: deletevpnconnection
      x-api-path-slug: actiondeletevpnconnection-get
      parameters:
      - in: query
        name: DestinationCidrBlock
        description: The CIDR block associated with the local subnet of the customer
          network
        type: string
      - in: query
        name: VpnConnectionId
        description: The ID of the VPN connection
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPN Connection
  /?Action=DeleteVpnConnectionRoute:
    get:
      summary: Delete Vpn Connection Route
      description: Deletes the specified static route associated with a VPN connection
        between an existing virtual private gateway and a VPN customer gateway.
      operationId: deletevpnconnectionroute
      x-api-path-slug: actiondeletevpnconnectionroute-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,             and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: VpnConnectionId.N
        description: One or more VPN connection IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPN Connection Route
  /?Action=ModifyVpcPeeringConnectionOptions:
    get:
      summary: Modify Vpc Peering Connection Options
      description: Modifies the VPC peering connection options on one side of a VPC
        peering connection.
      operationId: modifyvpcpeeringconnectionoptions
      x-api-path-slug: actionmodifyvpcpeeringconnectionoptions-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,       and provides an error response
        type: string
      - in: query
        name: VpcPeeringConnectionId
        description: The ID of the VPC peering connection
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC Peering Connection
  /?Action=RejectVpcPeeringConnection:
    get:
      summary: Reject Vpc Peering Connection
      description: Rejects a VPC peering connection request.
      operationId: rejectvpcpeeringconnection
      x-api-path-slug: actionrejectvpcpeeringconnection-get
      parameters:
      - in: query
        name: CustomerGatewayId
        description: The ID of the customer gateway
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,             and provides an error response
        type: string
      - in: query
        name: Options
        description: Indicates whether the VPN connection requires static routes
        type: string
      - in: query
        name: Type
        description: The type of VPN connection (ipsec
        type: string
      - in: query
        name: VpnGatewayId
        description: The ID of the virtual private gateway
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC Peering Connection
---