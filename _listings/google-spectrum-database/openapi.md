swagger: "2.0"
x-collection-name: Google Spectrum Database
x-complete: 1
info:
  title: Google Spectrum Database
  description: api-for-spectrummanagement-functions-
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