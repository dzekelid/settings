---
name: Microsoft Graph
x-slug: microsoft-graph
description: 'Microsoft Graph exposes multiple APIs from Office 365 and other Microsoft
  cloud services through a single endpoint: https://graph.microsoft.com. Microsoft
  Graph simplifies queries that would otherwise be more complex. You can use Microsoft
  Graph to: Access data from multiple Microsoft cloud services, including Azure Active
  Directory, Exchange Online as part of Office 365, SharePoint, OneDrive, OneNote,
  and Planner. Navigate between entities and relationships. Access intelligence and
  insights from the Microsoft cloud (for commercial users).'
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Settings
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/microsoft-graph/apis.md
specificationVersion: "0.14"
apis:
- name: Microsoft Graph Get User Mailbox Settings
  x-api-slug: microsoft-graph
  description: Get user mailbox settings Get the user's mailboxSettings. This includes
    settings for automatic replies (notify people automatically upon receipt of their
    email), locale (language and country/region), and time zone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailboxSettings
  tags: User, Mailbox, Settings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/microsoft-graph/memailboxsettings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/microsoft-graph/memailboxsettings-get-openapi.md
- name: Microsoft Graph Get User Mailbox Settings
  x-api-slug: microsoft-graph
  description: Get user mailbox settings Get the user's mailboxSettings. This includes
    settings for automatic replies (notify people automatically upon receipt of their
    email), locale (language and country/region), and time zone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/mailboxSettings
  tags: User, Mailbox, Settings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/microsoft-graph/usersiduserprincipalnamemailboxsettings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/microsoft-graph/usersiduserprincipalnamemailboxsettings-get-openapi.md
- name: Microsoft Graph Get User Mailbox Settings
  x-api-slug: microsoft-graph
  description: Get user mailbox settings Get the user's mailboxSettings. This includes
    settings for automatic replies (notify people automatically upon receipt of their
    email), locale (language and country/region), and time zone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailboxSettings/automaticRepliesSetting
  tags: User, Mailbox, Settings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/microsoft-graph/memailboxsettingsautomaticrepliessetting-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/microsoft-graph/memailboxsettingsautomaticrepliessetting-get-openapi.md
- name: Microsoft Graph Get User Mailbox Settings
  x-api-slug: microsoft-graph
  description: Get user mailbox settings Get the user's mailboxSettings. This includes
    settings for automatic replies (notify people automatically upon receipt of their
    email), locale (language and country/region), and time zone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/mailboxSettings/automaticRepliesSetting
  tags: User, Mailbox, Settings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/microsoft-graph/usersiduserprincipalnamemailboxsettingsautomaticrepliessetting-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/microsoft-graph/usersiduserprincipalnamemailboxsettingsautomaticrepliessetting-get-openapi.md
- name: Microsoft Graph Get User Mailbox Settings
  x-api-slug: microsoft-graph
  description: Get user mailbox settings Get the user's mailboxSettings. This includes
    settings for automatic replies (notify people automatically upon receipt of their
    email), locale (language and country/region), and time zone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailboxSettings/language
  tags: User, Mailbox, Settings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/microsoft-graph/memailboxsettingslanguage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/microsoft-graph/memailboxsettingslanguage-get-openapi.md
- name: Microsoft Graph Get User Mailbox Settings
  x-api-slug: microsoft-graph
  description: Get user mailbox settings Get the user's mailboxSettings. This includes
    settings for automatic replies (notify people automatically upon receipt of their
    email), locale (language and country/region), and time zone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/mailboxSettings/language
  tags: User, Mailbox, Settings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/microsoft-graph/usersiduserprincipalnamemailboxsettingslanguage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/microsoft-graph/usersiduserprincipalnamemailboxsettingslanguage-get-openapi.md
- name: Microsoft Graph Get User Mailbox Settings
  x-api-slug: microsoft-graph
  description: Get user mailbox settings Get the user's mailboxSettings. This includes
    settings for automatic replies (notify people automatically upon receipt of their
    email), locale (language and country/region), and time zone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailboxSettings/timeZone
  tags: User, Mailbox, Settings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/microsoft-graph/memailboxsettingstimezone-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/microsoft-graph/memailboxsettingstimezone-get-openapi.md
- name: Microsoft Graph Get User Mailbox Settings
  x-api-slug: microsoft-graph
  description: Get user mailbox settings Get the user's mailboxSettings. This includes
    settings for automatic replies (notify people automatically upon receipt of their
    email), locale (language and country/region), and time zone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/mailboxSettings/timeZone
  tags: User, Mailbox, Settings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/microsoft-graph/usersiduserprincipalnamemailboxsettingstimezone-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/microsoft-graph/usersiduserprincipalnamemailboxsettingstimezone-get-openapi.md
- name: Microsoft Graph Update User Mailbox Settings
  x-api-slug: microsoft-graph
  description: Update user mailbox settings Update one or more settings for the user's
    mailbox. This includes settings for automatic replies (notify people automatically
    upon receipt of their email), locale, or time zone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailboxSettings
  tags: User, Mailbox, Settings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/microsoft-graph/memailboxsettings-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/microsoft-graph/memailboxsettings-patch-openapi.md
- name: Microsoft Graph Update User Mailbox Settings
  x-api-slug: microsoft-graph
  description: Update user mailbox settings Update one or more settings for the user's
    mailbox. This includes settings for automatic replies (notify people automatically
    upon receipt of their email), locale, or time zone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/mailboxSettings
  tags: User, Mailbox, Settings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/microsoft-graph/usersiduserprincipalnamemailboxsettings-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/microsoft-graph/usersiduserprincipalnamemailboxsettings-patch-openapi.md
- name: Microsoft Graph
  x-api-slug: microsoft-graph
  description: 'Microsoft Graph exposes multiple APIs from Office 365 and other Microsoft
    cloud services through a single endpoint: https://graph.microsoft.com. Microsoft
    Graph simplifies queries that would otherwise be more complex. You can use Microsoft
    Graph to: Access data from multiple Microsoft cloud services, including Azure
    Active Directory, Exchange Online as part of Office 365, SharePoint, OneDrive,
    OneNote, and Planner. Navigate between entities and relationships. Access intelligence
    and insights from the Microsoft cloud (for commercial users).'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/microsoft-graph/openapi.md
x-common:
- type: x-change-loge
  url: https://developer.microsoft.com/en-us/graph/docs/overview/changelog
- type: x-documentation
  url: https://developer.microsoft.com/en-us/graph/docs
- type: x-explorer
  url: https://developer.microsoft.com/en-us/graph/graph-explorer
- type: x-getting-started
  url: https://developer.microsoft.com/en-us/graph/docs/get-started/rest
- type: x-github
  url: https://github.com/microsoftgraph
- type: x-sdk
  url: https://developer.microsoft.com/en-us/graph/code-samples-and-sdks
- type: x-website
  url: https://developer.microsoft.com/en-us/graph/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---