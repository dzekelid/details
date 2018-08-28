---
swagger: "2.0"
x-collection-name: Logicbroker
x-complete: 0
info:
  title: Logic Broker CommerceAPI Get return details
  version: 1.0.0
  description: Request rate limited to 10 requests per second with bursts up to 100
    requests.
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
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---