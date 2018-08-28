swagger: "2.0"
x-collection-name: AWS Cognito
x-complete: 1
info:
  title: AWS Cognito Merged API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AdminSetUserSettings:
    get:
      summary: Admin Set User Settings
      description: Sets all the user settings for a specified user name.
      operationId: adminSetUserSettings
      x-api-path-slug: actionadminsetusersettings-get
      parameters:
      - in: query
        name: MFAOptions
        description: Specifies the options for MFA (e
        type: string
      - in: query
        name: Username
        description: The user name of the user for whom you wish to set user settings
        type: string
      - in: query
        name: UserPoolId
        description: The user pool ID for the user pool where you want to set the
          users settings, such            as MFA options
        type: string
      responses:
        200:
          description: OK
      tags:
      - Users
  /?Action=SetUserSettings:
    get:
      summary: Set User Settings
      description: Sets the user settings like multi-factor authentication (MFA).
      operationId: setUserSettings
      x-api-path-slug: actionsetusersettings-get
      parameters:
      - in: query
        name: AccessToken
        description: The access token for the set user settings request
        type: string
      - in: query
        name: MFAOptions
        description: Specifies the options for MFA (e
        type: string
      responses:
        200:
          description: OK
      tags:
      - Users