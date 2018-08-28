---
swagger: "2.0"
x-collection-name: Facebook
x-complete: 0
info:
  title: Facebook Post Page Settings
  description: The page's post permission settings
  version: 1.0.0
host: graph.facebook.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{page}/settings:
    get:
      summary: Get Page Settings
      description: The page's post permission settings
      operationId: getPageSettings
      x-api-path-slug: pagesettings-get
      parameters:
      - in: path
        name: page
        description: Represents the ID of the page object
      responses:
        200:
          description: OK
      tags:
      - Page
      - Settings
    post:
      summary: Post Page Settings
      description: The page's post permission settings
      operationId: postPageSettings
      x-api-path-slug: pagesettings-post
      parameters:
      - in: path
        name: page
        description: Represents the ID of the page object
      - in: query
        name: setting
        description: 'Which single setting to update: USERS_CAN_POST, USERS_CAN_POST_PHOTOS,
          USERS_CAN_TAG_PHOTOS, USERS_CAN_POST_VIDEOS'
      - in: query
        name: value
        description: Connect to the social network with the Graph API
      responses:
        200:
          description: OK
      tags:
      - Page
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