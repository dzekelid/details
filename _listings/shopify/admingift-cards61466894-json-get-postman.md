{
  "info": {
    "name": "Shopify Show a specific gift card's details",
    "_postman_id": "5ef5400a-f13c-4c28-8f96-926bc6a3d9c1",
    "description": "Show a specific gift card's details.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Commerce",
      "item": [
        {
          "id": "edd63657-5271-4bee-b1f7-f5ee15e137d3",
          "name": "getAdminGiftCards61466894.json",
          "request": {
            "url": "http://DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com/admin/gift_cards/61466894.json",
            "method": "GET",
            "header": [
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Show a specific gift card's details."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5420f0fa-2f5a-4155-8b9c-f5b047dfaf1f"
            }
          ]
        }
      ]
    }
  ]
}