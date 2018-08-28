---
swagger: "2.0"
x-collection-name: AWS Elastic Beanstalk
x-complete: 0
info:
  title: AWS Elastic Beanstalk API Validate Configuration Settings
  version: 1.0.0
  description: |-
    Takes a set of configuration settings and either a configuration template or
          environment, and determines whether those values are valid.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeConfigurationSettings:
    get:
      summary: Describe Configuration Settings
      description: |-
        Returns a description of the settings for the specified configuration set, that is,
              either a configuration template or the configuration set associated with a running
              environment.
      operationId: describeConfigurationSettings
      x-api-path-slug: actiondescribeconfigurationsettings-get
      parameters:
      - in: query
        name: ApplicationName
        description: The application for the environment or configuration template
        type: string
      - in: query
        name: EnvironmentName
        description: The name of the environment to describe
        type: string
      - in: query
        name: TemplateName
        description: The name of the configuration template to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configuration Settings
  /?Action=ValidateConfigurationSettings:
    get:
      summary: Validate Configuration Settings
      description: |-
        Takes a set of configuration settings and either a configuration template or
              environment, and determines whether those values are valid.
      operationId: validateConfigurationSettings
      x-api-path-slug: actionvalidateconfigurationsettings-get
      parameters:
      - in: query
        name: ApplicationName
        description: The name of the application that the configuration template or
          environment belongs      to
        type: string
      - in: query
        name: EnvironmentName
        description: The name of the environment to validate the settings against
        type: string
      - in: query
        name: OptionSettings.member.N
        description: A list of the options and desired values to evaluate
        type: string
      - in: query
        name: TemplateName
        description: The name of the configuration template to validate the settings
          against
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configuration Settings
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