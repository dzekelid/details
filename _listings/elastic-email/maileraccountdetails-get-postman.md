{
  "info": {
    "name": "Elastic Email SMTP API Account Details",
    "_postman_id": "32f54568-44dc-47dc-95f8-b4526b4b0ba0",
    "description": "The Account Details command is used to determine how much credit you have left.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Mailer",
      "item": [
        {
          "id": "f8975de5-d287-4bb1-81fc-b06277b22556",
          "name": "getMailerAccountDetails",
          "request": {
            "url": "http://api.elasticemail.com/mailer/account-details?api_key=%7B%7D&username=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "The Account Details command is used to determine how much credit you have left."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e2e16304-10e7-44d5-9f48-32b67bec991b"
            }
          ]
        }
      ]
    }
  ]
}