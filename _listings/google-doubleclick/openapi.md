---
swagger: "2.0"
x-collection-name: Google Doubleclick
x-complete: 1
info:
  title: Google Doubleclick Merged API
  version: 1.0.0
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
---