---
swagger: "2.0"
x-collection-name: Atlassian
x-complete: 0
info:
  title: Confluence Cloud API Get look and feel settings
  description: "Returns the look and feel settings for the site or a single space.
    This \nincludes attributes such as the color scheme, padding, and border radius.\n\nThe
    look and feel settings for a space can be inherited from the global \nlook and
    feel settings or provided by a theme.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \nNone"
  termsOfService: http://atlassian.com/terms/
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /settings/lookandfeel:
    get:
      summary: Get look and feel settings
      description: "Returns the look and feel settings for the site or a single space.
        This \nincludes attributes such as the color scheme, padding, and border radius.\n\nThe
        look and feel settings for a space can be inherited from the global \nlook
        and feel settings or provided by a theme.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
        required**: \nNone"
      operationId: com.atlassian.confluence.plugins.restapi.resources.LookAndFeelResource.getLookAndFeelSettings_get
      x-api-path-slug: settingslookandfeel-get
      parameters:
      - in: query
        name: spaceKey
        description: The key of the space for which the look and feel settings will
          bereturned
      responses:
        200:
          description: OK
      tags:
      - Look
      - Feel
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