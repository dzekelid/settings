---
swagger: "2.0"
x-collection-name: RingCentral
x-complete: 0
info:
  title: RingCentral Update Caller Blocking Settings
  description: "Updates the current call blocking settings of a user.\nApp Permission\nEditExtensions\nUser
    Permission\nEditBlockedNumbers\nUsage Plan Group\nLight\nError Codes\n\n \n  \n
    \  HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [greetings] value is invalid"
  version: 1.0.0
host: platform.ringcentral.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /restapi/v1.0/account/{accountId}/extension/{extensionId}/caller-blocking:
    get:
      summary: Get Caller Blocking Settings
      description: |-
        Returns the current call blocking settings of a user.
        App Permission
        ReadAccounts
        User Permission
        ReadBlockedNumbers
        Usage Plan Group
        Light
      operationId: listCallBlockingSettings
      x-api-path-slug: restapiv1-0accountaccountidextensionextensionidcallerblocking-get
      parameters:
      - in: path
        name: accountId
      - in: path
        name: extensionId
      responses:
        200:
          description: OK
      tags:
      - Caller
      - Blocking
      - Settings
    put:
      summary: Update Caller Blocking Settings
      description: "Updates the current call blocking settings of a user.\nApp Permission\nEditExtensions\nUser
        Permission\nEditBlockedNumbers\nUsage Plan Group\nLight\nError Codes\n\n \n
        \ \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
        [greetings] value is invalid"
      operationId: updateCallBlockingSettings
      x-api-path-slug: restapiv1-0accountaccountidextensionextensionidcallerblocking-put
      parameters:
      - in: path
        name: accountId
      - in: path
        name: extensionId
      responses:
        200:
          description: OK
      tags:
      - Caller
      - Blocking
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