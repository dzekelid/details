---
swagger: "2.0"
x-collection-name: ChainGenie
x-complete: 0
info:
  title: ChainGenie Get contract details & state
  description: "Get contract details & state\n- Provide full information including\n
    - Escrow amount in contract\n - Contract state \n - Buyer & Seller information\n
    - Links to contract / invoice documents\n - and other contract / sale specific
    information"
  version: "1.0"
host: api.chaingenie.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /tradechain/GetFundsLockedInContract:
    post:
      summary: Get contract escrow details
      description: "Get contract escrow details -\n- Retrieves full information including
        but not limited to\n - Escrow amount in contract\n - Contract state \n - Buyer
        & Seller information\n - Links to contract / invoice documents\n - and other
        contract / sale specific information"
      operationId: TradechainGetFundsLockedInContractPost
      x-api-path-slug: tradechaingetfundslockedincontract-post
      parameters:
      - in: header
        name: ApiKey
      - in: formData
        name: itemContractId
      responses:
        200:
          description: OK
      tags:
      - Blockchain
      - Contract
      - Escrow
      - Details
  /tradechain/GetStateOfContract:
    post:
      summary: Get contract details & state
      description: "Get contract details & state\n- Provide full information including\n
        - Escrow amount in contract\n - Contract state \n - Buyer & Seller information\n
        - Links to contract / invoice documents\n - and other contract / sale specific
        information"
      operationId: TradechainGetStateOfContractPost
      x-api-path-slug: tradechaingetstateofcontract-post
      parameters:
      - in: header
        name: ApiKey
      - in: formData
        name: itemContractId
      responses:
        200:
          description: OK
      tags:
      - Blockchain
      - Contract
      - Details
      - '&'
      - State
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