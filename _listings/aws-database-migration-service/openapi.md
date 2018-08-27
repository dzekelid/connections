swagger: "2.0"
x-collection-name: AWS Database Migration Service
x-complete: 1
info:
  title: AWS Database Migration Service API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeConnections:
    get:
      summary: Describe Connections
      description: Describes the status of the connections that have been made between
        the replication instance and an endpoint.
      operationId: describeConnections
      x-api-path-slug: actiondescribeconnections-get
      parameters:
      - in: query
        name: Filters
        description: The filters applied to the connection
        type: string
      - in: query
        name: Marker
        description: An optional pagination token provided by a previous      request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Connections
  /?Action=TestConnection:
    get:
      summary: Test Connection
      description: Tests the connection between the replication instance and the endpoint.
      operationId: testConnection
      x-api-path-slug: actiontestconnection-get
      parameters:
      - in: query
        name: EndpointArn
        description: The Amazon Resource Name (ARN) string that uniquely identifies
          the endpoint
        type: string
      - in: query
        name: ReplicationInstanceArn
        description: The Amazon Resource Name (ARN) of the replication instance
        type: string
      responses:
        200:
          description: OK
      tags:
      - Connections