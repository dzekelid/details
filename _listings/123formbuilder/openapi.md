---
swagger: "2.0"
x-collection-name: 123FormBuilder
x-complete: 1
info:
  title: ""
  version: 1.0.0
host: api.123contactform.com
basePath: /v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /forms/{form_id}:
    get:
      summary: Get form details
      description: Get the details of a single form
      operationId: get-the-details-of-a-single-form
      x-api-path-slug: formsform-id-get
      parameters:
      - in: path
        name: form_id
        description: The ID of the form
      - in: query
        name: JWT
        description: JWT authentication token
      responses:
        200:
          description: OK
      tags:
      - Form
      - Details
    put:
      summary: Update form details
      description: Update form details
      operationId: update-form-details
      x-api-path-slug: formsform-id-put
      parameters:
      - in: formData
        name: active
        description: Form activity status
      - in: formData
        name: active_date_from
        description: If activity status is 1, this field is required
      - in: formData
        name: active_date_to
        description: If activity status is 1, this field is required
      - in: formData
        name: active_days
        description: If activity status is 4, this field is required
      - in: path
        name: form_id
        description: The ID of the form
      - in: formData
        name: group_id
        description: The ID of the group in which you want to create the form
      - in: query
        name: JWT
        description: JWT authentication token
      - in: formData
        name: name
        description: Change the name of the form
      responses:
        200:
          description: OK
      tags:
      - Form
      - Details
  /forms/{form_id}/submissions/{submission_id}:
    get:
      summary: Get submission details
      description: Get the details of a single submission
      operationId: get-the-details-of-a-single-submission
      x-api-path-slug: formsform-idsubmissionssubmission-id-get
      parameters:
      - in: path
        name: form_id
        description: The ID of the form
      - in: query
        name: include_recipients
        description: Returns the recipient(s) who should receive the submission
      - in: query
        name: JWT
        description: JWT authentication token
      - in: path
        name: submission_id
        description: The ID of the submission
      responses:
        200:
          description: OK
      tags:
      - Submission
      - Details
  /groups/{group_id}:
    get:
      summary: Get group details
      description: Get information about a specific group.
      operationId: get-information-about-a-specific-group
      x-api-path-slug: groupsgroup-id-get
      parameters:
      - in: path
        name: group_id
        description: The ID of the group
      - in: query
        name: JWT
        description: JWT authentication token
      responses:
        200:
          description: OK
      tags:
      - Group
      - Details
---