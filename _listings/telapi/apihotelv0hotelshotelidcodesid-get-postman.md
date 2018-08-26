{
  "info": {
    "name": "hetras Hotel API Version 0 Get all the details for a specific code available for the hotel.",
    "_postman_id": "cccc922d-a869-4c2f-a29f-88327be1a8ed",
    "description": "Read the details about a specific code available for the defined hotel.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Codesthe",
      "item": [
        {
          "id": "4df1bbd0-758e-43cd-88aa-56ed4bb5a586",
          "name": "Codes_GetCodes",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.hetras-certification.net",
              "path": [
                "api/hotel/v0/hotels/:hotelId/codes"
              ],
              "query": [
                {
                  "key": "code",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "type",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "hotelId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "App-Id",
                "value": "{}",
                "description": "Application identifier",
                "disabled": false
              },
              {
                "key": "App-Key",
                "value": "{}",
                "description": "Application key",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "With this call you can find codes for a hotel by type or code. By default and without any filter criteria\r\n            defined it will return you all available codes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "78a4c63c-0c4f-4dd1-889c-b194d9d58b6d"
            }
          ]
        }
      ]
    },
    {
      "name": "Detailsa",
      "item": [
        {
          "id": "08184c5c-01bf-4f16-8b47-bdb7802244cb",
          "name": "Codes_GetCode",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.hetras-certification.net",
              "path": [
                "api/hotel/v0/hotels/:hotelId/codes/:id"
              ],
              "variable": [
                {
                  "id": "hotelId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "App-Id",
                "value": "{}",
                "description": "Application identifier",
                "disabled": false
              },
              {
                "key": "App-Key",
                "value": "{}",
                "description": "Application key",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Read the details about a specific code available for the defined hotel."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "256e317a-9034-4dfa-b311-a8c3787639c1"
            }
          ]
        }
      ]
    }
  ]
}