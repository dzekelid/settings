---
name: Gmail
x-slug: gmail
description: The Gmail API is a RESTful API that can be used to access Gmail mailboxes
  and send mail. For most web applications (including mobile apps), the Gmail API
  is the best choice for authorized access to a users Gmail data.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/gmail-icon.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Settings
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/gmail/apis.md
specificationVersion: "0.14"
apis:
- name: Gmail Get Auto-Forwarding Settings
  x-api-slug: gmail
  description: Gets the auto-forwarding setting for the specified account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/gmail-icon.png
  humanURL: https://www.google.com/gmail/
  baseURL: https://www.googleapis.com//gmail/v1/users//{userId}/settings/autoForwarding
  tags: Settings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/gmail/useridsettingsautoforwarding-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/gmail/useridsettingsautoforwarding-get-openapi.md
- name: Gmail Update Auto-Forwarding Settings
  x-api-slug: gmail
  description: |-
    Updates the auto-forwarding setting for the specified account. A verified forwarding address must be specified when auto-forwarding is enabled.

    This method is only available to service account clients that have been delegated domain-wide authority.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/gmail-icon.png
  humanURL: https://www.google.com/gmail/
  baseURL: https://www.googleapis.com//gmail/v1/users//{userId}/settings/autoForwarding
  tags: Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/gmail/useridsettingsautoforwarding-put-openapi.md
- name: Gmail Gets IMAP Settings
  x-api-slug: gmail
  description: Gets IMAP settings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/gmail-icon.png
  humanURL: https://www.google.com/gmail/
  baseURL: https://www.googleapis.com//gmail/v1/users//{userId}/settings/imap
  tags: IMAP Settings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/gmail/useridsettingsimap-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/gmail/useridsettingsimap-get-openapi.md
- name: Gmail Update IMAP Setting
  x-api-slug: gmail
  description: Updates IMAP settings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/gmail-icon.png
  humanURL: https://www.google.com/gmail/
  baseURL: https://www.googleapis.com//gmail/v1/users//{userId}/settings/imap
  tags: IMAP Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/gmail/useridsettingsimap-put-openapi.md
- name: Gmail Update IMAP Setting
  x-api-slug: gmail
  description: Updates POP settings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/gmail-icon.png
  humanURL: https://www.google.com/gmail/
  baseURL: https://www.googleapis.com//gmail/v1/users//{userId}/settings/pop
  tags: POP Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/gmail/useridsettingspop-put-openapi.md
- name: Gmail Get Vacation Settings
  x-api-slug: gmail
  description: Gets vacation responder settings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/gmail-icon.png
  humanURL: https://www.google.com/gmail/
  baseURL: https://www.googleapis.com//gmail/v1/users//{userId}/settings/vacation
  tags: Vacation Settings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/gmail/useridsettingsvacation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/gmail/useridsettingsvacation-get-openapi.md
- name: Gmail Update Vacation Settings
  x-api-slug: gmail
  description: Updates vacation responder settings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/gmail-icon.png
  humanURL: https://www.google.com/gmail/
  baseURL: https://www.googleapis.com//gmail/v1/users//{userId}/settings/vacation
  tags: Vacation Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/gmail/useridsettingsvacation-put-openapi.md
- name: Gmail
  x-api-slug: gmail
  description: The Gmail API is a RESTful API that can be used to access Gmail mailboxes
    and send mail. For most web applications (including mobile apps), the Gmail API
    is the best choice for authorized access to a users Gmail data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/gmail-icon.png
  humanURL: https://www.google.com/gmail/
  baseURL: https://www.googleapis.com//gmail/v1/users
  tags: Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/gmail/openapi.md
x-common:
- type: x-auth-scopes
  url: https://developers.google.com/gmail/api/auth/scopes
- type: x-authentication
  url: https://developers.google.com/gmail/api/auth/about-auth
- type: x-developer
  url: https://developers.google.com/gmail/api/
- type: x-documentation
  url: https://developers.google.com/gmail/api/v1/reference/
- type: x-twitter
  url: https://twitter.com/gmail
- type: x-website
  url: https://www.google.com/gmail/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---