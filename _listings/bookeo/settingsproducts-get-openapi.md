---
swagger: "2.0"
x-collection-name: Bookeo
x-complete: 0
info:
  title: Bookeo Get information about the products offered
  version: 1.0.0
  description: |-
    Get information about all the products (things that can be booked) offered.
     3 types of product are available:
     - fixed are products with a fixed schedule and a given number of seats. Ex a group tour, a class, a workshop
     - fixedCourse are fixed products that are defined as a course, i.e. comprise of a series of dates
     - flexibleTime are products that describe private appointments, i.e. when one booking uses one resource (teacher, consultant, etc)

     Although Bookeo applies a minimum amount of caching, it is recommended to cache these results for 10-15 minutes to improve the performance of your application, as product settings change rarely.
host: api.bookeo.com
basePath: /v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /settings/apikeyinfo:
    get:
      summary: Get information about your own API Key
      description: Get information about your own api key.
      operationId: getSettingsApikeyinfo
      x-api-path-slug: settingsapikeyinfo-get
      responses:
        200:
          description: OK
      tags:
      - Settings
      - Apikeyinfo
  /settings/business:
    get:
      summary: Get information, location and contact details about the business
      description: Get information, location and contact details about the business.
      operationId: getSettingsBusiness
      x-api-path-slug: settingsbusiness-get
      responses:
        200:
          description: OK
      tags:
      - Settings
      - Business
  /settings/languages:
    get:
      summary: Retrieve all supported languages
      description: Retrieve all supported languages.
      operationId: getSettingsLanguages
      x-api-path-slug: settingslanguages-get
      responses:
        200:
          description: OK
      tags:
      - Settings
      - Languages
  /settings/peoplecategories:
    get:
      summary: Retrieve all supported people categories
      description: |-
        Retrieve the people categories supported by this account.
         This can include the default ones ("Adults","Children","Infants") and also custom ones defined by the account ("Students", ...)
      operationId: getSettingsPeoplecategories
      x-api-path-slug: settingspeoplecategories-get
      responses:
        200:
          description: OK
      tags:
      - Settings
      - Peoplecategories
  /settings/products:
    get:
      summary: Get information about the products offered
      description: |-
        Get information about all the products (things that can be booked) offered.
         3 types of product are available:
         - fixed are products with a fixed schedule and a given number of seats. Ex a group tour, a class, a workshop
         - fixedCourse are fixed products that are defined as a course, i.e. comprise of a series of dates
         - flexibleTime are products that describe private appointments, i.e. when one booking uses one resource (teacher, consultant, etc)

         Although Bookeo applies a minimum amount of caching, it is recommended to cache these results for 10-15 minutes to improve the performance of your application, as product settings change rarely.
      operationId: getSettingsProducts
      x-api-path-slug: settingsproducts-get
      parameters:
      - in: query
        name: itemsPerPage
      - in: query
        name: pageNavigationToken
      - in: query
        name: pageNumber
      - in: query
        name: type
        description: if not specified, get all products
      responses:
        200:
          description: OK
      tags:
      - Settings
      - Products
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