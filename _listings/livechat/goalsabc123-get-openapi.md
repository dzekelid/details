---
swagger: "2.0"
x-collection-name: LiveChat
x-complete: 0
info:
  title: LiveChat Get a single goal details
  description: Returns the goal details for the given GOAL_ID.
  version: 1.0.0
host: api.livechatinc.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /visitors/S1352647457.ac951bfe2e/details:
    post:
      summary: Add custom visitor details
      description: Displays additional information about a visitor in LiveChat apps.
      operationId: VisitorsS1352647457Ac951bfe2eDetailsPost
      x-api-path-slug: visitorss1352647457-ac951bfe2edetails-post
      parameters:
      - in: formData
        name: fields[0][name]
      - in: formData
        name: fields[0][value]
      - in: formData
        name: id
      - in: formData
        name: license_id
      - in: formData
        name: token
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - Custom
      - Visitor
      - Details
  /goals/ABC123:
    get:
      summary: Get a single goal details
      description: Returns the goal details for the given GOAL_ID.
      operationId: GoalsABC123Get
      x-api-path-slug: goalsabc123-get
      parameters:
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - Single
      - Goal
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