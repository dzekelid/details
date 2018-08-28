---
swagger: "2.0"
x-collection-name: Square
x-complete: 0
info:
  title: Square Connect API Provides the details for a single employee role.
  description: Provides the details for a single employee role.
  termsOfService: https://connect.squareup.com/tos
  contact:
    name: Square Developer Platform
    url: https://squareup.com/developers
    email: developers@squareup.com
  version: "2.0"
host: connect.squareup.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/me/roles/{role_id}:
    put:
      summary: Modifies the details of an employee role.
      description: Modifies the details of an employee role.
      operationId: UpdateEmployeeRole
      x-api-path-slug: v1merolesrole-id-put
      parameters:
      - in: body
        name: body
        description: An object containing the fields to POST for the request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: role_id
        description: The ID of the role to modify
      responses:
        200:
          description: OK
      tags:
      - Modifies
      - Details
      - Of
      - Employee
      - Role
    get:
      summary: Provides the details for a single employee role.
      description: Provides the details for a single employee role.
      operationId: RetrieveEmployeeRole
      x-api-path-slug: v1merolesrole-id-get
      parameters:
      - in: path
        name: role_id
        description: The roles ID
      responses:
        200:
          description: OK
      tags:
      - Provides
      - Detailsa
      - Single
      - Employee
      - Role
  /v1/me/timecards/{timecard_id}:
    put:
      summary: Modifies a timecard's details. This creates an API_EDIT event for the
        timecard. You can view a timecard's event history with the List Timecard Events
        endpoint.
      description: Modifies a timecard's details. This creates an API_EDIT event for
        the timecard. You can view a timecard's event history with the List Timecard
        Events endpoint.
      operationId: UpdateTimecard
      x-api-path-slug: v1metimecardstimecard-id-put
      parameters:
      - in: body
        name: body
        description: An object containing the fields to POST for the request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: timecard_id
        description: TThe ID of the timecard to modify
      responses:
        200:
          description: OK
      tags:
      - Modifies
      - Timecards
      - Details
      - ""
      - This
      - Creates
      - EDIT
      - Eventthe
      - Timecard
      - ""
      - You
      - Can
      - View
      - Timecards
      - Event
      - History
      - List
      - Timecard
      - Events
      - Endpoint
    get:
      summary: Provides the details for a single timecard.
      description: Provides the details for a single timecard.
      operationId: RetrieveTimecard
      x-api-path-slug: v1metimecardstimecard-id-get
      parameters:
      - in: path
        name: timecard_id
        description: The timecards ID
      responses:
        200:
          description: OK
      tags:
      - Provides
      - Detailsa
      - Single
      - Timecard
  /v1/{location_id}/bank-accounts:
    get:
      summary: Provides non-confidential details for all of a location's associated
        bank accounts. This endpoint does not provide full bank account numbers, and
        there is no way to obtain a full bank account number with the Connect API.
      description: Provides non-confidential details for all of a location's associated
        bank accounts. This endpoint does not provide full bank account numbers, and
        there is no way to obtain a full bank account number with the Connect API.
      operationId: ListBankAccounts
      x-api-path-slug: v1location-idbankaccounts-get
      parameters:
      - in: path
        name: location_id
        description: The ID of the location to list bank accounts for
      responses:
        200:
          description: OK
      tags:
      - Provides
      - Non-confidential
      - Details
      - Of
      - Locations
      - Associated
      - Bank
      - Accounts
      - ""
      - This
      - Endpoint
      - Does
      - Not
      - Provide
      - Full
      - Bank
      - Account
      - Numbers
      - ""
      - There
      - Is
      - "No"
      - Way
      - To
      - Obtain
      - Full
      - Bank
      - Account
      - Number
      - Connect
  /v1/{location_id}/cash-drawer-shifts:
    get:
      summary: Provides the details for all of a location's cash drawer shifts during
        a date range. The date range you specify cannot exceed 90 days.
      description: Provides the details for all of a location's cash drawer shifts
        during a date range. The date range you specify cannot exceed 90 days.
      operationId: ListCashDrawerShifts
      x-api-path-slug: v1location-idcashdrawershifts-get
      parameters:
      - in: query
        name: begin_time
        description: The beginning of the requested reporting period, in ISO 8601
          format
      - in: query
        name: end_time
        description: The beginning of the requested reporting period, in ISO 8601
          format
      - in: path
        name: location_id
        description: The ID of the location to list cash drawer shifts for
      - in: query
        name: order
        description: The order in which cash drawer shifts are listed in the response,
          based on their created_at field
      responses:
        200:
          description: OK
      tags:
      - Provides
      - Details
      - Of
      - Locations
      - Cash
      - Drawer
      - Shifts
      - During
      - Date
      - Range
      - ""
      - Date
      - Range
      - You
      - Specify
      - Cannot
      - Exceed
      - "90"
      - Days
  /v1/{location_id}/categories/{category_id}:
    put:
      summary: Modifies the details of an existing item category.
      description: Modifies the details of an existing item category.
      operationId: UpdateCategory
      x-api-path-slug: v1location-idcategoriescategory-id-put
      parameters:
      - in: body
        name: body
        description: An object containing the fields to POST for the request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: category_id
        description: The ID of the category to edit
      - in: path
        name: location_id
        description: The ID of the categorys associated location
      responses:
        200:
          description: OK
      tags:
      - Modifies
      - Details
      - Of
      - Existing
      - Item
      - Category
  /v1/{location_id}/discounts/{discount_id}:
    put:
      summary: Modifies the details of an existing discount.
      description: Modifies the details of an existing discount.
      operationId: UpdateDiscount
      x-api-path-slug: v1location-iddiscountsdiscount-id-put
      parameters:
      - in: body
        name: body
        description: An object containing the fields to POST for the request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: discount_id
        description: The ID of the discount to edit
      - in: path
        name: location_id
        description: The ID of the categorys associated location
      responses:
        200:
          description: OK
      tags:
      - Modifies
      - Details
      - Of
      - Existing
      - Discount
  /v1/{location_id}/fees/{fee_id}:
    put:
      summary: Modifies the details of an existing fee (tax).
      description: Modifies the details of an existing fee (tax).
      operationId: UpdateFee
      x-api-path-slug: v1location-idfeesfee-id-put
      parameters:
      - in: body
        name: body
        description: An object containing the fields to POST for the request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: fee_id
        description: The ID of the fee to edit
      - in: path
        name: location_id
        description: The ID of the fees associated location
      responses:
        200:
          description: OK
      tags:
      - Modifies
      - Details
      - Of
      - Existing
      - Fee
      - (tax)
  /v1/{location_id}/items/{item_id}:
    put:
      summary: Modifies the core details of an existing item.
      description: Modifies the core details of an existing item.
      operationId: UpdateItem
      x-api-path-slug: v1location-iditemsitem-id-put
      parameters:
      - in: body
        name: body
        description: An object containing the fields to POST for the request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: item_id
        description: The ID of the item to modify
      - in: path
        name: location_id
        description: The ID of the items associated location
      responses:
        200:
          description: OK
      tags:
      - Modifies
      - Core
      - Details
      - Of
      - Existing
      - Item
    get:
      summary: Provides the details for a single item, including associated modifier
        lists and fees.
      description: Provides the details for a single item, including associated modifier
        lists and fees.
      operationId: RetrieveItem
      x-api-path-slug: v1location-iditemsitem-id-get
      parameters:
      - in: path
        name: item_id
        description: The items ID
      - in: path
        name: location_id
        description: The ID of the items associated location
      responses:
        200:
          description: OK
      tags:
      - Provides
      - Detailsa
      - Single
      - Item
      - ""
      - Including
      - Associated
      - Modifier
      - Lists
      - Fees
  /v1/{location_id}/items/{item_id}/variations/{variation_id}:
    put:
      summary: Modifies the details of an existing item variation.
      description: Modifies the details of an existing item variation.
      operationId: UpdateVariation
      x-api-path-slug: v1location-iditemsitem-idvariationsvariation-id-put
      parameters:
      - in: body
        name: body
        description: An object containing the fields to POST for the request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: item_id
        description: The ID of the item to modify
      - in: path
        name: location_id
        description: The ID of the items associated location
      - in: path
        name: variation_id
        description: The ID of the variation to modify
      responses:
        200:
          description: OK
      tags:
      - Modifies
      - Details
      - Of
      - Existing
      - Item
      - Variation
  /v1/{location_id}/modifier-lists/{modifier_list_id}:
    put:
      summary: Modifies the details of an existing item modifier list.
      description: Modifies the details of an existing item modifier list.
      operationId: UpdateModifierList
      x-api-path-slug: v1location-idmodifierlistsmodifier-list-id-put
      parameters:
      - in: body
        name: body
        description: An object containing the fields to POST for the request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: location_id
        description: The ID of the items associated location
      - in: path
        name: modifier_list_id
        description: The ID of the modifier list to edit
      responses:
        200:
          description: OK
      tags:
      - Modifies
      - Details
      - Of
      - Existing
      - Item
      - Modifier
      - List
    get:
      summary: Provides the details for a single modifier list.
      description: Provides the details for a single modifier list.
      operationId: RetrieveModifierList
      x-api-path-slug: v1location-idmodifierlistsmodifier-list-id-get
      parameters:
      - in: path
        name: location_id
        description: The ID of the items associated location
      - in: path
        name: modifier_list_id
        description: The modifier lists ID
      responses:
        200:
          description: OK
      tags:
      - Provides
      - Detailsa
      - Single
      - Modifier
      - List
  /v1/{location_id}/modifier-lists/{modifier_list_id}/modifier-options/{modifier_option_id}:
    put:
      summary: Modifies the details of an existing item modifier option.
      description: Modifies the details of an existing item modifier option.
      operationId: UpdateModifierOption
      x-api-path-slug: v1location-idmodifierlistsmodifier-list-idmodifieroptionsmodifier-option-id-put
      parameters:
      - in: body
        name: body
        description: An object containing the fields to POST for the request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: location_id
        description: The ID of the items associated location
      - in: path
        name: modifier_list_id
        description: The ID of the modifier list to edit
      - in: path
        name: modifier_option_id
        description: The ID of the modifier list to edit
      responses:
        200:
          description: OK
      tags:
      - Modifies
      - Details
      - Of
      - Existing
      - Item
      - Modifier
      - Option
  /v1/{location_id}/orders/{order_id}:
    put:
      summary: 'Updates the details of an online store order. Every update you perform
        on an order corresponds to one of three actions:'
      description: 'Updates the details of an online store order. Every update you
        perform on an order corresponds to one of three actions:'
      operationId: UpdateOrder
      x-api-path-slug: v1location-idordersorder-id-put
      parameters:
      - in: body
        name: body
        description: An object containing the fields to POST for the request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: location_id
        description: The ID of the orders associated location
      - in: path
        name: order_id
        description: The orders Square-issued ID
      responses:
        200:
          description: OK
      tags:
      - S
      - Details
      - Of
      - Online
      - Store
      - Order
      - ""
      - Every
      - Update
      - You
      - Perform
      - "On"
      - Order
      - Corresponds
      - To
      - Of
      - Three
      - 'Actions:'
  /v1/{location_id}/pages/{page_id}:
    put:
      summary: Modifies the details of a Favorites page in Square Register.
      description: Modifies the details of a Favorites page in Square Register.
      operationId: UpdatePage
      x-api-path-slug: v1location-idpagespage-id-put
      parameters:
      - in: body
        name: body
        description: An object containing the fields to POST for the request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: location_id
        description: The ID of the Favorites pages associated location
      - in: path
        name: page_id
        description: The ID of the page to modify
      responses:
        200:
          description: OK
      tags:
      - Modifies
      - Details
      - Of
      - Favorites
      - Page
      - In
      - Square
      - Register
  /v1/{location_id}/refunds:
    get:
      summary: Provides the details for all refunds initiated by a merchant or any
        of the merchant's mobile staff during a date range. Date ranges cannot exceed
        one year in length.
      description: Provides the details for all refunds initiated by a merchant or
        any of the merchant's mobile staff during a date range. Date ranges cannot
        exceed one year in length.
      operationId: v1.location_id.refunds.get
      x-api-path-slug: v1location-idrefunds-get
      parameters:
      - in: query
        name: batch_token
        description: A pagination cursor to retrieve the next set of results for youroriginal
          query to the endpoint
      - in: query
        name: begin_time
        description: The beginning of the requested reporting period, in ISO 8601
          format
      - in: query
        name: end_time
        description: The end of the requested reporting period, in ISO 8601 format
      - in: query
        name: limit
        description: The maximum number of payments to return in a single response
      - in: path
        name: location_id
        description: The ID of the location to list refunds for
      - in: query
        name: order
        description: TThe order in which payments are listed in the response
      responses:
        200:
          description: OK
      tags:
      - Provides
      - Details
      - Refunds
      - Initiated
      - By
      - Merchant
      - Any
      - Of
      - Merchants
      - Mobile
      - Staff
      - During
      - Date
      - Range
      - ""
      - Date
      - Ranges
      - Cannot
      - Exceed
      - Year
      - In
      - Length
  /v1/me/employees/{employee_id}:
    get:
      summary: Provides the details for a single employee.
      description: Provides the details for a single employee.
      operationId: RetrieveEmployee
      x-api-path-slug: v1meemployeesemployee-id-get
      parameters:
      - in: path
        name: employee_id
        description: The employees ID
      responses:
        200:
          description: OK
      tags:
      - Provides
      - Detailsa
      - Single
      - Employee
  /v1/me/locations:
    get:
      summary: Provides details for a business's locations, including their IDs.
      description: Provides details for a business's locations, including their IDs.
      operationId: v1.me.locations.get
      x-api-path-slug: v1melocations-get
      responses:
        200:
          description: OK
      tags:
      - Provides
      - Detailsa
      - Businesss
      - Locations
      - ""
      - Including
      - Their
      - IDs
  /v1/{location_id}/bank-accounts/{bank_account_id}:
    get:
      summary: Provides non-confidential details for a merchant's associated bank
        account. This endpoint does not provide full bank account numbers, and there
        is no way to obtain a full bank account number with the Connect API.
      description: Provides non-confidential details for a merchant's associated bank
        account. This endpoint does not provide full bank account numbers, and there
        is no way to obtain a full bank account number with the Connect API.
      operationId: RetrieveBankAccount
      x-api-path-slug: v1location-idbankaccountsbank-account-id-get
      parameters:
      - in: path
        name: bank_account_id
        description: The bank accounts Square-issued ID
      - in: path
        name: location_id
        description: The ID of the bank accounts associated location
      responses:
        200:
          description: OK
      tags:
      - Provides
      - Non-confidential
      - Detailsa
      - Merchants
      - Associated
      - Bank
      - Account
      - ""
      - This
      - Endpoint
      - Does
      - Not
      - Provide
      - Full
      - Bank
      - Account
      - Numbers
      - ""
      - There
      - Is
      - "No"
      - Way
      - To
      - Obtain
      - Full
      - Bank
      - Account
      - Number
      - Connect
  /v1/{location_id}/cash-drawer-shifts/{shift_id}:
    get:
      summary: Provides the details for a single cash drawer shift, including all
        events that occurred during the shift.
      description: Provides the details for a single cash drawer shift, including
        all events that occurred during the shift.
      operationId: RetrieveCashDrawerShift
      x-api-path-slug: v1location-idcashdrawershiftsshift-id-get
      parameters:
      - in: path
        name: location_id
        description: The ID of the location to list cash drawer shifts for
      - in: path
        name: shift_id
        description: The shifts ID
      responses:
        200:
          description: OK
      tags:
      - Provides
      - Detailsa
      - Single
      - Cash
      - Drawer
      - Shift
      - ""
      - Including
      - ""
      - Events
      - That
      - Occurred
      - During
      - Shift
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