swagger: "2.0"
x-collection-name: Mattermost
x-complete: 1
info:
  title: Mattermost
  version: 1.0.0
host: your-mattermost-url.com
basePath: /api/v4
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /data_retention/policy:
    get:
      summary: Get the data retention policy details.
      description: |-
        Gets the current data retention policy details from the server, including what data should be purged and the cutoff times for each data type that should be purged.
        __Minimum server version__: 4.3
        ##### Permissions
        Requires an active session but no other permissions.
      operationId: gets-the-current-data-retention-policy-details-from-the-server-including-what-data-should-be-purged-
      x-api-path-slug: data-retentionpolicy-get
      responses:
        200:
          description: OK
      tags:
      - Data
      - Retention
      - Policy
      - Details.