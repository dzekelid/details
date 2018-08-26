{
  "info": {
    "name": "AXA Assistance Gets the policy holders details for the electric damage",
    "_postman_id": "3e93e078-1e71-450e-8f4e-72fcba6876a2",
    "description": "Gets the policy holders details for the electric damage",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "insurance",
      "item": [
        {
          "id": "00f120e6-5dc6-4320-83e2-8b1f4f84ccd2",
          "name": "getAssistanceV1HomeElectric_damageDeclarationsDeclaration_idPolicy_holders",
          "request": {
            "url": {
              "protocol": "http",
              "host": "sandbox.api.axa-assistance.com",
              "path": [
                "assistance/v1/home/electric_damage/declarations/:declaration_id/policy_holders"
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
            "description": "Gets the policy holders details for the electric damage"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f67c663b-93d5-484a-af61-045e6e420480"
            }
          ]
        }
      ]
    }
  ]
}