{
  "info": {
    "name": "Azure Virtual Network API Virtual Network Gateway Connections List",
    "_postman_id": "50af7bcb-9f33-46ea-8e4a-3bf9efe929d8",
    "description": "The List VirtualNetworkGatewayConnections operation retrieves all the virtual network gateways connections created.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "virtual network gateway connections",
      "item": [
        {
          "id": "4d532e5f-3fee-4aab-bcaa-71cf88200838",
          "name": "VirtualNetworkGatewayConnections_List",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Network/connections"
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
            "description": "The List VirtualNetworkGatewayConnections operation retrieves all the virtual network gateways connections created"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b7859659-d1d0-4d87-a4a1-0e3365ba71cd"
            }
          ]
        }
      ]
    }
  ]
}