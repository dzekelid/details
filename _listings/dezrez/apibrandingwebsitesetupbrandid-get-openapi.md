---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Get files and details that can be used to customize a website
  version: 1.0.0
  description: Get files and details that can be used to customize a website.
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/account/{id}/update:
    put:
      summary: Update account details
      description: Update account details.
      operationId: Account_UpdateAccountDetailsByidBydetailsDataContract
      x-api-path-slug: apiaccountidupdate-put
      parameters:
      - in: body
        name: detailsDataContract
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Account
      - Details
  /api/accounting/exports/batchpaymentcsv:
    post:
      summary: Get details formatted for batch payment csv
      description: Get details formatted for batch payment csv.
      operationId: AccountingExport_ExportBatchPaymentBydataContract
      x-api-path-slug: apiaccountingexportsbatchpaymentcsv-post
      parameters:
      - in: body
        name: dataContract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Details
      - Formattedbatch
      - Payment
      - Csv
  /api/Agency:
    get:
      summary: Get details of the current users agency
      description: Get details of the current users agency.
      operationId: Agency_Get
      x-api-path-slug: apiagency-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Details
      - Of
      - Current
      - Users
      - Agency
  /api/appointment/{id}/Date/{date}:
    get:
      summary: Get details of a calculated appointment using it's id and date.
      description: Get details of a calculated appointment using it's id and date..
      operationId: Appointment_GetByidBydate
      x-api-path-slug: apiappointmentiddatedate-get
      parameters:
      - in: path
        name: date
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Details
      - Of
      - Calculated
      - Appointment
      - Using
      - Its
      - Id
      - Date
  /api/auction/{id}/recordbid:
    post:
      summary: Record auction bid details
      description: Record auction bid details.
      operationId: Auction_ReccordAuctionBidByidBydataContactDataContract
      x-api-path-slug: apiauctionidrecordbid-post
      parameters:
      - in: body
        name: dataContactDataContract
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Record
      - Auction
      - Bid
      - Details
  /api/branding/websitesetup/{brandId}:
    get:
      summary: Get files and details that can be used to customize a website
      description: Get files and details that can be used to customize a website.
      operationId: Branding_WebsiteSetupBybrandId
      x-api-path-slug: apibrandingwebsitesetupbrandid-get
      parameters:
      - in: path
        name: brandId
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Files
      - Details
      - That
      - Can
      - Be
      - Used
      - To
      - Customize
      - Website
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