---
name: Eventbrite
x-slug: eventbrite
description: Eventbrite brings people together through live experiences. Discover
  events that match your passions, or create your own with online ticketing tools.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
x-kinRank: "9"
x-alexaRank: "643"
tags: Settings
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/eventbrite/apis.md
specificationVersion: "0.14"
apis:
- name: Eventbrite Get Checkout Settings Countries Currencies
  x-api-slug: eventbrite
  description: Get the countries and currencies which are supported by Eventbrite
    for ticket payment
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D///checkout_settings/countries_currencies/
  tags: Checkout,Settings,Countries,Currencies
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/eventbrite/checkout-settingscountries-currencies-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/eventbrite/checkout-settingscountries-currencies-get-openapi.md
- name: Eventbrite Get Checkout Settings Methods
  x-api-slug: eventbrite
  description: Get the available checkout methods to do payments given a country and
    a currency.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D///checkout_settings/methods/
  tags: Checkout,Settings,Methods
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/eventbrite/checkout-settingsmethods-get-openapi.md
- name: Eventbrite Get Checkout Settings
  x-api-slug: eventbrite
  description: Searches and returns a list of checkout_settings for the current user
    as the key checkout_settings.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D///checkout_settings/
  tags: Checkout,Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/eventbrite/checkout-settings-get-openapi.md
- name: Eventbrite Post Checkout Settings
  x-api-slug: eventbrite
  description: Creates a new checkout_settings object belonging to the current user.
    Two common settings are Eventbrite Payment Processing ( checkout_method = &#8220;eventbrite&#8221;
    ) and PayPal ( checkout_method = &#8220;paypal&#8221; ). In addition to the checkout_method
    you must provide the country and currency proceeds from the event should be paid
    to.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D///checkout_settings/
  tags: Checkout,Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/eventbrite/checkout-settings-post-openapi.md
- name: Eventbrite Get Checkout Settings Checkout Settings
  x-api-slug: eventbrite
  description: Get a specific checkout_settings object by ID
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D///checkout_settings/:checkout_settings_id/
  tags: Checkout,Settings,:checkout,Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/eventbrite/checkout-settingscheckout-settings-id-get-openapi.md
- name: Eventbrite Get Events Event Checkout Settings
  x-api-slug: eventbrite
  description: Gets and returns a list of checkout_settings associated with a given
    event by its event_id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D///events/:event_id/checkout_settings/
  tags: Events,:event,Checkout,Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/eventbrite/eventsevent-idcheckout-settings-get-openapi.md
- name: Eventbrite Post Events Event Checkout Settings
  x-api-slug: eventbrite
  description: Associate a single or set of checkout_settings with a given event by
    its event_id. This does not add more checkout settings to the event, but instead
    replaces all checkout settings for the event with the one(s) submitted. The JSON
    post body is a string list of the checkout_settings IDs you want to associate.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D///events/:event_id/checkout_settings/
  tags: Events,:event,Checkout,Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/eventbrite/eventsevent-idcheckout-settings-post-openapi.md
- name: Eventbrite Get Events Event Payout Settings
  x-api-slug: eventbrite
  description: Gets and returns the payout_settings (user instrument ID) associated
    with a given event by its event_id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D///events/:event_id/payout_settings/
  tags: Events,:event,Payout,Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/eventbrite/eventsevent-idpayout-settings-get-openapi.md
- name: Eventbrite Post Events Event Payout Settings
  x-api-slug: eventbrite
  description: Associate a payout user instrument ID with a given event, or clear
    the association by passing a null value for the user instrument ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D///events/:event_id/payout_settings/
  tags: Events,:event,Payout,Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/eventbrite/eventsevent-idpayout-settings-post-openapi.md
- name: Eventbrite Get Events Display Settings
  x-api-slug: eventbrite
  description: Retrieves the display settings for an event.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D///events/{id}/display_settings/
  tags: Events,Display,Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/eventbrite/eventsiddisplay-settings-get-openapi.md
- name: Eventbrite Post Events Display Settings
  x-api-slug: eventbrite
  description: Updates the display settings for an event.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D///events/{id}/display_settings/
  tags: Events,Display,Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/eventbrite/eventsiddisplay-settings-post-openapi.md
- name: Eventbrite Get Events Ticket Buyer Settings
  x-api-slug: eventbrite
  description: Returns a ticket_buyer_settings for an event.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D///events/{id}/ticket_buyer_settings/
  tags: Events,Ticket,Buyer,Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/eventbrite/eventsidticket-buyer-settings-get-openapi.md
- name: Eventbrite Post Events Ticket Buyer Settings
  x-api-slug: eventbrite
  description: Updates the ticket buyer settings for an event. Returns a ticket_buyer_settings.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D///events/{id}/ticket_buyer_settings/
  tags: Events,Ticket,Buyer,Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/eventbrite/eventsidticket-buyer-settings-post-openapi.md
- name: Eventbrite
  x-api-slug: eventbrite
  description: Eventbrite brings people together through live experiences. Discover
    events that match your passions, or create your own with online ticketing tools.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/193-eventbrite.jpg
  humanURL: http://eventbriteapi.com
  baseURL: https://www.eventbrite.com//%7Bdata-type%7D/
  tags: Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/eventbrite/openapi.md
x-common:
- type: x-apigee-console
  url: https://api.apigee.com/v1/consoles/eventbrite/apidescription?format=internal&ver=1351170233000
- type: x-authentication
  url: https://developer.eventbrite.com/docs/auth/
- type: x-base
  url: https://www.eventbriteapi.com/
- type: x-blog
  url: http://blog.eventbrite.com/
- type: x-blog-rss
  url: http://blog.eventbrite.com/feed/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/eventbrite
- type: x-crunchbase
  url: https://crunchbase.com/organization/eventbrite
- type: x-developer
  url: https://developer.eventbrite.com/
- type: x-github
  url: https://github.com/eventbrite
- type: x-pricing
  url: http://help.eventbrite.com/customer/en_us/portal/articles/428604
- type: x-privacy
  url: http://www.eventbrite.com/privacypolicy
- type: x-sdks-io
  url: https://sdks.io/SDK/View/eventbrite
- type: x-selfservice-registration
  url: https://www.eventbrite.com/signup/?referrer=%2F%3Fshow_onboarding%3D1&user_type=prebuyer&user_type_sig=AH_ElWGNJ_zHaAxwjzt5jiCRmvPvNBsy6w
- type: x-terms-of-service
  url: http://www.eventbrite.com/tos
- type: x-twitter
  url: https://twitter.com/EventbriteAPI
- type: x-twitter
  url: https://twitter.com/eventbrite
- type: x-website
  url: http://eventbriteapi.com
- type: x-website
  url: http://developer.eventbrite.com/
- type: x-website
  url: http://eventbrite.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---