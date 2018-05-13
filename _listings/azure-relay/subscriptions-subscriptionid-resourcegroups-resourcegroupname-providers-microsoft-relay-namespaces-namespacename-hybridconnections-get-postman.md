{
  "info": {
    "name": "Azure Relay API Hybrid Connections List By Namespace",
    "_postman_id": "db46edef-dd5b-487c-ae09-04729358a7d0",
    "description": "Lists the HybridConnection within the namespace.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "hybrid connections namespace",
      "item": [
        {
          "id": "83d1610a-535e-47ad-a861-6fcc043b31e4",
          "name": "HybridConnections_ListByNamespace",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Relay/namespaces/:namespaceName/HybridConnections"
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
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the HybridConnection within the namespace"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c58872aa-87d1-4cff-bd19-216fd0a7c8e9"
            }
          ]
        }
      ]
    }
  ]
}