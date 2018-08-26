---
swagger: "2.0"
x-collection-name: Google People
x-complete: 0
info:
  title: Google People API Get Connections
  description: |-
    Provides a list of the authenticated user's contacts merged with any
    linked profiles.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: people.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/{resourceName}/connections:
    get:
      summary: Get Connections
      description: |-
        Provides a list of the authenticated user's contacts merged with any
        linked profiles.
      operationId: people.people.connections.list
      x-api-path-slug: v1resourcenameconnections-get
      parameters:
      - in: query
        name: pageSize
        description: The number of connections to include in the response
      - in: query
        name: pageToken
        description: The token of the page to be returned
      - in: query
        name: requestMask.includeField
        description: Comma-separated list of fields to be included in the response
      - in: query
        name: requestSyncToken
        description: Whether the response should include a sync token, which can be
          used to getall changes since the last request
      - in: path
        name: resourceName
        description: The resource name to return connections for
      - in: query
        name: sortOrder
        description: The order in which the connections should be sorted
      - in: query
        name: syncToken
        description: A sync token, returned by a previous call to `people
      responses:
        200:
          description: OK
      tags:
      - Connection
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