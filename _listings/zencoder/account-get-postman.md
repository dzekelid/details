{
  "info": {
    "name": "Zencoder API Get Account Details",
    "_postman_id": "babb6d9f-b5b9-4cfe-8eb2-a119299404a7",
    "description": "Get Account Details",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Account",
      "item": [
        {
          "id": "f5c9d823-ee87-49bf-a73c-f830b8b37cc4",
          "name": "getAccount",
          "request": {
            "url": "http://app.zencoder.com/api/v2/account?api_key=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Account Details"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "11e80b17-3f14-45dc-bf4e-b5a5822c5a95"
            }
          ]
        }
      ]
    }
  ]
}