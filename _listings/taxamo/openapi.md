swagger: "2.0"
x-collection-name: Taxamo
x-complete: 1
info:
  title: Taxamo
  description: taxamos-elegant-suite-of-apis-and-comprehensive-reporting-dashboard-enables-digital-merchants-to-easily-comply-with-eu-regulatory-requirements-on-tax-calculation-evidence-collection-tax-return-creation-and-data-storage-
  version: "1"
host: api.taxamo.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/settlement/detailed_refunds:
    get:
      summary: Detailed Refunds
      description: Detailed refunds.
      operationId: getDetailedRefunds
      x-api-path-slug: apiv1settlementdetailed-refunds-get
      parameters:
      - in: query
        name: country_codes
        description: Comma separated list of 2-letter country codes
      - in: query
        name: date_from
        description: Take only refunds issued at or after the date
      - in: query
        name: date_to
        description: Take only refunds issued at or before the date
      - in: query
        name: format
        description: Output format
      - in: query
        name: limit
        description: Limit (no more than 1000, defaults to 100)
      - in: query
        name: offset
        description: Offset
      responses:
        200:
          description: OK
      tags:
      - Detailed
      - Refunds