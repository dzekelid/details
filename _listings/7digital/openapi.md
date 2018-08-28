swagger: "2.0"
x-collection-name: 7digital
x-complete: 1
info:
  title: 7digital Purchasing API
  description: the-purchasing-api-allows-3rd-parties-to-deliver-digital-content-to-individual-users-
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