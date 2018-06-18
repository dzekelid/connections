{
  "info": {
    "name": "Azure Virtual Network API Virtual Network Gateway Connections Get Shared Key",
    "_postman_id": "d11dde39-043f-4f74-ab13-aea3850df85b",
    "description": "The Get VirtualNetworkGatewayConnectionSharedKey operation retrieves information about the specified virtual network gateway connection shared key through Network resource provider.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "virtual network gateway connections",
      "item": [
        {
          "id": "e3683a2b-dd89-414a-b777-ab5839a4f34a",
          "name": "VirtualNetworkGatewayConnections_GetSharedKey",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Network/connections/:virtualNetworkGatewayConnectionName/sharedkey"
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
            "description": "The Get VirtualNetworkGatewayConnectionSharedKey operation retrieves information about the specified virtual network gateway connection shared key through Network resource provider"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5089ec15-6c93-436c-9a8e-33711ebccda8"
            }
          ]
        }
      ]
    }
  ]
}