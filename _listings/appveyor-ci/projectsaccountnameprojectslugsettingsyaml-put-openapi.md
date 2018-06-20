---
swagger: "2.0"
x-collection-name: AppVeyor CI
x-complete: 0
info:
  title: App Veyor Put Projects Accountname Projectslug Settings Yaml
  description: Put projects accountname projectslug settings yaml.
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
    parameters:
      summary: Parameters Projects Accountname Projectslug Settings
      description: Parameters projects accountname projectslug settings.
      operationId: parametersProjectsAccountnameProjectslugSettings
      x-api-path-slug: projectsaccountnameprojectslugsettings-parameters
      responses:
        200:
          description: OK
      tags:
      - Projects
      - AccountName
      - ProjectSlug
      - Settings
  /projects/{accountName}/{projectSlug}/settings/build-number:
    parameters:
      summary: Parameters Projects Accountname Projectslug Settings Build Number
      description: Parameters projects accountname projectslug settings build number.
      operationId: parametersProjectsAccountnameProjectslugSettingsBuildNumber
      x-api-path-slug: projectsaccountnameprojectslugsettingsbuildnumber-parameters
      responses:
        200:
          description: OK
      tags:
      - Projects
      - AccountName
      - ProjectSlug
      - Settings
      - Build
      - Number
    put:
      summary: Put Projects Accountname Projectslug Settings Build Number
      description: Put projects accountname projectslug settings build number.
      operationId: putProjectsAccountnameProjectslugSettingsBuildNumber
      x-api-path-slug: projectsaccountnameprojectslugsettingsbuildnumber-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Projects
      - AccountName
      - ProjectSlug
      - Settings
      - Build
      - Number
  /projects/{accountName}/{projectSlug}/settings/environment-variables:
    get:
      summary: Get Projects Accountname Projectslug Settings Environment Variables
      description: Get projects accountname projectslug settings environment variables.
      operationId: getProjectsAccountnameProjectslugSettingsEnvironmentVariables
      x-api-path-slug: projectsaccountnameprojectslugsettingsenvironmentvariables-get
      responses:
        200:
          description: OK
      tags:
      - Projects
      - AccountName
      - ProjectSlug
      - Settings
      - Environment
      - Variables
    parameters:
      summary: Parameters Projects Accountname Projectslug Settings Environment Variables
      description: Parameters projects accountname projectslug settings environment
        variables.
      operationId: parametersProjectsAccountnameProjectslugSettingsEnvironmentVariables
      x-api-path-slug: projectsaccountnameprojectslugsettingsenvironmentvariables-parameters
      responses:
        200:
          description: OK
      tags:
      - Projects
      - AccountName
      - ProjectSlug
      - Settings
      - Environment
      - Variables
    put:
      summary: Put Projects Accountname Projectslug Settings Environment Variables
      description: Put projects accountname projectslug settings environment variables.
      operationId: putProjectsAccountnameProjectslugSettingsEnvironmentVariables
      x-api-path-slug: projectsaccountnameprojectslugsettingsenvironmentvariables-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Projects
      - AccountName
      - ProjectSlug
      - Settings
      - Environment
      - Variables
  /projects/{accountName}/{projectSlug}/settings/yaml:
    get:
      summary: Get Projects Accountname Projectslug Settings Yaml
      description: Get projects accountname projectslug settings yaml.
      operationId: getProjectsAccountnameProjectslugSettingsYaml
      x-api-path-slug: projectsaccountnameprojectslugsettingsyaml-get
      responses:
        200:
          description: OK
      tags:
      - Projects
      - AccountName
      - ProjectSlug
      - Settings
      - Yaml
    parameters:
      summary: Parameters Projects Accountname Projectslug Settings Yaml
      description: Parameters projects accountname projectslug settings yaml.
      operationId: parametersProjectsAccountnameProjectslugSettingsYaml
      x-api-path-slug: projectsaccountnameprojectslugsettingsyaml-parameters
      responses:
        200:
          description: OK
      tags:
      - Projects
      - AccountName
      - ProjectSlug
      - Settings
      - Yaml
    put:
      summary: Put Projects Accountname Projectslug Settings Yaml
      description: Put projects accountname projectslug settings yaml.
      operationId: putProjectsAccountnameProjectslugSettingsYaml
      x-api-path-slug: projectsaccountnameprojectslugsettingsyaml-put
      parameters:
      - in: body
        name: body
        description: The body of requests should contain YAML data
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Projects
      - AccountName
      - ProjectSlug
      - Settings
      - Yaml
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