swagger: "2.0"
x-collection-name: Zencoder
x-complete: 1
info:
  title: Zencoder
  version: v2
host: app.zencoder.com
basePath: /api/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /account:
    get:
      summary: Get Account Details
      description: Get Account Details
      operationId: getAccount
      x-api-path-slug: account-get
      parameters:
      - in: query
        name: api_key
        description: The API key
      responses:
        200:
          description: OK
      tags:
      - Account