swagger: "2.0"
x-collection-name: Shopify
x-complete: 1
info:
  title: Shopify API
  description: todo-add-description
  version: 1.0.0
host: DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /admin/gift_cards/61466894.json:
    get:
      summary: Show a specific gift card's details
      description: Show a specific gift card's details.
      operationId: getAdminGiftCards61466894.json
      x-api-path-slug: admingift-cards61466894-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Show
      - Specific
      - Gift
      - Cards
      - Details
  /admin/orders/4602125518/risks/8609858574.json:
    put:
      summary: Update an existing risk detail line on an order
      description: Update an existing risk detail line on an order.
      operationId: putAdminOrders4602125518Risks8609858574.json
      x-api-path-slug: adminorders4602125518risks8609858574-json-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Existing
      - Risk
      - Detail
      - Line
      - "On"
      - Order