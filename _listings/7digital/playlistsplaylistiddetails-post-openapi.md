---
swagger: "2.0"
x-collection-name: 7digital
x-complete: 0
info:
  title: 7digital Purchasing API playlists/{playlistId}/details
  description: Updates playlist details at {playlistId} with the supplied playlist
    details. It does not affect playlist tracks. Use this method e.g. for changing
    visibility of the playlist from private to public. The playlist details can only
    be updated by the playlist owner, i.e. oauth_token representing the user has to
    be provided.
  version: "1.2"
host: api.7digital.com
basePath: 1.2/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  playlists/{playlistId}/details:
    'post ':
      summary: playlists/{playlistId}/details
      description: Updates playlist details at {playlistId} with the supplied playlist
        details. It does not affect playlist tracks. Use this method e.g. for changing
        visibility of the playlist from private to public. The playlist details can
        only be updated by the playlist owner, i.e. oauth_token representing the user
        has to be provided.
      operationId: playlistsplaylistiddetails
      x-api-path-slug: playlistsplaylistiddetails-post
      parameters:
      - ~
      - in: query
        name: oauth_token
        description: Users OAuth access token
      responses:
        200:
          description: OK
      tags:
      - Playlists
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