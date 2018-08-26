---
swagger: "2.0"
x-collection-name: Atlassian
x-complete: 0
info:
  title: Jira Cloud API Get project role details
  description: Returns all [project roles](https://confluence.atlassian.com/x/3odKLg)
    and the details for each role. Note that the list of project roles is common to
    all projects.
  termsOfService: http://atlassian.com/terms/
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/2/project/{projectIdOrKey}/roledetails:
    get:
      summary: Get project role details
      description: Returns all [project roles](https://confluence.atlassian.com/x/3odKLg)
        and the details for each role. Note that the list of project roles is common
        to all projects.
      operationId: com.atlassian.jira.rest.v2.issue.project.ProjectRoleDetailsResource.getProjectRoleDetails_get
      x-api-path-slug: api2projectprojectidorkeyroledetails-get
      parameters:
      - in: path
        name: projectIdOrKey
        description: The project ID or project key (case sensitive)
      responses:
        200:
          description: OK
      tags:
      - Project
      - Role
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