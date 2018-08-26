---
swagger: "2.0"
x-collection-name: Hewlett Packard Enterprise (HPE)
x-complete: 0
info:
  title: HPE OneSphere API Get Zones Connections
  description: Gets the list of connection for the zone. It requires the **administrator**
    role.
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