---
swagger: "2.0"
x-collection-name: 3dcart
x-complete: 0
info:
  title: 3dcart This method is used to update the Store Settings in the database.
  version: 1.0.0
  description: This method is used to update the store settings in the database..
host: apirest.3dcart.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /3dCartWebAPI/v1/StoreSettings:
    get:
      summary: Get the Store Settings
      description: Get the store settings.
      operationId: StoreSettings_GetStoreSettings
      x-api-path-slug: 3dcartwebapiv1storesettings-get
      parameters:
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - Store
      - Settings
    put:
      summary: This method is used to update the Store Settings in the database.
      description: This method is used to update the store settings in the database..
      operationId: StoreSettings_UpdateStoreSettings
      x-api-path-slug: 3dcartwebapiv1storesettings-put
      parameters:
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: body
        name: settings
        description: A Json or XML object containing the Store Settings
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - This
      - Method
      - Is
      - Used
      - To
      - Update
      - Store
      - Settings
      - In
      - Database
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