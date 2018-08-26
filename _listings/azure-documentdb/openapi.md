---
swagger: "2.0"
x-collection-name: Azure DocumentDB
x-complete: 1
info:
  title: DocumentDB
  description: azure-documentdb-database-service-resource-provider-rest-api
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DocumentDB/databaseAccounts/{accountName}/listConnectionStrings
  : post:
      summary: Database Accounts List Connection Strings
      description: Lists the connection strings for the specified Azure DocumentDB
        database account.
      operationId: DatabaseAccounts_ListConnectionStrings
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-documentdbdatabaseaccountsaccountnamelistconnectionstrings-post
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Database
      - Accounts
      - List
      - Connection
      - Strings
---