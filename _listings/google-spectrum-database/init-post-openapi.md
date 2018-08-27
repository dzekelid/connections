---
swagger: "2.0"
x-collection-name: Google Spectrum Database
x-complete: 0
info:
  title: Google Spectrum Database API Initialize Connection
  description: Initializes the connection between a white space device and the database.
  contact:
    name: Google
    url: https://google.com
  version: v1explorer
host: www.googleapis.com
basePath: /spectrum/v1explorer/paws
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /init:
    post:
      summary: Initialize Connection
      description: Initializes the connection between a white space device and the
        database.
      operationId: spectrum.paws.init
      x-api-path-slug: init-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
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