{
  "info": {
    "name": "Yapily Returns the details of the application which owns the request credentials",
    "_postman_id": "b418bc98-e000-4db9-a30f-1fffacf52e19",
    "description": "Returns the details of the application which owns the request credentials.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Accounts",
      "item": [
        {
          "id": "ca9a412a-287f-450e-9cc8-b024a350b826",
          "name": "getAccountsUsingGET",
          "request": {
            "url": "http://api.yapily.com:443/accounts",
            "method": "GET",
            "header": [
              {
                "key": "consent",
                "value": "{}",
                "description": "Consent Token",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get accounts."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d3741798-b7b5-4b8a-ac92-2d02d2bc6c63"
            }
          ]
        }
      ]
    },
    {
      "name": "Account",
      "item": [
        {
          "id": "9dd5c196-2827-4e89-b0fa-3482565bd8d8",
          "name": "getAccountUsingGET",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.yapily.com",
              "path": [
                "accounts/:accountId"
              ],
              "port": "443",
              "variable": [
                {
                  "id": "accountId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "consent",
                "value": "{}",
                "description": "Consent Token",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3ba36c03-3cc6-4d30-a895-546cc19a4644"
            }
          ]
        },
        {
          "id": "9140b46b-1ce7-4b6d-bde1-8c6ca6db6351",
          "name": "getTransactionsUsingGET",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.yapily.com",
              "path": [
                "accounts/:accountId/transactions"
              ],
              "port": "443",
              "variable": [
                {
                  "id": "accountId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "consent",
                "value": "{}",
                "description": "Consent Token",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get account transactions."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "23b5ca8f-7362-48d8-8422-d64f0741d79c"
            }
          ]
        }
      ]
    },
    {
      "name": "Identity",
      "item": [
        {
          "id": "7446126d-138a-4f2e-a19a-737d32cb5d73",
          "name": "identityUsingGET",
          "request": {
            "url": "http://api.yapily.com:443/identity",
            "method": "GET",
            "header": [
              {
                "key": "consent",
                "value": "{}",
                "description": "Consent Token",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get identity."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6870fbf1-0007-4e19-8c89-7cf358d00055"
            }
          ]
        }
      ]
    },
    {
      "name": "Retrieves",
      "item": [
        {
          "id": "844be0bc-c793-4504-a014-76d86ec2395f",
          "name": "getInstitutionsUsingGET",
          "request": {
            "url": "http://api.yapily.com:443/institutions",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves the list of institutions available in yapily."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c4120f9c-07aa-4689-b0ee-75d5a8e10f0d"
            }
          ]
        },
        {
          "id": "72f533f1-3295-4c7a-a85f-c797058a6e2e",
          "name": "getInstitutionUsingGET",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.yapily.com",
              "path": [
                "institutions/:institutionId"
              ],
              "port": "443",
              "variable": [
                {
                  "id": "institutionId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves details of a specific institution available in yapily."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5954b6bb-5c2f-4c9d-8d36-d365fb453a82"
            }
          ]
        },
        {
          "id": "cb8cdc6b-5f0c-4a54-8666-8686d5e13f8f",
          "name": "getPersonalCurrentAccountsUsingGET",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.yapily.com",
              "path": [
                "institutions/:institutionId/personal-current-accounts"
              ],
              "port": "443",
              "variable": [
                {
                  "id": "institutionId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves details of personal current accounts for an institution."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "51204281-ed59-45ed-b8b0-f0814909673f"
            }
          ]
        }
      ]
    },
    {
      "name": "Returns",
      "item": [
        {
          "id": "20564925-7dcf-4019-878a-fd5d678b5d09",
          "name": "getApplicationMeUsingGET",
          "request": {
            "url": "http://api.yapily.com:443/me",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the details of the application which owns the request credentials."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e28706d2-5b62-4a6d-8b10-f41970afb195"
            }
          ]
        }
      ]
    }
  ]
}