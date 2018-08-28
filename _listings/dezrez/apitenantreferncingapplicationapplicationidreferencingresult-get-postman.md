{
  "info": {
    "name": "Dezrez Get the details of an individual application referencing result",
    "_postman_id": "ab88ebc3-a766-4840-a35b-8412f6a3254f",
    "description": "Get the details of an individual application referencing result.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Details",
      "item": [
        {
          "id": "974fa66f-7507-4111-b68d-cfc5e9152a70",
          "name": "TenantReferencing_GetApplicationStatusByapplicationId",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.dezrez.com",
              "path": [
                "api/tenantreferncing/application/:applicationId/referencingresult"
              ],
              "variable": [
                {
                  "id": "applicationId",
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
            "description": "Get the details of an individual application referencing result."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b177688d-dda3-4332-a0cc-ac374ce3fda6"
            }
          ]
        }
      ]
    }
  ]
}