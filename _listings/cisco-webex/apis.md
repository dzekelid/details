---
name: Cisco WebEx
x-slug: cisco-webex
description: Cisco Webex is the leading enterprise solution for video conferencing
  & web conferencing today. This secure software-based platform for video & audio
  conferencing, group messaging & webinars helps organizations be more productive.Participants
  can join ...
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/730-cisco-webex.jpg
x-kinRank: "7"
x-alexaRank: "632"
tags: Details
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/details/master/_listings/cisco-webex/apis.md
specificationVersion: "0.14"
apis:
- name: Webex Teams Admin API - Get License Details
  x-api-slug: licenses-license-get
  description: "Shows details for a license, by ID.\r\n\r\nSpecify the license ID
    in the licenseId parameter in the URI.\r\n\r\nhttps://developer.webex.com/endpoint-licenses-licenseId-get.html\r\n\r\nExample
    Response:\r\n``` json\r\n{\r\n  'id' : 'OTZhYmMyYWEtM2RjYy0xMWU1LWExNTItZmUzNDgxOWNkYzlh',\r\n
    \ 'displayName' : 'Spark Calling',\r\n  'totalUnits' : '42',\r\n  'consumedUnits'
    : \"8'\r\n}\r\n```"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/730-cisco-webex.jpg
  humanURL: https://webex.com
  baseURL: https://api.ciscospark.com//v1
  tags: Enterprise, Office, Collaboration, Video Conferencing, SaaS, Technology, Telecommunications,
    API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/details/master/_listings/cisco-webex/licenses-license-get-openapi.md
- name: Webex Teams Admin API - Get Role Details
  x-api-slug: roles-role-get
  description: |-
    Shows details for a role, by ID.

    Specify the role ID in the roleId parameter in the URI.

    https://developer.webex.com/endpoint-roles-roleId-get.html

    Example Response:
    ``` json
    {
      'id' : 'OTZhYmMyYWEtM2RjYy0xMWU1LWExNTItZmUzNDgxOWNkYzlh',
      'displayName' : 'Full Administrator'
    }
    ```
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/730-cisco-webex.jpg
  humanURL: https://webex.com
  baseURL: https://api.ciscospark.com//v1
  tags: Enterprise, Office, Collaboration, Video Conferencing, SaaS, Technology, Telecommunications,
    API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/details/master/_listings/cisco-webex/roles-role-get-openapi.md
- name: Webex Teams Admin API - Get Person Details (me)
  x-api-slug: peopleme-get
  description: |-
    Show the profile for the authenticated user.

    https://developer.webex.com/endpoint-people-me-get.html
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/730-cisco-webex.jpg
  humanURL: https://webex.com
  baseURL: https://api.ciscospark.com//v1
  tags: Enterprise, Office, Collaboration, Video Conferencing, SaaS, Technology, Telecommunications,
    API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/details/master/_listings/cisco-webex/peopleme-get-openapi.md
- name: Webex Teams Admin API - Get Events Details
  x-api-slug: events-event-get
  description: "Shows details for an event, by event ID.\r\nSpecify the event ID in
    the eventId parameter in the URI.\r\n\r\nhttps://developer.webex.com/endpoint-events-eventId-get.html"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/730-cisco-webex.jpg
  humanURL: https://webex.com
  baseURL: https://api.ciscospark.com//v1
  tags: Enterprise, Office, Collaboration, Video Conferencing, SaaS, Technology, Telecommunications,
    API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/details/master/_listings/cisco-webex/events-event-get-openapi.md
- name: Webex Teams Admin API - Get Organization Details
  x-api-slug: organizations-organization-get
  description: "Shows details for an organization, by ID.\r\n\r\nSpecify the org ID
    in the orgId parameter in the URI.\r\n\r\nhttps://developer.webex.com/endpoint-organizations-orgId-get.html\r\n\r\nExample
    Response:\r\n``` json\r\n{\r\n  'id' : 'OTZhYmMyYWEtM2RjYy0xMWU1LWExNTItZmUzNDgxOWNkYzlh',\r\n
    \ 'displayName' : 'Acme, Inc.',\r\n  'created' : '2015-10-18T14:26:16+00:00'\r\n}\r\n```"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/730-cisco-webex.jpg
  humanURL: https://webex.com
  baseURL: https://api.ciscospark.com//v1
  tags: Enterprise, Office, Collaboration, Video Conferencing, SaaS, Technology, Telecommunications,
    API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/details/master/_listings/cisco-webex/organizations-organization-get-openapi.md
- name: Webex Teams Admin API - Get Person Details1
  x-api-slug: people-person-get
  description: |-
    Shows details for a person, by ID.
    Specify the person ID in the personId parameter in the URI.

    https://developer.webex.com/endpoint-people-personId-get.html
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/730-cisco-webex.jpg
  humanURL: https://webex.com
  baseURL: https://api.ciscospark.com//v1
  tags: Enterprise, Office, Collaboration, Video Conferencing, SaaS, Technology, Telecommunications,
    API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/details/master/_listings/cisco-webex/people-person-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/details/master/_listings/cisco-webex/people-person-get-openapi.md
- name: Webex Teams Admin API - Get Person Details1
  x-api-slug: people-person-get
  description: |-
    Shows details for a person, by ID.
    Specify the person ID in the personId parameter in the URI.

    https://developer.webex.com/endpoint-people-personId-get.html
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/730-cisco-webex.jpg
  humanURL: https://webex.com
  baseURL: https://api.ciscospark.com//v1
  tags: Enterprise, Office, Collaboration, Video Conferencing, SaaS, Technology, Telecommunications,
    API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/details/master/_listings/cisco-webex/people-person-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/details/master/_listings/cisco-webex/people-person-get-openapi.md
- name: Webex Teams Admin API - Get Person Details1
  x-api-slug: people-person-get
  description: |-
    Shows details for a person, by ID.
    Specify the person ID in the personId parameter in the URI.

    https://developer.webex.com/endpoint-people-personId-get.html
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/730-cisco-webex.jpg
  humanURL: https://webex.com
  baseURL: https://api.ciscospark.com//v1
  tags: Enterprise, Office, Collaboration, Video Conferencing, SaaS, Technology, Telecommunications,
    API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/details/master/_listings/cisco-webex/people-person-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/details/master/_listings/cisco-webex/people-person-get-openapi.md
- name: Webex Teams Admin API - Get Person Details1
  x-api-slug: people-person-get
  description: |-
    Shows details for a person, by ID.
    Specify the person ID in the personId parameter in the URI.

    https://developer.webex.com/endpoint-people-personId-get.html
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/730-cisco-webex.jpg
  humanURL: https://webex.com
  baseURL: https://api.ciscospark.com//v1
  tags: Enterprise, Office, Collaboration, Video Conferencing, SaaS, Technology, Telecommunications,
    API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/details/master/_listings/cisco-webex/people-person-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/details/master/_listings/cisco-webex/people-person-get-openapi.md
- name: Webex Teams API - Get membership details
  x-api-slug: memberships-membership-get
  description: "Get details for a membership by ID.\r\n\r\nSpecify the membership
    ID in the membershipId URI parameter.\r\n\r\nhttps://developer.webex.com/endpoint-memberships-membershipId-get.html"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/730-cisco-webex.jpg
  humanURL: https://webex.com
  baseURL: https://api.ciscospark.com//v1
  tags: Enterprise, Office, Collaboration, Video Conferencing, SaaS, Technology, Telecommunications,
    API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/details/master/_listings/cisco-webex/memberships-membership-get-openapi.md
- name: Webex Teams API - Get message details
  x-api-slug: messages-message-get
  description: |-
    Shows details for a message, by message ID.

    Specify the message ID in the messageId parameter in the URI.

    https://developer.webex.com/endpoint-messages-messageId-get.html
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/730-cisco-webex.jpg
  humanURL: https://webex.com
  baseURL: https://api.ciscospark.com//v1
  tags: Enterprise, Office, Collaboration, Video Conferencing, SaaS, Technology, Telecommunications,
    API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/details/master/_listings/cisco-webex/messages-message-get-openapi.md
- name: Webex Teams API - Get person details (me)
  x-api-slug: peopleme-get
  description: |-
    Show the profile for the authenticated user.

    https://developer.webex.com/endpoint-people-me-get.html
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/730-cisco-webex.jpg
  humanURL: https://webex.com
  baseURL: https://api.ciscospark.com//v1
  tags: Enterprise, Office, Collaboration, Video Conferencing, SaaS, Technology, Telecommunications,
    API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/details/master/_listings/cisco-webex/peopleme-get-openapi.md
- name: Webex Teams API - Get Team room details
  x-api-slug: rooms-room-get
  description: "Shows details for a room, by ID.\r\n\r\nSpecify the room ID in the
    roomId parameter in the URI.\r\n\r\nhttps://developer.webex.com/endpoint-rooms-roomId-get.html"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/730-cisco-webex.jpg
  humanURL: https://webex.com
  baseURL: https://api.ciscospark.com//v1
  tags: Enterprise, Office, Collaboration, Video Conferencing, SaaS, Technology, Telecommunications,
    API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/details/master/_listings/cisco-webex/rooms-room-get-openapi.md
- name: Webex Teams API - Get team membership details
  x-api-slug: teammemberships-membership-get
  description: "Get details for a membership by ID.\r\n\r\nSpecify the membership
    ID in the membershipId URI parameter.\r\n\r\nhttps://developer.webex.com/endpoint-teammemberships-membershipId-get.html"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/730-cisco-webex.jpg
  humanURL: https://webex.com
  baseURL: https://api.ciscospark.com//v1
  tags: Enterprise, Office, Collaboration, Video Conferencing, SaaS, Technology, Telecommunications,
    API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/details/master/_listings/cisco-webex/teammemberships-membership-get-openapi.md
- name: Webex Teams API - Get team details
  x-api-slug: teams-team-get
  description: |-
    Show details for a team.

    https://developer.webex.com/endpoint-teams-teamId-get.html
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/730-cisco-webex.jpg
  humanURL: https://webex.com
  baseURL: https://api.ciscospark.com//v1
  tags: Enterprise, Office, Collaboration, Video Conferencing, SaaS, Technology, Telecommunications,
    API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/details/master/_listings/cisco-webex/teams-team-get-openapi.md
- name: Webex Teams API - Get person details
  x-api-slug: people-person-get
  description: "Shows details for a person, by ID.\r\n\r\nSpecify the person ID in
    the personId parameter in the URI.\r\n\r\nhttps://developer.webex.com/endpoint-people-personId-get.html"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/730-cisco-webex.jpg
  humanURL: https://webex.com
  baseURL: https://api.ciscospark.com//v1
  tags: Enterprise, Office, Collaboration, Video Conferencing, SaaS, Technology, Telecommunications,
    API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/details/master/_listings/cisco-webex/people-person-get-openapi.md
- name: Webex Teams API - Get webhook details1
  x-api-slug: webhooks-webhook-get
  description: "Shows details for a webhook, by ID.\r\n\r\nSpecify the webhook ID
    in the webhookId parameter in the URI.\r\n\r\nhttps://developer.webex.com/endpoint-webhooks-webhookId-get.html"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/730-cisco-webex.jpg
  humanURL: https://webex.com
  baseURL: https://api.ciscospark.com//v1
  tags: Enterprise, Office, Collaboration, Video Conferencing, SaaS, Technology, Telecommunications,
    API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/details/master/_listings/cisco-webex/webhooks-webhook-get-openapi.md
- name: Webex Teams API - Get webhook details1
  x-api-slug: webhooks-webhook-get
  description: "Shows details for a webhook, by ID.\r\n\r\nSpecify the webhook ID
    in the webhookId parameter in the URI.\r\n\r\nhttps://developer.webex.com/endpoint-webhooks-webhookId-get.html"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/730-cisco-webex.jpg
  humanURL: https://webex.com
  baseURL: https://api.ciscospark.com//v1
  tags: Enterprise, Office, Collaboration, Video Conferencing, SaaS, Technology, Telecommunications,
    API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/details/master/_listings/cisco-webex/webhooks-webhook-get-openapi.md
- name: Webex Teams API - Get webhook details1
  x-api-slug: webhooks-webhook-get
  description: "Shows details for a webhook, by ID.\r\n\r\nSpecify the webhook ID
    in the webhookId parameter in the URI.\r\n\r\nhttps://developer.webex.com/endpoint-webhooks-webhookId-get.html"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/730-cisco-webex.jpg
  humanURL: https://webex.com
  baseURL: https://api.ciscospark.com//v1
  tags: Enterprise, Office, Collaboration, Video Conferencing, SaaS, Technology, Telecommunications,
    API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/details/master/_listings/cisco-webex/webhooks-webhook-get-openapi.md
- name: Webex Teams API - Get webhook details1
  x-api-slug: webhooks-webhook-get
  description: "Shows details for a webhook, by ID.\r\n\r\nSpecify the webhook ID
    in the webhookId parameter in the URI.\r\n\r\nhttps://developer.webex.com/endpoint-webhooks-webhookId-get.html"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/730-cisco-webex.jpg
  humanURL: https://webex.com
  baseURL: https://api.ciscospark.com//v1
  tags: Enterprise, Office, Collaboration, Video Conferencing, SaaS, Technology, Telecommunications,
    API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/details/master/_listings/cisco-webex/webhooks-webhook-get-openapi.md
x-common:
- type: x-postman-collection
  url: https://app.getpostman.com/run-collection/1f5e101d8290a5303c90
- type: x-api-gallery
  url: http://cisco.unity.connection.messaging.interface.api.gallery.streamdata.io
- type: x-api-stack
  url: http://cisco.webex.stack.network
- type: x-blog
  url: http://blogs.webex.com/
- type: x-blog-rss
  url: http://blogs.webex.com/webex_interactions/index.rdf
- type: x-crunchbase
  url: https://crunchbase.com/organization/webex-communications
- type: x-crunchbase
  url: http://www.crunchbase.com/company/webex
- type: x-postman-collection
  url: https://app.getpostman.com/run-collection/0aa22af74405f82086d4
- type: x-twitter
  url: https://twitter.com/webex
- type: x-developer
  url: https://developer.webex.com/
- type: x-website
  url: https://webex.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---