---
swagger: "2.0"
x-collection-name: Bookeo
x-complete: 0
info:
  title: Bookeo Get information, location and contact details about the business
  version: 1.0.0
  description: Get information, location and contact details about the business.
host: api.bookeo.com
basePath: /v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /settings/apikeyinfo:
    get:
      summary: Get information about your own API Key
      description: Get information about your own api key.
      operationId: getSettingsApikeyinfo
      x-api-path-slug: settingsapikeyinfo-get
      responses:
        200:
          description: OK
      tags:
      - Settings
      - Apikeyinfo
  /settings/business:
    get:
      summary: Get information, location and contact details about the business
      description: Get information, location and contact details about the business.
      operationId: getSettingsBusiness
      x-api-path-slug: settingsbusiness-get
      responses:
        200:
          description: OK
      tags:
      - Settings
      - Business
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