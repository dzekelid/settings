---
swagger: "2.0"
x-collection-name: Instructure
x-complete: 0
info:
  title: Instructure Canvas Users API Update user settings.
  description: Update user settings..
  termsOfService: https://www.canvaslms.com/policies/api-policy
  version: v1
host: canvas.instructure.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/{id}/settings:
    get:
      summary: Update user settings.
      description: Update user settings..
      operationId: update-user-settings
      x-api-path-slug: usersidsettings-get
      parameters:
      - in: query
        name: manual_mark_as_read
        description: If true, require user to manually mark discussion posts as read
          (don&#39;tnauto-mark as read)
      responses:
        200:
          description: OK
      tags:
      - Users
      - Id
      - Settings
    put:
      summary: Update user settings.
      description: Update user settings..
      operationId: update-user-settings
      x-api-path-slug: usersidsettings-put
      parameters:
      - in: query
        name: manual_mark_as_read
        description: If true, require user to manually mark discussion posts as read
          (don&#39;tnauto-mark as read)
      responses:
        200:
          description: OK
      tags:
      - Users
      - Id
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