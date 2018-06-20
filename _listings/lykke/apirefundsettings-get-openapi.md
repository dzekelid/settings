---
swagger: "2.0"
x-collection-name: Lykke
x-complete: 0
info:
  title: Lykke Get API Refundsettings
  version: 1.0.0
  description: Get api refundsettings.
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/AppSettings:
    get:
      summary: Get API Application Settings
      description: Get api application settings.
      operationId: ApiAppSettingsGet
      x-api-path-slug: apiappsettings-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - Application
      - Settings
  /api/Ethereum/settings:
    get:
      summary: Get API Ethereum Settings
      description: Get api ethereum settings.
      operationId: ApiEthereumSettingsGet
      x-api-path-slug: apiethereumsettings-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - Ethereum
      - Settings
  /api/MyLykkeSettings:
    get:
      summary: Get API Mylykkesettings
      description: Get api mylykkesettings.
      operationId: ApiMyLykkeSettingsGet
      x-api-path-slug: apimylykkesettings-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - Mylykkesettings
  /api/PushSettings:
    get:
      summary: Get API Pushsettings
      description: Get api pushsettings.
      operationId: ApiPushSettingsGet
      x-api-path-slug: apipushsettings-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - Pushsettings
    post:
      summary: Add API Pushsettings
      description: Add api pushsettings.
      operationId: ApiPushSettingsPost
      x-api-path-slug: apipushsettings-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: model
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Pushsettings
  /api/RefundSettings:
    get:
      summary: Get API Refundsettings
      description: Get api refundsettings.
      operationId: ApiRefundSettingsGet
      x-api-path-slug: apirefundsettings-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - Refundsettings
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