---
swagger: "2.0"
x-collection-name: Gmail
x-complete: 1
info:
  title: Gmail
  description: access-gmail-mailboxes-including-sending-user-email-
  contact:
    name: Google
    url: https://google.com
  version: v1
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
  /{userId}/settings/imap:
    get:
      summary: Gets IMAP Settings
      description: Gets IMAP settings.
      operationId: gmail.users.settings.getImap
      x-api-path-slug: useridsettingsimap-get
      parameters:
      - in: path
        name: userId
        description: Users email address
      responses:
        200:
          description: OK
      tags:
      - IMAP Settings
    put:
      summary: Update IMAP Setting
      description: Updates IMAP settings.
      operationId: gmail.users.settings.updateImap
      x-api-path-slug: useridsettingsimap-put
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
      - IMAP Settings
  /{userId}/settings/pop:
    put:
      summary: Update IMAP Setting
      description: Updates POP settings.
      operationId: gmail.users.settings.updatePop
      x-api-path-slug: useridsettingspop-put
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
      - POP Settings
  /{userId}/settings/vacation:
    get:
      summary: Get Vacation Settings
      description: Gets vacation responder settings.
      operationId: gmail.users.settings.getVacation
      x-api-path-slug: useridsettingsvacation-get
      parameters:
      - in: path
        name: userId
        description: Users email address
      responses:
        200:
          description: OK
      tags:
      - Vacation Settings
    put:
      summary: Update Vacation Settings
      description: Updates vacation responder settings.
      operationId: gmail.users.settings.updateVacation
      x-api-path-slug: useridsettingsvacation-put
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
      - Vacation Settings
---