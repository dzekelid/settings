---
swagger: "2.0"
x-collection-name: MockLab
x-complete: 0
info:
  title: MockLab Post Settings
  version: 1.0.0
  description: Update global settings
basePath: /__admin
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /settings:
    post:
      summary: Post Settings
      description: Update global settings
      operationId: postSettings
      x-api-path-slug: settings-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: Successful response
      tags:
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