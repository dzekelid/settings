---
swagger: "2.0"
x-collection-name: Reddit
x-complete: 1
info:
  title: Reddit
  description: the-reddit-api-allows-you-to-access-the-user-submitted-and-rated-stories-on-reddit-com--it-also-provides-advanced-functionality-including-user-account-information-and-subreddit-moderation-
  version: 1.0.0
host: www.reddit.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  '{/r/subreddit}/wiki/settings/page':
    get&nbsp;:
      summary: Get Subreddit Wiki Settings Page
      description: Retrieve the current permission settings for page
      operationId: get&nbsp;RSubredditWikiSettingsPage
      x-api-path-slug: rsubredditwikisettingspage-getnbsp
      parameters:
      - in: query
        name: page
        description: the name of an existing wiki page
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subreddit
      - Wiki
      - Settings
      - Page
    post&nbsp;:
      summary: Add Subreddit Wiki Settings Page
      description: Update the permissions and visibility of wiki page
      operationId: post&nbsp;RSubredditWikiSettingsPage
      x-api-path-slug: rsubredditwikisettingspage-postnbsp
      parameters:
      - in: query
        name: /r/subreddit
        description: subreddit
        type: string
        format: string
      - in: query
        name: listed
        description: boolean value
        type: string
      - in: query
        name: page
        description: the name of an existing wiki page
        type: string
      - in: query
        name: permlevel
        description: an integer
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subreddit
      - Wiki
      - Settings
      - Page
---