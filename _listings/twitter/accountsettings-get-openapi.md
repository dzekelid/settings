---
swagger: "2.0"
x-collection-name: Twitter
x-complete: 0
info:
  title: Twitter Get Account Settings
  description: returns settings for user
  version: "1.1"
host: api.twitter.com
basePath: /1.1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /account/settings:
    get:
      summary: Get Account Settings
      description: returns settings for user
      operationId: returns-settings-for-user
      x-api-path-slug: accountsettings-get
      responses:
        200:
          description: OK
      tags:
      - Social
      - Account
    post:
      summary: Update  Account Settings
      description: updates user's settings
      operationId: updates-users-settings
      x-api-path-slug: accountsettings-post
      parameters:
      - in: query
        name: end_sleep_time
        description: the hour that sleep time should end if enabled
      - in: query
        name: lang
        description: language which Twitter should render in for the user
      - in: query
        name: sleep_time_enabled
        description: enables/disables sleep time, silencing notifications
      - in: query
        name: start_sleep_time
        description: the hour that sleep time should begin if enabled
      - in: query
        name: time_zone
        description: timezone dates and times should be displayed in
      - in: query
        name: trend_location_woeid
        description: the Yahoo! Where On Earth ID to user as defaul tend location
      responses:
        200:
          description: OK
      tags:
      - Social
      - Account
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