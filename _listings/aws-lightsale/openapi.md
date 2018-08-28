swagger: "2.0"
x-collection-name: AWS Lightsale
x-complete: 1
info:
  title: AWS Lightsale API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=GetInstanceAccessDetails:
    get:
      summary: Get Instance Access Details
      description: |-
        Returns temporary SSH keys you can use to connect to a specific virtual private server,
              or instance.
      operationId: getInstanceAccessDetails
      x-api-path-slug: actiongetinstanceaccessdetails-get
      parameters:
      - in: query
        name: instanceName
        description: The name of the instance to access
        type: string
      - in: query
        name: protocol
        description: The protocol to use to connect to your instance
        type: string
      responses:
        200:
          description: OK
      tags:
      - Instances