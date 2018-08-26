---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Get the details of an individual application referencing result
  version: 1.0.0
  description: Get the details of an individual application referencing result.
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
  /api/people/unsubscribe/{id}:
    get:
      summary: Get All contact items for a person, but obscure the details
      description: Get all contact items for a person, but obscure the details.
      operationId: People_ObscuredContactItemsByid
      x-api-path-slug: apipeopleunsubscribeid-get
      parameters:
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Itemsa
      - Person
      - ""
      - But
      - Obscure
      - Details
  /api/people/{id}/updatedetails:
    put:
      summary: Update a Persons Details
      description: Update a persons details.
      operationId: People_UpdateDetailsByidBydetailsCommand
      x-api-path-slug: apipeopleidupdatedetails-put
      parameters:
      - in: body
        name: detailsCommand
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
      - Persons
      - Details
  /api/posting/transaction/{ledgerEntryId}:
    get:
      summary: Get ledger entry details by Id
      description: Get ledger entry details by id.
      operationId: Posting_GetTransactionByledgerEntryIdByaccountId
      x-api-path-slug: apipostingtransactionledgerentryid-get
      parameters:
      - in: query
        name: accountId
        description: Account Id to filter ledger lines
      - in: path
        name: ledgerEntryId
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Ledger
      - Entry
      - Details
      - By
      - Id
  /api/tenantreferncing/addapplication/{caseId}/{tenancyRoleId}/{personId}/{productId}:
    post:
      summary: Creates a tenancy referencing application for a case using the details
        supplied
      description: Creates a tenancy referencing application for a case using the
        details supplied.
      operationId: TenantReferencing_CreateApplicationBycaseIdBytenancyRoleIdBypersonIdByproductId
      x-api-path-slug: apitenantreferncingaddapplicationcaseidtenancyroleidpersonidproductid-post
      parameters:
      - in: path
        name: caseId
        description: The id of the case to add the Application to
      - in: path
        name: personId
        description: The id of the individual the application is for
      - in: path
        name: productId
        description: The id of the product the client has chosen
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: tenancyRoleId
        description: The role id of the tenancy the case is linked to
      responses:
        200:
          description: OK
      tags:
      - Creates
      - Tenancy
      - Referencing
      - Applicationa
      - Case
      - Using
      - Details
      - Supplied
  /api/tenantreferncing/addguarantor/{caseId}/{tenancyRoleId}/{personId}:
    post:
      summary: Adds a Guarantor to a tenancy referencing application for a case using
        the details supplied
      description: Adds a guarantor to a tenancy referencing application for a case
        using the details supplied.
      operationId: TenantReferencing_CreateApplicationBycaseIdBytenancyRoleIdBypersonId
      x-api-path-slug: apitenantreferncingaddguarantorcaseidtenancyroleidpersonid-post
      parameters:
      - in: path
        name: caseId
        description: The id of the case to add the Guarantor to
      - in: path
        name: personId
        description: The id of the individual the application is for
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: tenancyRoleId
        description: The role id of the tenancy the case is linked to
      responses:
        200:
          description: OK
      tags:
      - S
      - Guarantor
      - To
      - Tenancy
      - Referencing
      - Applicationa
      - Case
      - Using
      - Details
      - Supplied
  /api/tenantreferncing/application/{applicationId}/referencingresult:
    get:
      summary: Get the details of an individual application referencing result
      description: Get the details of an individual application referencing result.
      operationId: TenantReferencing_GetApplicationStatusByapplicationId
      x-api-path-slug: apitenantreferncingapplicationapplicationidreferencingresult-get
      parameters:
      - in: path
        name: applicationId
        description: The id of the application to retrieve results for
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Details
      - Of
      - Individual
      - Application
      - Referencing
      - Result
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