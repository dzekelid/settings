---
swagger: "2.0"
x-collection-name: AppVeyor CI
x-complete: 0
info:
  title: App Veyor Get Projects Accountname Projectslug Settings
  description: Get projects accountname projectslug settings.
  termsOfService: https://www.appveyor.com/terms-of-service/
  contact:
    name: AppVeyor Team
    url: https://www.appveyor.com/about/
    email: team@appveyor.com
  version: 0.20170106.0
host: ci.appveyor.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /environments/{deploymentEnvironmentId}/settings:
    get:
      summary: Get Environments Deploymentenvironmentid Settings
      description: Get environments deploymentenvironmentid settings.
      operationId: getEnvironmentsDeploymentenvironmentSettings
      x-api-path-slug: environmentsdeploymentenvironmentidsettings-get
      responses:
        200:
          description: OK
      tags:
      - Environments
      - DeploymentEnvironmentId
      - Settings
    parameters:
      summary: Parameters Environments Deploymentenvironmentid Settings
      description: Parameters environments deploymentenvironmentid settings.
      operationId: parametersEnvironmentsDeploymentenvironmentSettings
      x-api-path-slug: environmentsdeploymentenvironmentidsettings-parameters
      responses:
        200:
          description: OK
      tags:
      - Environments
      - DeploymentEnvironmentId
      - Settings
  /projects/{accountName}/{projectSlug}/settings:
    get:
      summary: Get Projects Accountname Projectslug Settings
      description: Get projects accountname projectslug settings.
      operationId: getProjectsAccountnameProjectslugSettings
      x-api-path-slug: projectsaccountnameprojectslugsettings-get
      responses:
        200:
          description: OK
      tags:
      - Projects
      - AccountName
      - ProjectSlug
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