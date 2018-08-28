swagger: "2.0"
x-collection-name: PayRun
x-complete: 1
info:
  title: Pay Run.IO
  description: open-scableable-transparent-payroll-api-
  version: 17.18.6.206
host: api.test.payrun.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Templates/hmrcsettings:
    get:
      summary: Gets the hmrc settings template
      description: Return the hmrc settings data object template
      operationId: GetHmrcSettingsTemplate
      x-api-path-slug: templateshmrcsettings-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Hmrc
      - Settings
      - Template