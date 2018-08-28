---
name: RingCentral
x-slug: ringcentral
description: 'RingCentral, Inc. (NYSE: RNG) is a global provider of cloud enterprise
  unified communications and collaboration solutions. More flexible and cost-effective
  than legacy on-premise systems, RingCentral empowers today&rsquo;s mobile and distributed
  workforces to be connected anywhere and on any device through voice, video, team
  messaging, collaboration, SMS, conferencing, online meetings, contact center, and
  fax. RingCentral provides an open platform that integrates with today&rsquo;s leading
  business apps while giving customers the flexibility to customize their own workflows.'
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
x-kinRank: "7"
x-alexaRank: "7180"
tags: Settings
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/ringcentral/apis.md
specificationVersion: "0.14"
apis:
- name: RingCentral Connect Platform API Explorer - Get Caller Blocking Settings
  x-api-slug: restapiv1-0accountaccountidextensionextensionidcallerblocking-get
  description: |-
    Returns the current call blocking settings of a user.
    App Permission
    ReadAccounts
    User Permission
    ReadBlockedNumbers
    Usage Plan Group
    Light
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidcallerblocking-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Update Caller Blocking Settings
  x-api-slug: restapiv1-0accountaccountidextensionextensionidcallerblocking-put
  description: "Updates the current call blocking settings of a user.\nApp Permission\nEditExtensions\nUser
    Permission\nEditBlockedNumbers\nUsage Plan Group\nLight\nError Codes\n\n \n  \n
    \  HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [greetings] value is invalid"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidcallerblocking-put-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Recording Settings
  x-api-slug: restapiv1-0accountaccountidcallrecording-get
  description: |-
    Returns call recording settings.
    App Permission
    ReadAccounts
    User Permission
    ReadCompanyInfo
    Usage Plan Group
    Light
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/ringcentral/restapiv1-0accountaccountidcallrecording-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Recording Extension Settings
  x-api-slug: restapiv1-0accountaccountidcallrecordingextensions-get
  description: |-
    Returns the list of extensions to be recorded.
    App Permission
    ReadAccounts
    User Permission
    ReadCompanyInfo
    Usage Plan Group
    Medium
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/ringcentral/restapiv1-0accountaccountidcallrecordingextensions-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Notification Settings
  x-api-slug: restapiv1-0accountaccountidextensionextensionidnotificationsettings-get
  description: "Returns notification settings for the current extension.\nApp Permission\nReadAccounts\nUser
    Permission\nReadMessagesNotificationsSettings\nUsage Plan Group\nLight\nError
    Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadAccounts] permission\n\n\n403\nCMN-408\nIn
    order to call this API endpoint, user needs to have [ReadMessagesNotificationsSettings]
    permission for requested resource."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidnotificationsettings-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Update Notification Settings
  x-api-slug: restapiv1-0accountaccountidextensionextensionidnotificationsettings-put
  description: "Updates notification settings for the current extension.\nApp Permission\nEditExtensions\nUser
    Permission\nEditMessagesNotificationsSettings\nUsage Plan Group\nMedium\nError
    Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n403\nCMN-109\nFeature
    VoicemailToText is unavailable\n\n\n403\nCMN-401\nIn order to call this API endpoint,
    application needs to have [EditExtensions] permission"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidnotificationsettings-put-openapi.md
- name: RingCentral Connect Platform API Explorer - Get User Conferencing Settings
  x-api-slug: restapiv1-0accountaccountidextensionextensionidconferencing-get
  description: "Returns the information on the Free Conference Calling (FCC) feature
    for a given extension.\nApp Permission\nReadAccounts\nUser Permission\nOrganizeConference\nUsage
    Plan Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n403\nCMN-112\nFeature [Conferencing] is not available for current
    extension type\n\n\n403\nCMN-408\nIn order to call this API endpoint, user needs
    to have [OrganizeConference] permission for requested resource.\n\n\n404\nCMN-102\nResource
    for parameter [accountId] is not found\n\n\n503\nFCC-103\nConference group is
    not set for current account"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidconferencing-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Update User Conferencing Settings
  x-api-slug: restapiv1-0accountaccountidextensionextensionidconferencing-put
  description: "Updates the default conferencing number for the current extension.
    The number can be selected from conferencing numbers of the current extension.
    Updates the setting, allowing participants join the conference before host.\nApp
    Permission\nEditExtensions\nUser Permission\nOrganizeConference\nUsage Plan Group\nMedium\nError
    Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [allowJoinBeforeHost, phoneNumbers] value is invalid\n\n\n403\nCMN-408\nIn order
    to call this API endpoint, user needs to have [OrganizeConference] permission
    for requested resource.\n\n\n404\nCMN-102\nResource for parameter [accountId]
    is not found\n\n\n503\nCMN-201\nService Temporary Unavailable"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidconferencing-put-openapi.md
x-common:
- type: x-blog
  url: https://medium.com/ringcentral-developers
- type: x-blog-rss
  url: https://medium.com/feed/ringcentral-developers
- type: x-github
  url: https://github.com/ringcentral
- type: x-openapi
  url: https://netstorage.ringcentral.com/dpw/api-explorer/swagger-ring_basic.yml?v=20180816
- type: x-website
  url: http://www.ringcentral.com
- type: x-api-gallery
  url: http://reverb.api.gallery.streamdata.io
- type: x-api-stack
  url: http://ringcentral.stack.network
- type: x-code
  url: https://developer.ringcentral.com/library/sdks.html
- type: x-crunchbase
  url: https://crunchbase.com/organization/ringcentral
- type: x-developer
  url: https://developer.ringcentral.com/
- type: x-documentation
  url: https://developer.ringcentral.com/api-explorer/latest/index.html?_ga=2.259782990.551967760.1534465156-1236351744.1533920460
- type: x-support
  url: https://developer.ringcentral.com/support.html
- type: x-twitter
  url: https://twitter.com/RingCentral
- type: x-website
  url: https://developer.ringcentral.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---