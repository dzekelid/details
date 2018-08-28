swagger: "2.0"
x-collection-name: AWS Config
x-complete: 1
info:
  title: AWS Config API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=GetComplianceDetailsByConfigRule:
    get:
      summary: Get Compliance Details By Config Rule
      description: Returns the evaluation results for the specified AWS Config rule.
      operationId: getComplianceDetailsByConfigRule
      x-api-path-slug: actiongetcompliancedetailsbyconfigrule-get
      parameters:
      - in: query
        name: ComplianceTypes
        description: Filters the results by compliance
        type: string
      - in: query
        name: ConfigRuleName
        description: The name of the AWS Config rule for which you want compliance
          information
        type: string
      - in: query
        name: Limit
        description: The maximum number of evaluation results returned on each page
        type: string
      - in: query
        name: NextToken
        description: The nextToken string returned on a previous page thatyou use
          to get the next page of results in a paginated response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Compliance
  /?Action=GetComplianceDetailsByResource:
    get:
      summary: Get Compliance Details By Resource
      description: Returns the evaluation results for the specified AWS resource.
      operationId: getComplianceDetailsByResource
      x-api-path-slug: actiongetcompliancedetailsbyresource-get
      parameters:
      - in: query
        name: ComplianceTypes
        description: Filters the results by compliance
        type: string
      - in: query
        name: NextToken
        description: The nextToken string returned on a previous page thatyou use
          to get the next page of results in a paginated response
        type: string
      - in: query
        name: ResourceId
        description: The ID of the AWS resource for which you want compliance information
        type: string
      - in: query
        name: ResourceType
        description: The type of the AWS resource for which you want compliance information
        type: string
      responses:
        200:
          description: OK
      tags:
      - Compliance