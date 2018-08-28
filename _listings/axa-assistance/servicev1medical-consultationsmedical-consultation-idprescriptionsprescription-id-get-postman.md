{
  "info": {
    "name": "AXA Assistance Provides detail of a prescription",
    "_postman_id": "c1d98ff4-cfad-4866-8da6-6983d50d7452",
    "description": "Provides detail of a prescription",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "insurance",
      "item": [
        {
          "id": "4b47df6e-622b-4999-b084-8557a7c19a60",
          "name": "getServiceV1Medical_consultationsMedical_consultation_idPrescriptionsPrescription_id",
          "request": {
            "url": {
              "protocol": "http",
              "host": "sandbox.api.axa-assistance.com",
              "path": [
                "service/v1/medical_consultations/:medical_consultation_id/prescriptions/:prescription_id"
              ],
              "variable": [
                {
                  "id": "medical_consultation_id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "prescription_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Provides detail of a prescription"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bbb31ce3-7e8f-4d15-9ce8-98e6a2924900"
            }
          ]
        }
      ]
    }
  ]
}