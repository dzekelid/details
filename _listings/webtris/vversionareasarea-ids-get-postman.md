{
  "info": {
    "name": "WebTRIS Traffic Flow API Returns details of selected area",
    "_postman_id": "76acb07f-e4a2-4e91-87f5-429650d36b60",
    "description": "Returns details of selected area.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Returns",
      "item": [
        {
          "id": "5bffebd8-1231-4cba-b994-2701270e43db",
          "name": "Areas_Get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "webtris.highwaysengland.co.uk",
              "path": [
                "api",
                "v:version/areas"
              ],
              "variable": [
                {
                  "id": "version",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns list of areas."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b316a8db-b85a-4f6e-b13e-ff3efe4553aa"
            }
          ]
        },
        {
          "id": "cf7cc901-24b3-4c70-b36c-7bf9241d88ab",
          "name": "Areas_Get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "webtris.highwaysengland.co.uk",
              "path": [
                "api",
                "v:version/areas/:area_Ids"
              ],
              "variable": [
                {
                  "id": "area_Ids",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "version",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns details of selected area."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "648cb2d8-478f-40bb-87e0-797f5364a304"
            }
          ]
        }
      ]
    }
  ]
}