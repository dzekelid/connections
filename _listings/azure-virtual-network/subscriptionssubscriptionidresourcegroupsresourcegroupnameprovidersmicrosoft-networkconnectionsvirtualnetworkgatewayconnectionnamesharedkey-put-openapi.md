---
swagger: "2.0"
x-collection-name: Azure Virtual Network
x-complete: 0
info:
  title: Azure Virtual Network API Virtual Network Gateway Connections Set Shared
    Key
  description: The Put VirtualNetworkGatewayConnectionSharedKey operation sets the
    virtual network gateway connection shared key for passed virtual network gateway
    connection in the specified resource group through Network resource provider.
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
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/connections/{virtualNetworkGatewayConnectionName}
  : put:
      summary: Virtual Network Gateway Connections Create Or Update
      description: Creates or updates a virtual network gateway connection in the
        specified resource group.
      operationId: VirtualNetworkGatewayConnections_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkconnectionsvirtualnetworkgatewayconnectionname-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to the create or update virtual network gateway
          connection operation
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: virtualNetworkGatewayConnectionName
        description: The name of the virtual network gateway connection
      responses:
        200:
          description: OK
      tags:
      - Virtual Network Gateway Connections
    get:
      summary: Virtual Network Gateway Connections Get
      description: Gets the specified virtual network gateway connection by resource
        group.
      operationId: VirtualNetworkGatewayConnections_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkconnectionsvirtualnetworkgatewayconnectionname-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: virtualNetworkGatewayConnectionName
        description: The name of the virtual network gateway connection
      responses:
        200:
          description: OK
      tags:
      - Virtual Network Gateway Connections
    delete:
      summary: Virtual Network Gateway Connections Delete
      description: Deletes the specified virtual network Gateway connection.
      operationId: VirtualNetworkGatewayConnections_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkconnectionsvirtualnetworkgatewayconnectionname-delete
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: virtualNetworkGatewayConnectionName
        description: The name of the virtual network gateway connection
      responses:
        200:
          description: OK
      tags:
      - Virtual Network Gateway Connections
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/connections/{virtualNetworkGatewayConnectionName}/sharedkey
  : put:
      summary: Virtual Network Gateway Connections Set Shared Key
      description: The Put VirtualNetworkGatewayConnectionSharedKey operation sets
        the virtual network gateway connection shared key for passed virtual network
        gateway connection in the specified resource group through Network resource
        provider.
      operationId: VirtualNetworkGatewayConnections_SetSharedKey
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkconnectionsvirtualnetworkgatewayconnectionnamesharedkey-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to the Begin Set Virtual Network Gateway
          connection Shared key operation throughNetwork resource provider
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: virtualNetworkGatewayConnectionName
        description: The virtual network gateway connection name
      responses:
        200:
          description: OK
      tags:
      - Virtual Network Gateway Connections
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