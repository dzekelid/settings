swagger: "2.0"
x-collection-name: Google Glass
x-complete: 1
info:
  title: Google Mirror
  description: interacts-with-glass-users-via-the-timeline-
  contact:
    name: Google
    url: https://google.com
  version: v1
host: www.googleapis.com
basePath: /mirror/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /settings/{id}:
    get:
      summary: Get Setting
      description: Gets a single setting by ID.
      operationId: mirror.settings.get
      x-api-path-slug: settingsid-get
      parameters:
      - in: path
        name: id
        description: The ID of the setting
      responses:
        200:
          description: OK
      tags:
      - Setting