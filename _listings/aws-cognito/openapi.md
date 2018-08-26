---
swagger: "2.0"
x-collection-name: AWS Cognito
x-complete: 1
info:
  title: AWS Cognito Merged API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=GetBulkPublishDetails:
    get:
      summary: Get Bulk Publish Details
      description: Get the status of the last BulkPublish operation for an identity
        pool.
      operationId: getBulkPublishDetails
      x-api-path-slug: actiongetbulkpublishdetails-get
      parameters:
      - in: query
        name: IdentityPoolId
        description: A name-spaced GUID (for example, us-east-1:23EC4050-6AEA-7089-A2DD-08002EXAMPLE)
          created by Amazon Cognito
        type: string
      responses:
        200:
          description: OK
      tags:
      - Publish
---