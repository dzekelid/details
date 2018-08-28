swagger: "2.0"
x-collection-name: Cisco WebEx
x-complete: 1
info:
  title: Webex Teams API
  description: hey-there-thanks-for-checking-out-cisco-webex-for-developers--if-youve-used-cisco-webex-meetings-or-cisco-webex-teams-formerly-cisco-spark-you-know-how-easy-it-is-to-meet-and-collaborate-with-your-team-members-and-customers-the-webex-for-developers-program-opens-up-the-power-behind-the-webex-platform-to-anyone-seeking-to-extend-the-webex-experience-webex-meetings-is-a-powerful-conferencing-solution-that-lets-you-connect-with-anyone-anywhere-in-real-time--by-combining-video-audio-and-content-sharing-webex-meetings-creates-an-effective-conferencing-environment-leading-to-more-productive-meetings-and-increased-productivity--developer-information-for-webex-meetings-will-soon-be-available-on-this-site--in-the-meantime-to-get-started-with-developing-for-webex-meetings-please-see-the-getting-started-guides-over-on-cisco-devnet--keep-reading-for-information-about-webex-teams-webex-teams-makes-staying-in-sync-with-your-teammates-and-customers-easy-conversations-in-webex-teams-take-place-in-virtual-meeting-rooms--some-rooms-live-for-a-few-hours-while-others-become-permanent-fixtures-of-your-teams-workflow-with-titles-like-daily-standup-or-build-status--webex-teams-allows-conversations-to-flow-seamlessly-between-messages-video-calls-and-realtime-whiteboarding-sessions--no-other-solution-brings-together-so-many-facets-of-collaboration-into-a-single-unified-platform-httpsdeveloper-webex-comgettingstarted-html
  version: 1.0.0
host: api.ciscospark.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /licenses/{_license}:
    get:
      summary: Get License Details
      description: "Shows details for a license, by ID.\r\n\r\nSpecify the license
        ID in the licenseId parameter in the URI.\r\n\r\nhttps://developer.webex.com/endpoint-licenses-licenseId-get.html\r\n\r\nExample
        Response:\r\n``` json\r\n{\r\n  'id' : 'OTZhYmMyYWEtM2RjYy0xMWU1LWExNTItZmUzNDgxOWNkYzlh',\r\n
        \ 'displayName' : 'Spark Calling',\r\n  'totalUnits' : '42',\r\n  'consumedUnits'
        : \"8'\r\n}\r\n```"
      operationId: LicensesByLicenseGet
      x-api-path-slug: licenses-license-get
      parameters:
      - in: path
        name: _license
      responses:
        200:
          description: OK
      tags:
      - Video Conferencing
      - License
      - Details
  /roles/{_role}:
    get:
      summary: Get Role Details
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
      operationId: RolesByRoleGet
      x-api-path-slug: roles-role-get
      parameters:
      - in: path
        name: _role
      responses:
        200:
          description: OK
      tags:
      - Video Conferencing
      - Role
      - Details
  /people/me:
    get:
      summary: Get person details (me)
      description: |-
        Show the profile for the authenticated user.

        https://developer.webex.com/endpoint-people-me-get.html
      operationId: PeopleMeGet
      x-api-path-slug: peopleme-get
      responses:
        200:
          description: OK
      tags:
      - Video Conferencing
      - Person
      - Details
      - (me)
  /events/{_event}:
    get:
      summary: Get Events Details
      description: "Shows details for an event, by event ID.\r\nSpecify the event
        ID in the eventId parameter in the URI.\r\n\r\nhttps://developer.webex.com/endpoint-events-eventId-get.html"
      operationId: EventsByEventGet
      x-api-path-slug: events-event-get
      parameters:
      - in: path
        name: _event
      responses:
        200:
          description: OK
      tags:
      - Video Conferencing
      - Events
      - Details
  /organizations/{_organization}:
    get:
      summary: Get Organization Details
      description: "Shows details for an organization, by ID.\r\n\r\nSpecify the org
        ID in the orgId parameter in the URI.\r\n\r\nhttps://developer.webex.com/endpoint-organizations-orgId-get.html\r\n\r\nExample
        Response:\r\n``` json\r\n{\r\n  'id' : 'OTZhYmMyYWEtM2RjYy0xMWU1LWExNTItZmUzNDgxOWNkYzlh',\r\n
        \ 'displayName' : 'Acme, Inc.',\r\n  'created' : '2015-10-18T14:26:16+00:00'\r\n}\r\n```"
      operationId: OrganizationsByOrganizationGet
      x-api-path-slug: organizations-organization-get
      parameters:
      - in: path
        name: _organization
      responses:
        200:
          description: OK
      tags:
      - Video Conferencing
      - Organization
      - Details
  /people/{_person}:
    get:
      summary: Get person details
      description: "Shows details for a person, by ID.\r\n\r\nSpecify the person ID
        in the personId parameter in the URI.\r\n\r\nhttps://developer.webex.com/endpoint-people-personId-get.html"
      operationId: PeopleByPersonGet
      x-api-path-slug: people-person-get
      parameters:
      - in: path
        name: _person
      responses:
        200:
          description: OK
      tags:
      - Video Conferencing
      - Person
      - Details
  /memberships/{_membership}:
    get:
      summary: Get membership details
      description: "Get details for a membership by ID.\r\n\r\nSpecify the membership
        ID in the membershipId URI parameter.\r\n\r\nhttps://developer.webex.com/endpoint-memberships-membershipId-get.html"
      operationId: MembershipsByMembershipGet
      x-api-path-slug: memberships-membership-get
      parameters:
      - in: path
        name: _membership
      responses:
        200:
          description: OK
      tags:
      - Video Conferencing
      - Membership
      - Details
  /messages/{_message}:
    get:
      summary: Get message details
      description: |-
        Shows details for a message, by message ID.

        Specify the message ID in the messageId parameter in the URI.

        https://developer.webex.com/endpoint-messages-messageId-get.html
      operationId: MessagesByMessageGet
      x-api-path-slug: messages-message-get
      parameters:
      - in: path
        name: _message
      responses:
        200:
          description: OK
      tags:
      - Video Conferencing
      - Message
      - Details
  /rooms/{_room}:
    get:
      summary: Get Team room details
      description: "Shows details for a room, by ID.\r\n\r\nSpecify the room ID in
        the roomId parameter in the URI.\r\n\r\nhttps://developer.webex.com/endpoint-rooms-roomId-get.html"
      operationId: RoomsByRoomGet2
      x-api-path-slug: rooms-room-get
      parameters:
      - in: path
        name: _room
      responses:
        200:
          description: OK
      tags:
      - Video Conferencing
      - Team
      - Room
      - Details
  /team/memberships/{_membership}:
    get:
      summary: Get team membership details
      description: "Get details for a membership by ID.\r\n\r\nSpecify the membership
        ID in the membershipId URI parameter.\r\n\r\nhttps://developer.webex.com/endpoint-teammemberships-membershipId-get.html"
      operationId: TeamMembershipsByMembershipGet
      x-api-path-slug: teammemberships-membership-get
      parameters:
      - in: path
        name: _membership
      responses:
        200:
          description: OK
      tags:
      - Video Conferencing
      - Team
      - Membership
      - Details
  /teams/{_team}:
    get:
      summary: Get team details
      description: |-
        Show details for a team.

        https://developer.webex.com/endpoint-teams-teamId-get.html
      operationId: TeamsByTeamGet
      x-api-path-slug: teams-team-get
      parameters:
      - in: path
        name: _team
      responses:
        200:
          description: OK
      tags:
      - Video Conferencing
      - Team
      - Details
  /webhooks/{_webhook}:
    get:
      summary: Get webhook details1
      description: "Shows details for a webhook, by ID.\r\n\r\nSpecify the webhook
        ID in the webhookId parameter in the URI.\r\n\r\nhttps://developer.webex.com/endpoint-webhooks-webhookId-get.html"
      operationId: WebhooksByWebhookGet2
      x-api-path-slug: webhooks-webhook-get
      parameters:
      - in: path
        name: _webhook
      responses:
        200:
          description: OK
      tags:
      - Video Conferencing
      - Webhook
      - Details1