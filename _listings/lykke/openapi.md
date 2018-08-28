swagger: "2.0"
x-collection-name: Lykke
x-complete: 1
info:
  title: Wallet_Api
  version: 1.0.0
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
  /api/SettingSignOrder:
    post:
      summary: Add API Settingsignorder
      description: Add api settingsignorder.
      operationId: ApiSettingSignOrderPost
      x-api-path-slug: apisettingsignorder-post
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
      - Settingsignorder
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
    post:
      summary: Add API Refundsettings
      description: Add api refundsettings.
      operationId: ApiRefundSettingsPost
      x-api-path-slug: apirefundsettings-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: refundAddressModel
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Refundsettings