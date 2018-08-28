---
swagger: "2.0"
x-collection-name: Postmark
x-complete: 0
info:
  title: Postmark Get Messages Outbound Message Details
  description: Get messages outbound message details.
  version: 1.0.0
host: spamcheck.postmarkapp.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /messages/inbound/{messageid}/details:
    get:
      summary: Get Messages Inbound Message Details
      description: Get messages inbound message details.
      operationId: getMessagesInboundMessageDetails
      x-api-path-slug: messagesinboundmessageiddetails-get
      parameters:
      - in: path
        name: messageid
        description: The ID of the message for which to details will be retrieved
      - in: header
        name: X-Postmark-Server-Token
        description: The token associated with the Server on which this request will
          operate
      responses:
        200:
          description: OK
      tags:
      - Messages
      - Inbound
      - Messageid
      - Details
  /messages/outbound/{messageid}/details:
    get:
      summary: Get Messages Outbound Message Details
      description: Get messages outbound message details.
      operationId: getMessagesOutboundMessageDetails
      x-api-path-slug: messagesoutboundmessageiddetails-get
      parameters:
      - in: path
        name: messageid
        description: The ID of the message for which to retrieve details
      - in: header
        name: X-Postmark-Server-Token
        description: The token associated with the Server on which this request will
          operate
      responses:
        200:
          description: OK
      tags:
      - Messages
      - Outbound
      - Messageid
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