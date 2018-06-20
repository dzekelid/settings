---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 1
info:
  title: Microsoft Graph API
  description: microsoft-graph-exposes-multiple-apis-from-office-365-and-other-microsoft-cloud-services-through-a-single-endpoint-httpsgraph-microsoft-com--microsoft-graph-simplifies-queries-that-would-otherwise-be-more-complex-
  version: 1.0.0
host: graph.microsoft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /me/mailboxSettings:
    get:
      summary: Get User Mailbox Settings
      description: Get user mailbox settings Get the user's mailboxSettings. This
        includes settings for automatic replies (notify people automatically upon
        receipt of their email), locale (language and country/region), and time zone.
      operationId: GetUserMailboxSettings
      x-api-path-slug: memailboxsettings-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer &lt;token&gt;
        type: string
      responses:
        200:
          description: OK
      tags:
      - User
      - Mailbox
      - Settings
    patch:
      summary: Update User Mailbox Settings
      description: Update user mailbox settings Update one or more settings for the
        user's mailbox. This includes settings for automatic replies (notify people
        automatically upon receipt of their email), locale, or time zone.
      operationId: UpdateUserMailboxSettings
      x-api-path-slug: memailboxsettings-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer &lt;token&gt;
        type: string
      responses:
        200:
          description: OK
      tags:
      - User
      - Mailbox
      - Settings
  /users/{id|userPrincipalName}/mailboxSettings:
    get:
      summary: Get User Mailbox Settings
      description: Get user mailbox settings Get the user's mailboxSettings. This
        includes settings for automatic replies (notify people automatically upon
        receipt of their email), locale (language and country/region), and time zone.
      operationId: GetUserMailboxSettings
      x-api-path-slug: usersiduserprincipalnamemailboxsettings-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer &lt;token&gt;
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - User
      - Mailbox
      - Settings
    patch:
      summary: Update User Mailbox Settings
      description: Update user mailbox settings Update one or more settings for the
        user's mailbox. This includes settings for automatic replies (notify people
        automatically upon receipt of their email), locale, or time zone.
      operationId: UpdateUserMailboxSettings
      x-api-path-slug: usersiduserprincipalnamemailboxsettings-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer &lt;token&gt;
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - User
      - Mailbox
      - Settings
  /me/mailboxSettings/automaticRepliesSetting:
    get:
      summary: Get User Mailbox Settings
      description: Get user mailbox settings Get the user's mailboxSettings. This
        includes settings for automatic replies (notify people automatically upon
        receipt of their email), locale (language and country/region), and time zone.
      operationId: GetUserMailboxSettings
      x-api-path-slug: memailboxsettingsautomaticrepliessetting-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer &lt;token&gt;
        type: string
      responses:
        200:
          description: OK
      tags:
      - User
      - Mailbox
      - Settings
  /users/{id|userPrincipalName}/mailboxSettings/automaticRepliesSetting:
    get:
      summary: Get User Mailbox Settings
      description: Get user mailbox settings Get the user's mailboxSettings. This
        includes settings for automatic replies (notify people automatically upon
        receipt of their email), locale (language and country/region), and time zone.
      operationId: GetUserMailboxSettings
      x-api-path-slug: usersiduserprincipalnamemailboxsettingsautomaticrepliessetting-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer &lt;token&gt;
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - User
      - Mailbox
      - Settings
  /me/mailboxSettings/language:
    get:
      summary: Get User Mailbox Settings
      description: Get user mailbox settings Get the user's mailboxSettings. This
        includes settings for automatic replies (notify people automatically upon
        receipt of their email), locale (language and country/region), and time zone.
      operationId: GetUserMailboxSettings
      x-api-path-slug: memailboxsettingslanguage-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer &lt;token&gt;
        type: string
      responses:
        200:
          description: OK
      tags:
      - User
      - Mailbox
      - Settings
  /users/{id|userPrincipalName}/mailboxSettings/language:
    get:
      summary: Get User Mailbox Settings
      description: Get user mailbox settings Get the user's mailboxSettings. This
        includes settings for automatic replies (notify people automatically upon
        receipt of their email), locale (language and country/region), and time zone.
      operationId: GetUserMailboxSettings
      x-api-path-slug: usersiduserprincipalnamemailboxsettingslanguage-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer &lt;token&gt;
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - User
      - Mailbox
      - Settings
  /me/mailboxSettings/timeZone:
    get:
      summary: Get User Mailbox Settings
      description: Get user mailbox settings Get the user's mailboxSettings. This
        includes settings for automatic replies (notify people automatically upon
        receipt of their email), locale (language and country/region), and time zone.
      operationId: GetUserMailboxSettings
      x-api-path-slug: memailboxsettingstimezone-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer &lt;token&gt;
        type: string
      responses:
        200:
          description: OK
      tags:
      - User
      - Mailbox
      - Settings
  /users/{id|userPrincipalName}/mailboxSettings/timeZone:
    get:
      summary: Get User Mailbox Settings
      description: Get user mailbox settings Get the user's mailboxSettings. This
        includes settings for automatic replies (notify people automatically upon
        receipt of their email), locale (language and country/region), and time zone.
      operationId: GetUserMailboxSettings
      x-api-path-slug: usersiduserprincipalnamemailboxsettingstimezone-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer &lt;token&gt;
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - User
      - Mailbox
      - Settings
---