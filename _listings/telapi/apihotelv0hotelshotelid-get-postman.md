{
  "info": {
    "name": "hetras Hotel API Version 0 Get the details of the hotel with the speccified hotel id.",
    "_postman_id": "66cf4822-32bc-4983-ae01-3e00fe803af1",
    "description": "Get the details of the hotel with the speccified hotel id..",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Folder",
      "item": [
        {
          "id": "74367a94-f0c2-48a0-8f17-45c50e3ddf63",
          "name": "Hotels_GetHotels",
          "request": {
            "url": "http://api.hetras-certification.net/api/hotel/v0/hotels",
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
            "description": "Get a list of all the hotels of a chain your application has access to.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0b26439f-5815-4f03-aada-8dc0fa641c98"
            }
          ]
        }
      ]
    },
    {
      "name": "Details",
      "item": [
        {
          "id": "ffc18d11-d533-452b-9c6a-03a116d04e88",
          "name": "Hotels_GetHotel",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.hetras-certification.net",
              "path": [
                "api/hotel/v0/hotels/:hotelId"
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
            "description": "Get the details of the hotel with the speccified hotel id.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "63312e3b-cbf7-4d9e-b9b8-5dbd15c2200a"
            }
          ]
        }
      ]
    }
  ]
}