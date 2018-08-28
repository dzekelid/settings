---
swagger: "2.0"
x-collection-name: Google Glass
x-complete: 0
info:
  title: Google Glass APIs Get Setting
  description: Gets a single setting by ID.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: www.googleapis.com
basePath: /mirror/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /settings/{id}:
    get:
      summary: Get Setting
      description: Gets a single setting by ID.
      operationId: mirror.settings.get
      x-api-path-slug: settingsid-get
      parameters:
      - in: path
        name: id
        description: The ID of the setting
      responses:
        200:
          description: OK
      tags:
      - Setting
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