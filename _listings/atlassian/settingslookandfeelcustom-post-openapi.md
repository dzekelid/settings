---
swagger: "2.0"
x-collection-name: Atlassian
x-complete: 0
info:
  title: Confluence Cloud API Update look and feel settings
  description: "Updates the look and feel settings for the site or for a single space.\nIf
    custom settings exist, they are updated. If no custom settings exist, \nthen a
    set of custom settings is created.\n\nNote, if a theme is selected for a space,
    the space look and feel settings \nare provided by the theme and cannot be overridden.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \n'Admin' permission for the space."
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
  /settings/lookandfeel/custom:
    post:
      summary: Update look and feel settings
      description: "Updates the look and feel settings for the site or for a single
        space.\nIf custom settings exist, they are updated. If no custom settings
        exist, \nthen a set of custom settings is created.\n\nNote, if a theme is
        selected for a space, the space look and feel settings \nare provided by the
        theme and cannot be overridden.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
        required**: \n'Admin' permission for the space."
      operationId: com.atlassian.confluence.plugins.restapi.resources.LookAndFeelResource.updateLookAndFeelSettings_pos
      x-api-path-slug: settingslookandfeelcustom-post
      parameters:
      - in: query
        name: spaceKey
        description: The key of the space for which the look and feel settings will
          beupdated
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