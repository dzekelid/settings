---
swagger: "2.0"
x-collection-name: Spreaker
x-complete: 1
info:
  title: Spreaker API
  version: v1
host: api.spreaker.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /user/{user_id}/actions/facebook:
    get:
      summary: Facebook Settings
      description: Edit facebook share settings.
      operationId: getUserUserActionsFacebook
      x-api-path-slug: useruser-idactionsfacebook-get
      parameters:
      - in: query
        name: EPISODE_BROADCAST
        description: on to enable sharing when the user has published a new episode,
          off otherwise
      - in: query
        name: RADIO_FOLLOW
        description: on to enable sharing when the user starts following a radio,
          off otherwise
      - in: query
        name: RADIO_MESSAGE
        description: on to enable sharing when the user has sent a message to a radio,
          off otherwise
      - in: query
        name: SHOW_FOLLOW
        description: on to enable sharing when the user starts following a show, off
          otherwise
      - in: query
        name: SHOW_MESSAGE
        description: on to enable sharing when the user has sent a message to a show,
          off otherwise
      - in: query
        name: USER_FOLLOW
        description: on to enable sharing when the user starts following another user,
          off otherwise
      - in: path
        name: user_id
        description: The user id
      responses:
        200:
          description: OK
      tags:
      - Facebook
      - Settings
  /user/{user_id}/actions/twitter:
    put:
      summary: Twitter Settings
      description: Edit twitter share settings.
      operationId: putUserUserActionsTwitter
      x-api-path-slug: useruser-idactionstwitter-put
      parameters:
      - in: query
        name: EPISODE_BROADCAST
        description: on to enable sharing when the user has published a new episode,
          off otherwise
      - in: query
        name: RADIO_FOLLOW
        description: on to enable sharing when the user starts following a radio,
          off otherwise
      - in: query
        name: SHOW_FOLLOW
        description: on to enable sharing when the user starts following a show, off
          otherwise
      - in: query
        name: USER_FOLLOW
        description: on to enable sharing when the user starts following another user,
          off otherwise
      - in: path
        name: user_id
        description: The user id
      responses:
        200:
          description: OK
      tags:
      - Twitter
      - Settings
---