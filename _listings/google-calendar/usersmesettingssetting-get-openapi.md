---
swagger: "2.0"
x-collection-name: Google Calendar
x-complete: 0
info:
  title: Google Calendar Get Setting
  description: Returns a single user setting.
  contact:
    name: Google
    url: https://google.com
  version: v3/
host: www.googleapis.com
basePath: /calendar/v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/me/settings:
    get:
      summary: Get Settings
      description: Returns all user settings for the authenticated user.
      operationId: calendar.settings.list
      x-api-path-slug: usersmesettings-get
      parameters:
      - in: query
        name: maxResults
        description: Maximum number of entries returned on one result page
      - in: query
        name: pageToken
        description: Token specifying which result page to return
      - in: query
        name: syncToken
        description: Token obtained from the nextSyncToken field returned on the last
          page of results from the previous list request
      responses:
        200:
          description: OK
      tags:
      - Setting
  /users/me/settings/watch:
    post:
      summary: Watch Settings
      description: Watch for changes to Settings resources.
      operationId: calendar.settings.watch
      x-api-path-slug: usersmesettingswatch-post
      parameters:
      - in: query
        name: maxResults
        description: Maximum number of entries returned on one result page
      - in: query
        name: pageToken
        description: Token specifying which result page to return
      - in: body
        name: resource
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: syncToken
        description: Token obtained from the nextSyncToken field returned on the last
          page of results from the previous list request
      responses:
        200:
          description: OK
      tags:
      - Setting
  /users/me/settings/{setting}:
    get:
      summary: Get Setting
      description: Returns a single user setting.
      operationId: calendar.settings.get
      x-api-path-slug: usersmesettingssetting-get
      parameters:
      - in: path
        name: setting
        description: The id of the user setting
      responses:
        200:
          description: OK
      tags:
      - Setting
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