swagger: "2.0"
x-collection-name: Bookeo
x-complete: 1
info:
  title: Bookeo
  version: 1.0.0
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
  /settings/resources:
    get:
      summary: Retrieve all available resources
      description: Retrieve all available resources.
      operationId: getSettingsResources
      x-api-path-slug: settingsresources-get
      parameters:
      - in: query
        name: itemsPerPage
        description: 'maximum: 100'
      - in: query
        name: pageNavigationToken
      - in: query
        name: pageNumber
      responses:
        200:
          description: OK
      tags:
      - Settings
      - Resources
  /settings/taxes:
    get:
      summary: Retrieve all taxes used by this business
      description: Retrieve all taxes used by this business.
      operationId: getSettingsTaxes
      x-api-path-slug: settingstaxes-get
      responses:
        200:
          description: OK
      tags:
      - Settings
      - Taxes