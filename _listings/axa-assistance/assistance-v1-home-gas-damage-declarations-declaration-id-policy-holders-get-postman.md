{
  "info": {
    "name": "AXA Assistance Gets the policy holders details for the gas damage",
    "_postman_id": "b0e8814d-4350-461d-a62a-a81532392dd1",
    "description": "Gets the policy holders details for the gas damage",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "insurance",
      "item": [
        {
          "id": "2e028b3a-0fa7-4f09-bf2b-b304b8ddf685",
          "name": "getAssistanceV1HomeGas_damageDeclarationsDeclaration_idPolicy_holders",
          "request": {
            "url": {
              "protocol": "http",
              "host": "sandbox.api.axa-assistance.com",
              "path": [
                "assistance/v1/home/gas_damage/declarations/:declaration_id/policy_holders"
              ],
              "variable": [
                {
                  "id": "declaration_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the policy holders details for the gas damage"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "15341ffa-fab8-4388-9825-7a235e763396"
            }
          ]
        }
      ]
    }
  ]
}