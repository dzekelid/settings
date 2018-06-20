---
name: Pingdom
x-slug: pingdom
description: Monitor your website???s availability and performance for free with Pingdom
  and always be the first to know when your website is down. No installation required.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
x-kinRank: "7"
x-alexaRank: "5592"
tags: Settings
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/pingdom/apis.md
specificationVersion: "0.14"
apis:
- name: Settings API Get Account Settings
  x-api-slug: settings-api
  description: Returns all account-specific settings.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: |-
    https://api.pingdom.com///
        /api/{version}/settings
  tags: Settings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/pingdom/apiversionsettings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/pingdom/apiversionsettings-get-openapi.md
- name: Settings API
  x-api-slug: settings-api
  description: Monitor your website???s availability and performance for free with
    Pingdom and always be the first to know when your website is down. No installation
    required.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: https://api.pingdom.com//
  tags: Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/pingdom/openapi.md
x-common:
- type: x-base
  url: https://api.pingdom.com
- type: x-blog
  url: http://royal.pingdom.com/
- type: x-blog-rss
  url: http://royal.pingdom.com/feed/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/pingdom
- type: x-crunchbase
  url: https://crunchbase.com/organization/pingdom
- type: x-developer
  url: https://www.pingdom.com/features/api/
- type: x-email
  url: sales@pingdom.com
- type: x-github
  url: https://github.com/Pingdom
- type: x-pricing
  url: https://www.pingdom.com/pricing
- type: x-twitter
  url: https://twitter.com/#!/pingdom
- type: x-website
  url: http://www.pingdom.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---