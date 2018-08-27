---
swagger: "2.0"
x-collection-name: Google Doubleclick
x-complete: 0
info:
  title: Google Doubleclick API Get Connection Type
  version: 1.0.0
  description: Gets one connection type by ID.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /userprofiles/{profileId}/connectionTypes:
    get:
      summary: Get Connection Types
      description: Retrieves a list of connection types.
      operationId: dfareporting.connectionTypes.list
      x-api-path-slug: userprofilesprofileidconnectiontypes-get
      parameters:
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Connection Type
  /userprofiles/{profileId}/connectionTypes/{id}:
    get:
      summary: Get Connection Type
      description: Gets one connection type by ID.
      operationId: dfareporting.connectionTypes.get
      x-api-path-slug: userprofilesprofileidconnectiontypesid-get
      parameters:
      - in: path
        name: id
        description: Connection type ID
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Connection Type
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