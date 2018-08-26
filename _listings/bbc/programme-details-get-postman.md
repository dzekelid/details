{
  "info": {
    "name": "BBC Nitro Exposes programme information for a single pid",
    "_postman_id": "283b7c6a-5fb0-41f4-95fa-dd3d3366b8f3",
    "description": "Exposes programme information for a single pid",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Programme",
      "item": [
        {
          "id": "05164db2-cb3d-44d9-b311-35b58cfed3c8",
          "name": "listProgrammeDetails",
          "request": {
            "url": "http://programmes.api.bbc.com/nitro/api/programme_details?page=%7B%7D&page_size=%7B%7D&partner_pid=%7B%7D&pid=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Exposes programme information for a single pid"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "47b0e53e-0246-4e61-9626-89bae0955d1b"
            }
          ]
        }
      ]
    }
  ]
}