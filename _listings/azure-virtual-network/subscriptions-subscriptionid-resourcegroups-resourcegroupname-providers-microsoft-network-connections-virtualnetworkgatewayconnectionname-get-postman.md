{
  "info": {
    "name": "Azure Virtual Network API Virtual Network Gateway Connections Get",
    "_postman_id": "5462697a-445a-4538-9b77-b6d874c13315",
    "description": "Gets the specified virtual network gateway connection by resource group.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "virtual network gateway connections",
      "item": [
        {
          "id": "74e6f421-7f8a-4edf-8d17-55c3e3a4b161",
          "name": "VirtualNetworkGatewayConnections_Get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Network/connections/:virtualNetworkGatewayConnectionName"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "resourceGroupName",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "virtualNetworkGatewayConnectionName",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "subscriptionId",
                  "value": "subscriptionId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the specified virtual network gateway connection by resource group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "104b926b-7b06-4605-b5c5-698fe656d59a"
            }
          ]
        }
      ]
    }
  ]
}