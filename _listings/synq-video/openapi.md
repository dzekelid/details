swagger: "2.0"
x-collection-name: SYNQ Video
x-complete: 1
info:
  title: SYNQ Video
  description: -sign-up-for-a-developer-api-keyhttpswww-synq-fmregister-synq-api-guide
  version: 1.9.1
host: api.synq.fm
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /video/details:
    post:
      summary: Return details about a video.
      description: Return details about a video. You may optionally request that only
        some of the metadata fields are returned.
      operationId: details
      x-api-path-slug: videodetails-post
      parameters:
      - in: formData
        name: api_key
      - in: formData
        name: video_id
        description: ID of the video to retrieve the metadata from
      responses:
        200:
          description: OK
      tags:
      - Video
      - Details