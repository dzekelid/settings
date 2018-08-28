---
swagger: "2.0"
x-collection-name: Gmail
x-complete: 0
info:
  title: Gmail Gets IMAP Settings
  description: Gets IMAP settings.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: www.googleapis.com
basePath: /gmail/v1/users
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{userId}/settings/autoForwarding:
    get:
      summary: Get Auto-Forwarding Settings
      description: Gets the auto-forwarding setting for the specified account.
      operationId: gmail.users.settings.getAutoForwarding
      x-api-path-slug: useridsettingsautoforwarding-get
      parameters:
      - in: path
        name: userId
        description: Users email address
      responses:
        200:
          description: OK
      tags:
      - Settings
    put:
      summary: Update Auto-Forwarding Settings
      description: |-
        Updates the auto-forwarding setting for the specified account. A verified forwarding address must be specified when auto-forwarding is enabled.

        This method is only available to service account clients that have been delegated domain-wide authority.
      operationId: gmail.users.settings.updateAutoForwarding
      x-api-path-slug: useridsettingsautoforwarding-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: userId
        description: Users email address
      responses:
        200:
          description: OK
      tags:
      - Settings
  /{userId}/settings/imap:
    get:
      summary: Gets IMAP Settings
      description: Gets IMAP settings.
      operationId: gmail.users.settings.getImap
      x-api-path-slug: useridsettingsimap-get
      parameters:
      - in: path
        name: userId
        description: Users email address
      responses:
        200:
          description: OK
      tags:
      - IMAP Settings
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