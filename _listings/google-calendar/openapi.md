swagger: "2.0"
x-collection-name: Google Calendar
x-complete: 1
info:
  title: Google Calendar
  description: manipulates-events-and-other-calendar-data-
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