{
  "info": {
    "name": "AXA Assistance Provides detail of a medical consultation",
    "_postman_id": "aa11cbbb-4bed-4d4c-a2b4-e90d621fb97f",
    "description": "Provides detail of a medical consultation",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "insurance",
      "item": [
        {
          "id": "10b6b8e3-ad5e-427e-9c35-5959b9b061b6",
          "name": "getServiceV1Medical_consultationsMedical_consultation_id",
          "request": {
            "url": {
              "protocol": "http",
              "host": "sandbox.api.axa-assistance.com",
              "path": [
                "service/v1/medical_consultations/:medical_consultation_id"
              ],
              "variable": [
                {
                  "id": "medical_consultation_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Provides detail of a medical consultation"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f68993c7-2f28-42b9-b0ed-8613fed49b88"
            }
          ]
        }
      ]
    }
  ]
}