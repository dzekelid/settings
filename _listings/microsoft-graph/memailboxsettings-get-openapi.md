---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph Get User Mailbox Settings
  description: Get user mailbox settings Get the user's mailboxSettings. This includes
    settings for automatic replies (notify people automatically upon receipt of their
    email), locale (language and country/region), and time zone.
  version: 1.0.0
host: graph.microsoft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /me/mailboxSettings:
    get:
      summary: Get User Mailbox Settings
      description: Get user mailbox settings Get the user's mailboxSettings. This
        includes settings for automatic replies (notify people automatically upon
        receipt of their email), locale (language and country/region), and time zone.
      operationId: GetUserMailboxSettings
      x-api-path-slug: memailboxsettings-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer &lt;token&gt;
        type: string
      responses:
        200:
          description: OK
      tags:
      - User
      - Mailbox
      - Settings
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