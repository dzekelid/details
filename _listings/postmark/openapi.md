swagger: "2.0"
x-collection-name: Postmark
x-complete: 1
info:
  title: Postmark Account-level
  description: postmark-makes-sending-and-receiving-email-incredibly-easy--the-accountlevel-api-allows-users-toconfigure-all-servers-domains-and-sender-signatures-associated-with-an-account-
  version: 0.9.0
host: api.postmarkapp.com
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