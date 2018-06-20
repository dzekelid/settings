---
swagger: "2.0"
x-collection-name: Instructure
x-complete: 1
info:
  title: Instructure Canvas Users API
  description: canvas-lms-includes-a-rest-api-for-accessing-and-modifying-data-externally-from-the-main-application-in-your-own-programs-and-scripts--
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
---