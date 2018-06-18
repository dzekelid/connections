---
swagger: "2.0"
x-collection-name: Azure Virtual Network
x-complete: 1
info:
  title: NetworkManagementClient
  description: the-microsoft-azure-network-management-api-provides-a-restful-set-of-web-services-that-interact-with-microsoft-azure-networks-service-to-manage-your-network-resources--the-api-has-entities-that-capture-the-relationship-between-an-end-user-and-the-microsoft-azure-networks-service-
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
    get:
      summary: Virtual Network Gateway Connections Get Shared Key
      description: The Get VirtualNetworkGatewayConnectionSharedKey operation retrieves
        information about the specified virtual network gateway connection shared
        key through Network resource provider.
      operationId: VirtualNetworkGatewayConnections_GetSharedKey
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkconnectionsvirtualnetworkgatewayconnectionnamesharedkey-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: virtualNetworkGatewayConnectionName
        description: The virtual network gateway connection shared key name
      responses:
        200:
          description: OK
      tags:
      - Virtual Network Gateway Connections
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/connections:
    get:
      summary: Virtual Network Gateway Connections List
      description: The List VirtualNetworkGatewayConnections operation retrieves all
        the virtual network gateways connections created.
      operationId: VirtualNetworkGatewayConnections_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkconnections-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Virtual Network Gateway Connections
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/connections/{virtualNetworkGatewayConnectionName}/sharedkey/reset
  : post:
      summary: Virtual Network Gateway Connections Reset Shared Key
      description: The VirtualNetworkGatewayConnectionResetSharedKey operation resets
        the virtual network gateway connection shared key for passed virtual network
        gateway connection in the specified resource group through Network resource
        provider.
      operationId: VirtualNetworkGatewayConnections_ResetSharedKey
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkconnectionsvirtualnetworkgatewayconnectionnamesharedkeyreset-post
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to the begin reset virtual network gateway
          connection shared key operation through network resource provider
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: virtualNetworkGatewayConnectionName
        description: The virtual network gateway connection reset shared key Name
      responses:
        200:
          description: OK
      tags:
      - Virtual Network Gateway Connections
---