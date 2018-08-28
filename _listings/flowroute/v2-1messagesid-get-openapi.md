---
swagger: "2.0"
x-collection-name: Flowroute
x-complete: 0
info:
  title: FlowRoute API Look Up a Message Detail Record
  description: Searches for a specific message record ID and returns a Message Detail
    Record (in MDR2 format).
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v2/numbers/{id}:
    get:
      summary: Phone Number Details
      description: Lists all of the information associated with any of the phone numbers
        in your account, including billing method, primary voice route, and failover
        voice route.
      operationId: lists-all-of-the-information-associated-with-any-of-the-phone-numbers-in-your-account-including-bill
      x-api-path-slug: v2numbersid-get
      parameters:
      - in: path
        name: id
        description: Phone number to search for which must be a number that you own
      responses:
        200:
          description: OK
      tags:
      - Messaging
      - Phone
      - Number
      - Details
  /v2.1/messages/{id}:
    get:
      summary: Look Up a Message Detail Record
      description: Searches for a specific message record ID and returns a Message
        Detail Record (in MDR2 format).
      operationId: searches-for-a-specific-message-record-id-and-returns-a-message-detail-record-in-mdr2-format
      x-api-path-slug: v2-1messagesid-get
      parameters:
      - in: path
        name: id
        description: The unique message detail record identifier (MDR ID) of any message
      responses:
        200:
          description: OK
      tags:
      - Messaging
      - Look
      - Up
      - Message
      - Detail
      - Record
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