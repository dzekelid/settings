---
name: AppVeyor CI
x-slug: appveyor-ci
description: We provide continuous integration tools for Windows developers. The service
  is offered for free to open-source projects, we offer subscriptions for private
  projects and AppVeyor Enterprise installations on customer premises.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
x-kinRank: "7"
x-alexaRank: "35479"
tags: Settings
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/appveyor-ci/apis.md
specificationVersion: "0.14"
apis:
- name: App Veyor Get Environments Deploymentenvironmentid Settings
  x-api-slug: app-veyor
  description: Get environments deploymentenvironmentid settings.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//environments/{deploymentEnvironmentId}/settings
  tags: Environments,DeploymentEnvironmentId,Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/appveyor-ci/environmentsdeploymentenvironmentidsettings-get-openapi.md
- name: App Veyor Parameters Environments Deploymentenvironmentid Settings
  x-api-slug: app-veyor
  description: Parameters environments deploymentenvironmentid settings.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//environments/{deploymentEnvironmentId}/settings
  tags: Environments,DeploymentEnvironmentId,Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/appveyor-ci/environmentsdeploymentenvironmentidsettings-parameters-openapi.md
- name: App Veyor Get Projects Accountname Projectslug Settings
  x-api-slug: app-veyor
  description: Get projects accountname projectslug settings.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}/settings
  tags: Projects,AccountName,ProjectSlug,Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/appveyor-ci/projectsaccountnameprojectslugsettings-get-openapi.md
- name: App Veyor Parameters Projects Accountname Projectslug Settings
  x-api-slug: app-veyor
  description: Parameters projects accountname projectslug settings.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}/settings
  tags: Projects,AccountName,ProjectSlug,Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/appveyor-ci/projectsaccountnameprojectslugsettings-parameters-openapi.md
- name: App Veyor Parameters Projects Accountname Projectslug Settings Build Number
  x-api-slug: app-veyor
  description: Parameters projects accountname projectslug settings build number.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}/settings/build-number
  tags: Projects,AccountName,ProjectSlug,Settings,Build,Number
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/appveyor-ci/projectsaccountnameprojectslugsettingsbuildnumber-parameters-openapi.md
- name: App Veyor Put Projects Accountname Projectslug Settings Build Number
  x-api-slug: app-veyor
  description: Put projects accountname projectslug settings build number.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}/settings/build-number
  tags: Projects,AccountName,ProjectSlug,Settings,Build,Number
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/appveyor-ci/projectsaccountnameprojectslugsettingsbuildnumber-put-openapi.md
- name: App Veyor Get Projects Accountname Projectslug Settings Environment Variables
  x-api-slug: app-veyor
  description: Get projects accountname projectslug settings environment variables.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}/settings/environment-variables
  tags: Projects,AccountName,ProjectSlug,Settings,Environment,Variables
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/appveyor-ci/projectsaccountnameprojectslugsettingsenvironmentvariables-get-openapi.md
- name: App Veyor Parameters Projects Accountname Projectslug Settings Environment
    Variables
  x-api-slug: app-veyor
  description: Parameters projects accountname projectslug settings environment variables.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}/settings/environment-variables
  tags: Projects,AccountName,ProjectSlug,Settings,Environment,Variables
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/appveyor-ci/projectsaccountnameprojectslugsettingsenvironmentvariables-parameters-openapi.md
- name: App Veyor Put Projects Accountname Projectslug Settings Environment Variables
  x-api-slug: app-veyor
  description: Put projects accountname projectslug settings environment variables.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}/settings/environment-variables
  tags: Projects,AccountName,ProjectSlug,Settings,Environment,Variables
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/appveyor-ci/projectsaccountnameprojectslugsettingsenvironmentvariables-put-openapi.md
- name: App Veyor Get Projects Accountname Projectslug Settings Yaml
  x-api-slug: app-veyor
  description: Get projects accountname projectslug settings yaml.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}/settings/yaml
  tags: Projects,AccountName,ProjectSlug,Settings,Yaml
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/appveyor-ci/projectsaccountnameprojectslugsettingsyaml-get-openapi.md
- name: App Veyor Parameters Projects Accountname Projectslug Settings Yaml
  x-api-slug: app-veyor
  description: Parameters projects accountname projectslug settings yaml.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}/settings/yaml
  tags: Projects,AccountName,ProjectSlug,Settings,Yaml
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/appveyor-ci/projectsaccountnameprojectslugsettingsyaml-parameters-openapi.md
- name: App Veyor Put Projects Accountname Projectslug Settings Yaml
  x-api-slug: app-veyor
  description: Put projects accountname projectslug settings yaml.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}/settings/yaml
  tags: Projects,AccountName,ProjectSlug,Settings,Yaml
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/appveyor-ci/projectsaccountnameprojectslugsettingsyaml-put-openapi.md
- name: App Veyor
  x-api-slug: app-veyor
  description: We provide continuous integration tools for Windows developers. The
    service is offered for free to open-source projects, we offer subscriptions for
    private projects and AppVeyor Enterprise installations on customer premises.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api
  tags: Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/appveyor-ci/openapi.md
x-common:
- type: x-crunchbase
  url: https://crunchbase.com/organization/appveyor-systems-inc
- type: x-documentation
  url: https://www.appveyor.com/docs/
- type: x-email
  url: jobs@appveyor.com
- type: x-email
  url: team@appveyor.com
- type: x-email
  url: privacy@appveyor.com
- type: x-twitter
  url: https://twitter.com/appveyor
- type: x-website
  url: http://appveyor.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---