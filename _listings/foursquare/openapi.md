swagger: "2.0"
x-collection-name: Foursquare
x-complete: 1
info:
  title: Foursquare
  version: 1.0.0
host: api.foursquare.com
basePath: /v2/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /settings/all:
    get:
      summary: Get Settings All
      description: /settings/{SETTING_ID}
      operationId: settingssetting-id
      x-api-path-slug: settingsall-get
      parameters:
      - in: query
        name: v
        description: All requests now accept a v=YYYYMMDD param, which indicates that
          the client is up to date as of the specified date
      responses:
        200:
          description: OK
      tags:
      - Settings
  /settings/{SETTING_ID}:
    get:
      summary: Get Settings Setting
      description: /photos/add
      operationId: photosadd
      x-api-path-slug: settingssetting-id-get
      parameters:
      - in: query
        name: SETTING_ID
        description: The name of a setting
      - in: path
        name: SETTING_ID
      - in: query
        name: v
        description: All requests now accept a v=YYYYMMDD param, which indicates that
          the client is up to date as of the specified date
      responses:
        200:
          description: OK
      tags:
      - Settings
      - Setting
  /settings/{SETTING_ID}/set:
    post:
      summary: Post Settings Setting Set
      description: /settings/all
      operationId: settingsall
      x-api-path-slug: settingssetting-idset-post
      parameters:
      - in: query
        name: SETTING_ID
        description: Name of setting to change
      - in: path
        name: SETTING_ID
      - in: query
        name: v
        description: All requests now accept a v=YYYYMMDD param, which indicates that
          the client is up to date as of the specified date
      - in: query
        name: value
        description: 1 for true, and 0 for false
      responses:
        200:
          description: OK
      tags:
      - Settings
      - Setting
      - Set