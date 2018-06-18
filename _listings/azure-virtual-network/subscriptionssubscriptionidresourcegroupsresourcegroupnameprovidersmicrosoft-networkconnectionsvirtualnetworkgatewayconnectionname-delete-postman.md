{
  "info": {
    "name": "Azure Virtual Network API Virtual Network Gateway Connections Delete",
    "_postman_id": "9e93b6e8-3b04-42aa-99f9-c21e0d182a13",
    "description": "Deletes the specified virtual network Gateway connection.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "virtual network gateway connections",
      "item": [
        {
          "id": "53125af1-f8b1-4b41-aa63-6add80260213",
          "name": "VirtualNetworkGatewayConnections_Delete",
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
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified virtual network Gateway connection"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "804fe992-e414-4e5f-abe3-2525e7d57437"
            }
          ]
        }
      ]
    }
  ]
}