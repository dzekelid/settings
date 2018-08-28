---
swagger: "2.0"
x-collection-name: Vestorly
x-complete: 0
info:
  title: Vestorly Put Newsletter Settings
  description: Update a single newsletter setting by ID
  termsOfService: http://www.vestorly.com/terms/
  contact:
    name: Vestorly Team
  version: 1.0.0
host: staging.vestorly.com
basePath: /api/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /newsletter_settings:
    get:
      summary: Get Newsletter Settings
      description: Returns all newsletter settings
      operationId: findNewsletterSettings
      x-api-path-slug: newsletter-settings-get
      parameters:
      - in: query
        name: access_token
        description: OAuth Token
      - in: query
        name: vestorly-auth
        description: Vestorly Auth Token
      - in: query
        name: vestorly_auth
        description: Vestorly Auth Token
      responses:
        200:
          description: OK
      tags:
      - Newsletter
      - Settings
  /newsletter_settings/{id}:
    get:
      summary: Get Newsletter Settings
      description: Returns a single newsletter settings if the user has access
      operationId: findNewsletterSettingsByID
      x-api-path-slug: newsletter-settingsid-get
      parameters:
      - in: query
        name: access_token
        description: OAuth Token
      - in: path
        name: id
        description: Mongo ID of newsletter settings to fetch
      - in: query
        name: vestorly-auth
        description: Vestorly Auth Token
      - in: query
        name: vestorly_auth
        description: Vestorly Auth Token
      responses:
        200:
          description: OK
      tags:
      - Newsletter
      - Settings
    put:
      summary: Put Newsletter Settings
      description: Update a single newsletter setting by ID
      operationId: updateNewsletterSettingsByID
      x-api-path-slug: newsletter-settingsid-put
      parameters:
      - in: query
        name: access_token
        description: OAuth Token
      - in: path
        name: id
        description: Mongo ID of newsletter settings to update
      - in: body
        name: newsletter_setting
        description: newsletter settings
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: vestorly-auth
        description: Vestorly Auth Token
      - in: query
        name: vestorly_auth
        description: Vestorly Auth Token
      responses:
        200:
          description: OK
      tags:
      - Newsletter
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