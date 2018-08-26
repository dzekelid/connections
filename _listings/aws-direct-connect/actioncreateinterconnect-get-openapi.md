---
swagger: "2.0"
x-collection-name: AWS Direct Connect
x-complete: 0
info:
  title: AWS Direct Connect API Create Interconnect
  version: 1.0.0
  description: Creates a new interconnect between a AWS Direct Connect partner's network
    and a specific AWS Direct Connect location.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AllocateConnectionOnInterconnect:
    get:
      summary: Allocate Connection On Interconnect
      description: Creates a hosted connection on an interconnect.
      operationId: allocateConnectionOnInterconnect
      x-api-path-slug: actionallocateconnectiononinterconnect-get
      parameters:
      - in: query
        name: bandwidth
        description: Bandwidth of the connection
        type: string
      - in: query
        name: connectionName
        description: Name of the provisioned connection
        type: string
      - in: query
        name: interconnectId
        description: ID of the interconnect on which the connection will be provisioned
        type: string
      - in: query
        name: ownerAccount
        description: Numeric account Id of the customer for whom the connection will
          be provisioned
        type: string
      - in: query
        name: vlan
        description: The dedicated VLAN provisioned to the connection
        type: string
      responses:
        200:
          description: OK
      tags:
      - Connections
  /?Action=ConfirmConnection:
    get:
      summary: Confirm Connection
      description: Confirm the creation of a hosted connection on an interconnect.
      operationId: confirmConnection
      x-api-path-slug: actionconfirmconnection-get
      parameters:
      - in: query
        name: connectionId
        description: ID of the connection
        type: string
      responses:
        200:
          description: OK
      tags:
      - Connections
  /?Action=CreateConnection:
    get:
      summary: Create Connection
      description: Creates a new connection between the customer network and a specific
        AWS Direct Connect location.
      operationId: createConnection
      x-api-path-slug: actioncreateconnection-get
      parameters:
      - in: query
        name: bandwidth
        description: Bandwidth of the connection
        type: string
      - in: query
        name: connectionName
        description: The name of the connection
        type: string
      - in: query
        name: location
        description: Where the connection is located
        type: string
      responses:
        200:
          description: OK
      tags:
      - Connections
  /?Action=DeleteConnection:
    get:
      summary: Delete Connection
      description: Deletes the connection.
      operationId: deleteConnection
      x-api-path-slug: actiondeleteconnection-get
      parameters:
      - in: query
        name: connectionId
        description: ID of the connection
        type: string
      responses:
        200:
          description: OK
      tags:
      - Connections
  /?Action=DescribeConnectionLoa:
    get:
      summary: Describe Connection Loa
      description: Returns the LOA-CFA for a Connection.
      operationId: describeConnectionLoa
      x-api-path-slug: actiondescribeconnectionloa-get
      parameters:
      - in: query
        name: connectionId
        description: ID of the connection
        type: string
      - in: query
        name: loaContentType
        description: A standard media type indicating the content type of the LOA-CFA
          document
        type: string
      - in: query
        name: providerName
        description: The name of the APN partner or service provider who establishes
          connectivity on your behalf
        type: string
      responses:
        200:
          description: OK
      tags:
      - Connections
  /?Action=DescribeConnections:
    get:
      summary: Describe Connections
      description: Displays all connections in this region.
      operationId: describeConnections
      x-api-path-slug: actiondescribeconnections-get
      parameters:
      - in: query
        name: connectionId
        description: ID of the connection
        type: string
      responses:
        200:
          description: OK
      tags:
      - Connections
  /?Action=DescribeConnectionsOnInterconnect:
    get:
      summary: Describe Connections On Interconnect
      description: Return a list of connections that have been provisioned on the
        given interconnect.
      operationId: describeConnectionsOnInterconnect
      x-api-path-slug: actiondescribeconnectionsoninterconnect-get
      parameters:
      - in: query
        name: interconnectId
        description: ID of the interconnect on which a list of connection is provisioned
        type: string
      responses:
        200:
          description: OK
      tags:
      - Connections
  /?Action=CreateInterconnect:
    get:
      summary: Create Interconnect
      description: Creates a new interconnect between a AWS Direct Connect partner's
        network and a specific AWS Direct Connect location.
      operationId: createInterconnect
      x-api-path-slug: actioncreateinterconnect-get
      parameters:
      - in: query
        name: bandwidth
        description: The port bandwidth
        type: string
      - in: query
        name: interconnectName
        description: The name of the interconnect
        type: string
      - in: query
        name: location
        description: Where the interconnect is located
        type: string
      responses:
        200:
          description: OK
      tags:
      - Interconnects
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