---
swagger: "2.0"
x-collection-name: Mailjet
x-complete: 0
info:
  title: Mailjet Messages API Message Detail
  description: View the details of a message.
  version: v3
host: api.mailjet.com
basePath: v3/REST/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  message{id}:
    get:
      summary: Message Detail
      description: View the details of a message.
      operationId: getMessage
      x-api-path-slug: messageid-get
      parameters:
      - in: path
        name: id
        description: Message ID
      responses:
        200:
          description: OK
      tags:
      - Message
      - Detail
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