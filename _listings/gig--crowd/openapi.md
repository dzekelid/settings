swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 1
info:
  title: GIG & Crowd
  version: 1.0.0
host: gigandcrowd.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/admin/settings/{userId}:
    get:
      summary: Get Admin Settings Userid
      description: Get admin settings userid.
      operationId: getApiV1AdminSettingsUser
      x-api-path-slug: apiv1adminsettingsuserid-get
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: userId
      responses:
        200:
          description: OK
      tags:
      - Admin
      - Settings
      - Userid
    post:
      summary: Post Admin Settings Userid
      description: Post admin settings userid.
      operationId: postApiV1AdminSettingsUser
      x-api-path-slug: apiv1adminsettingsuserid-post
      parameters:
      - in: header
        name: Authorization
      - in: body
        name: request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: userId
      responses:
        200:
          description: OK
      tags:
      - Admin
      - Settings
      - Userid
  /api/v1/managers/settings:
    get:
      summary: Get Managers Settings
      description: Get managers settings.
      operationId: getApiV1ManagersSettings
      x-api-path-slug: apiv1managerssettings-get
      parameters:
      - in: header
        name: Authorization
      responses:
        200:
          description: OK
      tags:
      - Managers
      - Settings