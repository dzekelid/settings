---
swagger: "2.0"
x-collection-name: RingCentral
x-complete: 0
info:
  title: RingCentral Get Notification Settings
  description: "Returns notification settings for the current extension.\nApp Permission\nReadAccounts\nUser
    Permission\nReadMessagesNotificationsSettings\nUsage Plan Group\nLight\nError
    Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadAccounts] permission\n\n\n403\nCMN-408\nIn
    order to call this API endpoint, user needs to have [ReadMessagesNotificationsSettings]
    permission for requested resource."
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
  /restapi/v1.0/account/{accountId}/call-recording:
    get:
      summary: Get Call Recording Settings
      description: |-
        Returns call recording settings.
        App Permission
        ReadAccounts
        User Permission
        ReadCompanyInfo
        Usage Plan Group
        Light
      operationId: loadCallRecordingSettings
      x-api-path-slug: restapiv1-0accountaccountidcallrecording-get
      parameters:
      - in: path
        name: accountId
      responses:
        200:
          description: OK
      tags:
      - Call
      - Recording
      - Settings
  /restapi/v1.0/account/{accountId}/call-recording/extensions:
    get:
      summary: Get Call Recording Extension Settings
      description: |-
        Returns the list of extensions to be recorded.
        App Permission
        ReadAccounts
        User Permission
        ReadCompanyInfo
        Usage Plan Group
        Medium
      operationId: listCallRecordingExtensionSettings
      x-api-path-slug: restapiv1-0accountaccountidcallrecordingextensions-get
      parameters:
      - in: path
        name: accountId
      responses:
        200:
          description: OK
      tags:
      - Call
      - Recording
      - Extension
      - Settings
  /restapi/v1.0/account/{accountId}/extension/{extensionId}/notification-settings:
    get:
      summary: Get Notification Settings
      description: "Returns notification settings for the current extension.\nApp
        Permission\nReadAccounts\nUser Permission\nReadMessagesNotificationsSettings\nUsage
        Plan Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
        Message\n   \n \n\n403\nCMN-401\nIn order to call this API endpoint, application
        needs to have [ReadAccounts] permission\n\n\n403\nCMN-408\nIn order to call
        this API endpoint, user needs to have [ReadMessagesNotificationsSettings]
        permission for requested resource."
      operationId: getNotificationSettings
      x-api-path-slug: restapiv1-0accountaccountidextensionextensionidnotificationsettings-get
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: path
        name: extensionId
        description: Internal identifier of an extension or tilde (~) to indicate
          the extension assigned to the account logged-in within the current session
      responses:
        200:
          description: OK
      tags:
      - Notification
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