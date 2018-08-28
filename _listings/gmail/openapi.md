swagger: "2.0"
x-collection-name: Gmail
x-complete: 1
info:
  title: Gmail
  version: 1.0.0
host: www.googleapis.com
basePath: /gmail/v1/users
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{userId}/settings/autoForwarding:
    get:
      summary: Get Auto-Forwarding Settings
      description: Gets the auto-forwarding setting for the specified account.
      operationId: gmail.users.settings.getAutoForwarding
      x-api-path-slug: useridsettingsautoforwarding-get
      parameters:
      - in: path
        name: userId
        description: Users email address
      responses:
        200:
          description: OK
      tags:
      - Settings
    put:
      summary: Update Auto-Forwarding Settings
      description: |-
        Updates the auto-forwarding setting for the specified account. A verified forwarding address must be specified when auto-forwarding is enabled.

        This method is only available to service account clients that have been delegated domain-wide authority.
      operationId: gmail.users.settings.updateAutoForwarding
      x-api-path-slug: useridsettingsautoforwarding-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: userId
        description: Users email address
      responses:
        200:
          description: OK
      tags:
      - Settings