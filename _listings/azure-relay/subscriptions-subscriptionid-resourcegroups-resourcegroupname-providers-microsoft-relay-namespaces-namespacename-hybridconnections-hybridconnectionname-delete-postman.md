{
  "info": {
    "name": "Azure Relay API Hybrid Connections Delete",
    "_postman_id": "e2b5db4a-918b-4f71-97bb-234b5efa55e0",
    "description": "Deletes a HybridConnection .",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "hybrid connections",
      "item": [
        {
          "id": "c4c1f2ad-2731-4014-819a-aa0f2b6afad3",
          "name": "HybridConnections_Delete",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Relay/namespaces/:namespaceName/HybridConnections/:hybridConnectionName"
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
                  "id": "subscriptionId",
                  "value": "subscriptionId",
                  "type": "string"
                },
                {
                  "id": "resourceGroupName",
                  "value": "resourceGroupName",
                  "type": "string"
                },
                {
                  "id": "namespaceName",
                  "value": "namespaceName",
                  "type": "string"
                },
                {
                  "id": "hybridConnectionName",
                  "value": "hybridConnectionName",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a HybridConnection "
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8543b791-9706-4753-abe8-9b74e93bb683"
            }
          ]
        }
      ]
    }
  ]
}