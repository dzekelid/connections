---
swagger: "2.0"
x-collection-name: AWS Database Migration Service
x-complete: 0
info:
  title: AWS Database Migration Service API Describe Connections
  version: 1.0.0
  description: Describes the status of the connections that have been made between
    the replication instance and an endpoint.
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