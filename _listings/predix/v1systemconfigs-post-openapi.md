---
swagger: "2.0"
x-collection-name: Predix
x-complete: 0
info:
  title: Predix Assets Update tenant-specific configuration settings
  description: This can be used to enable or disable the audit feature.
  version: 1.0.0
host: predix-apphub-arcs-prod.run.aws-usw02-pr.ice.predix.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/system/configs:
    get:
      summary: Get tenant-specific configuration settings
      description: This can be used to verify whether the audit feature is enabled.
      operationId: getV1SystemConfigs
      x-api-path-slug: v1systemconfigs-get
      responses:
        200:
          description: Successful response
      tags:
      - Tenant-specific
      - Configuration
      - Settings
    post:
      summary: Update tenant-specific configuration settings
      description: This can be used to enable or disable the audit feature.
      operationId: postV1SystemConfigs
      x-api-path-slug: v1systemconfigs-post
      parameters:
      - in: body
        name: body
        description: Array of configs to create
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: Successful response
      tags:
      - Tenant-specific
      - Configuration
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