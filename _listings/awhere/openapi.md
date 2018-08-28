swagger: "2.0"
x-collection-name: aWhere
x-complete: 1
info:
  title: aWhere API Platform
  description: todo-add-description
  version: 1.0.0
host: api.awhere.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v2/agronomics/models/BarleyGenericMSU/details:
    get:
      summary: Get Model Details
      description: "####Request\nThis API call returns the details about a particular
        model. Currently, growth stage models are available via the API, so the details
        are a list of the possible stages with GDD threshold information. \n\n[Model
        Details Documentation](http://developer.awhere.com/api/reference/models/details).\n\n\n####Security\nThis
        API call uses the security Access Token that is retrieved with the \"Get a
        Token\" request. If you run that request first, it will save a token to Postman
        and this API will use it automatically. You can also see where the token should
        normally go by clicking the \"Headers\" tab below. The Authorization header
        holds the token, replacing the \"{{aWhereAccessToken}}\" part."
      operationId: V2AgronomicsModelsBarleyGenericMSUDetailsGet
      x-api-path-slug: v2agronomicsmodelsbarleygenericmsudetails-get
      responses:
        200:
          description: OK
      tags:
      - Agriculture
      - Model
      - Details