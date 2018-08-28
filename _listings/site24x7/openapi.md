---
swagger: "2.0"
x-collection-name: Site24x7
x-complete: 1
info:
  title: SLA Setting API
  description: the-sla-setting-api-
  version: 1.0.0
host: www.site24x7.com.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /sla_settings/{sla_id}:
    get:
      summary: Get SLA Report
      description: Retrieve the configuration of a SLA Report.
      operationId: get-sla-report
      x-api-path-slug: sla-settingssla-id-get
      responses:
        "":
          description: ""
        400:
          description: Bad input parameter
        401:
          description: Bad or expired token
        403:
          description: Bad OAuth request (wrong consumer key, bad nonce, expired timestamp
        404:
          description: File or folder not found at the specified path
        405:
          description: Request method not expected (generally should be GET or POST)
        429:
          description: Your app is making too many requests and is being rate limited
        503:
          description: If the response includes the Retry-After header, this means
            your OAuth 1
        507:
          description: User is over Dropbox storage quota
        5xx:
          description: Server error
        200:
          description: OK
      tags:
      - SLA Settings
    delete:
      summary: Delete SLA Report
      description: Delete the existing SLA Report.
      operationId: delete-sla-report
      x-api-path-slug: sla-settingssla-id-delete
      responses:
        200:
          description: OK
      tags:
      - SLA Settings
---