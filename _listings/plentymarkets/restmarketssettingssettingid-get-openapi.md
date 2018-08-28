---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets Get market settings
  description: Gets market settings. The market settings ID must be specified.
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/markets/settings:
    get:
      summary: List market settings
      description: Lists market settings. The marketplace ID and the type must be
        specified.
      operationId: getRestMarketsSettings
      x-api-path-slug: restmarketssettings-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Market
      - Settings
    post:
      summary: Create market settings
      description: Creates new market settings by given data. The marketplace ID and
        the type must be specified.
      operationId: postRestMarketsSettings
      x-api-path-slug: restmarketssettings-post
      responses:
        200:
          description: OK
      tags:
      - Market
      - Settings
  /rest/markets/settings/bulk:
    post:
      summary: Create market settings
      description: Creates new market settings by given data. The marketplace ID and
        the type must be specified.
      operationId: postRestMarketsSettingsBulk
      x-api-path-slug: restmarketssettingsbulk-post
      responses:
        200:
          description: OK
      tags:
      - Market
      - Settings
    put:
      summary: Update market settings
      description: Updates market settings. The market settings ID must be specified.
      operationId: putRestMarketsSettingsBulk
      x-api-path-slug: restmarketssettingsbulk-put
      responses:
        200:
          description: OK
      tags:
      - Market
      - Settings
  /rest/markets/settings/{settingId}:
    delete:
      summary: Delete market settings
      description: Deletes market settings. The market settings ID must be specified.
      operationId: deleteRestMarketsSettingsSetting
      x-api-path-slug: restmarketssettingssettingid-delete
      parameters:
      - in: path
        name: settingId
      responses:
        200:
          description: OK
      tags:
      - Market
      - Settings
    get:
      summary: Get market settings
      description: Gets market settings. The market settings ID must be specified.
      operationId: getRestMarketsSettingsSetting
      x-api-path-slug: restmarketssettingssettingid-get
      parameters:
      - in: path
        name: settingId
      responses:
        200:
          description: OK
      tags:
      - Market
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