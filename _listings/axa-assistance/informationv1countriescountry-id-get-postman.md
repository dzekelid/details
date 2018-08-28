{
  "info": {
    "name": "AXA Assistance Retrieve a country detail",
    "_postman_id": "b71bf079-3871-4a3f-9d73-a9320640bc72",
    "description": "Retrieve a country detail",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "insurance",
      "item": [
        {
          "id": "90618829-e3d7-4dd5-bf93-c8cb456b538a",
          "name": "getInformationV1CountriesCountry_id",
          "request": {
            "url": {
              "protocol": "http",
              "host": "sandbox.api.axa-assistance.com",
              "path": [
                "information/v1/countries/:country_id"
              ],
              "variable": [
                {
                  "id": "country_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "accept-language",
                "value": "{}",
                "description": "Language/Country",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve a country detail"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d82a3819-4383-48bd-a2f8-9f5ad09e408e"
            }
          ]
        }
      ]
    }
  ]
}