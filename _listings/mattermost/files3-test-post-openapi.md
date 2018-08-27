---
swagger: "2.0"
x-collection-name: Mattermost
x-complete: 0
info:
  title: Mattermost API Test AWS S3 connection
  description: |-
    Send a test to validate if can connect to AWS S3. Optionally provide a configuration in the request body to test. If no valid configuration is present in the request body the current server configuration will be tested.
    ##### Permissions
    Must have `manage_system` permission.
    __Minimum server version__: 4.8
  termsOfService: https://about.mattermost.com/default-terms/
  version: 4.0.0
host: your-mattermost-url.com
basePath: /api/v4
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /database/recycle:
    post:
      summary: Recycle database connections
      description: |-
        Recycle database connections by closing and reconnecting all connections to master and read replica databases.
        ##### Permissions
        Must have `manage_system` permission.
      operationId: recycle-database-connections-by-closing-and-reconnecting-all-connections-to-master-and-read-replica-
      x-api-path-slug: databaserecycle-post
      responses:
        200:
          description: OK
      tags:
      - Recycle
      - Database
      - Connections
  /file/s3_test:
    post:
      summary: Test AWS S3 connection
      description: |-
        Send a test to validate if can connect to AWS S3. Optionally provide a configuration in the request body to test. If no valid configuration is present in the request body the current server configuration will be tested.
        ##### Permissions
        Must have `manage_system` permission.
        __Minimum server version__: 4.8
      operationId: send-a-test-to-validate-if-can-connect-to-aws-s3-optionally-provide-a-configuration-in-the-request-b
      x-api-path-slug: files3-test-post
      parameters:
      - in: body
        name: body
        description: Mattermost configuration
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Test
      - AWS
      - S3
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