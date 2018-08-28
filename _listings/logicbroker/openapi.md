swagger: "2.0"
x-collection-name: Logicbroker
x-complete: 1
info:
  title: CommerceAPI
  version: 1.0.0
host: stage.commerceapi.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/Webhooks/{WebhookId}:
    get:
      summary: Get webhook details
      description: Request rate limited to 10 requests per second with bursts up to
        100 requests.
      operationId: Webhook_GetWebhook
      x-api-path-slug: apiv1webhookswebhookid-get
      parameters:
      - in: path
        name: WebhookId
        description: The webhook id
      responses:
        200:
          description: OK
      tags:
      - Webhook
      - Details
  /api/v1/Shipments/{LogicbrokerKey}:
    put:
      summary: Update shipment details
      description: Request rate limited to 10 requests per second with bursts up to
        100 requests.
      operationId: Shipment_UpdateShipment
      x-api-path-slug: apiv1shipmentslogicbrokerkey-put
      parameters:
      - in: path
        name: LogicbrokerKey
        description: The Logicbroker key
      - in: body
        name: Shipment
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Shipment
      - Details
    get:
      summary: Get shipment details
      description: Request rate limited to 10 requests per second with bursts up to
        100 requests.
      operationId: Shipment_GetShipment
      x-api-path-slug: apiv1shipmentslogicbrokerkey-get
      parameters:
      - in: path
        name: LogicbrokerKey
        description: The Logicbroker key
      responses:
        200:
          description: OK
      tags:
      - Shipment
      - Details
  /api/v1/Returns/{LogicbrokerKey}:
    get:
      summary: Get return details
      description: Request rate limited to 10 requests per second with bursts up to
        100 requests.
      operationId: Return_GetReturn
      x-api-path-slug: apiv1returnslogicbrokerkey-get
      parameters:
      - in: path
        name: LogicbrokerKey
      responses:
        200:
          description: OK
      tags:
      - Return
      - Details
  /api/v1/Acknowledgements/{LogicbrokerKey}:
    get:
      summary: Get acknowledgement details
      description: Request rate limited to 10 requests per second with bursts up to
        100 requests.
      operationId: Acknowledgement_GetAck
      x-api-path-slug: apiv1acknowledgementslogicbrokerkey-get
      parameters:
      - in: path
        name: LogicbrokerKey
      responses:
        200:
          description: OK
      tags:
      - Acknowledgement
      - Details