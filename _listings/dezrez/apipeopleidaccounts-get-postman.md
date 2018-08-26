{
  "info": {
    "name": "Dezrez Get the bank details for a person",
    "_postman_id": "c0c23a99-7237-41ec-9cc8-3babacf15c56",
    "description": "Get the bank details for a person.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Set",
      "item": [
        {
          "id": "fb79970f-26b1-4c46-a542-2fa4aaa366c0",
          "name": "AccountingSystem_SetPrimarySystemBankAccountByid",
          "request": {
            "url": "http://api.dezrez.com/api/accountingsystem/setprimaryaccount?id=%7B%7D",
            "method": "POST",
            "header": [
              {
                "key": "Rezi-Api-Version",
                "value": "{}",
                "description": "Specifies which version of the API to call",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Set primary bank account for accounting system."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b49a114e-db4e-4d14-8fc2-808f0faad192"
            }
          ]
        }
      ]
    },
    {
      "name": "Bank",
      "item": [
        {
          "id": "d57978b3-b40d-4d23-917e-e84fa0a4634b",
          "name": "People_GetPersonsAccountsByid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.dezrez.com",
              "path": [
                "api/people/:id/accounts"
              ],
              "variable": [
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
                "key": "Rezi-Api-Version",
                "value": "{}",
                "description": "Specifies which version of the API to call",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get the bank details for a person."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f88446cd-31e6-4bab-acf1-a6dd57bafb70"
            }
          ]
        }
      ]
    }
  ]
}