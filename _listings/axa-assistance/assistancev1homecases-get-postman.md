{
  "info": {
    "name": "AXA Assistance Gets details of cases",
    "_postman_id": "0d88dc37-c86b-4c6f-8bcf-e484f949dad5",
    "description": "Gets details of cases",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "insurance",
      "item": [
        {
          "id": "7f72cff9-d17a-4443-a75f-6e641057ae5f",
          "name": "getAssistanceV1HomeCases",
          "request": {
            "url": "http://sandbox.api.axa-assistance.com/assistance/v1/home/cases?declaration_id=%7B%7D&lastname=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets details of cases"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e6cdd0a6-b3d2-4c0e-81a5-810ed14a5968"
            }
          ]
        }
      ]
    }
  ]
}