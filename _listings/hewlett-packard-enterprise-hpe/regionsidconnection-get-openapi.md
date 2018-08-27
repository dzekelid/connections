---
swagger: "2.0"
x-collection-name: Hewlett Packard Enterprise (HPE)
x-complete: 0
info:
  title: HPE OneSphere API Get Regions Connection
  description: Get region connection.
  termsOfService: http://www.hpe.com/onesphere
  contact:
    name: HPE OneSphere API team
    url: http://www.hpe.com/onesphere
  version: 1.0.0
host: deic02-hpe.hpeonesphere.com
basePath: /rest
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /zones/{id}/connections:
    get:
      summary: Get Zones Connections
      description: Gets the list of connection for the zone. It requires the **administrator**
        role.
      operationId: zoneConnectionInstances
      x-api-path-slug: zonesidconnections-get
      parameters:
      - in: path
        name: id
        description: ID of zone to fetch the list of connection for the zone
      - in: query
        name: uuid
        description: Type to filter connection by
      responses:
        200:
          description: OK
      tags:
      - Zones
      - Connections
    post:
      summary: Post Zones Connections
      description: Peforms an action to the zone. It requires the **administrator**
        role.
      operationId: RegisterZoneConnection
      x-api-path-slug: zonesidconnections-post
      parameters:
      - in: path
        name: id
        description: ID of zone to act on
      - in: body
        name: zoneConnection
        description: Create a new connection instance for the zone
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Zones
      - Connections
  /zones/{id}/connections/{uuid}:
    delete:
      summary: Delete Zones Connections Uu
      description: Deletes a connection instance of the zone
      operationId: UnregisterZoneConnection
      x-api-path-slug: zonesidconnectionsuuid-delete
      parameters:
      - in: path
        name: id
        description: ID of zone
      - in: path
        name: uuid
        description: ID of connection
      responses:
        200:
          description: OK
      tags:
      - Zones
      - Connections
      - Uu
    patch:
      summary: Patch Zones Connections Uu
      description: Updates a connection of the zone.
      operationId: UpdateZoneConnection
      x-api-path-slug: zonesidconnectionsuuid-patch
      parameters:
      - in: path
        name: id
        description: ID of zone
      - in: path
        name: uuid
        description: ID of connection
      - in: body
        name: zoneConnection
        description: Update connection
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Zones
      - Connections
      - Uu
  /regions/{id}/connection:
    delete:
      summary: Delete Regions Connection
      description: ""
      operationId: DeleteRegionConnection
      x-api-path-slug: regionsidconnection-delete
      parameters:
      - in: path
        name: id
        description: ID of region
      responses:
        200:
          description: OK
      tags:
      - Regions
      - Connection
    get:
      summary: Get Regions Connection
      description: Get region connection.
      operationId: GetRegionConnection
      x-api-path-slug: regionsidconnection-get
      parameters:
      - in: path
        name: id
        description: ID of region
      responses:
        200:
          description: OK
      tags:
      - Regions
      - Connection
    post:
      summary: Post Regions Connection
      description: Creates a new region connection
      operationId: CreateRegionConnection
      x-api-path-slug: regionsidconnection-post
      parameters:
      - in: path
        name: id
        description: ID of region
      - in: body
        name: regionConnection
        description: Add new region connection
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Regions
      - Connection
  /connect-app:
    get:
      summary: Get Connect App
      description: Generates connect app s3 url
      operationId: connect-app
      x-api-path-slug: connectapp-get
      parameters:
      - in: query
        name: os
        description: OS type for which compatible connect app URL has to be generated
      responses:
        200:
          description: OK
      tags:
      - Connect
      - App
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