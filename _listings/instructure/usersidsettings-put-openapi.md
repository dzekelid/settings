---
swagger: "2.0"
x-collection-name: Instructure
x-complete: 0
info:
  title: Instructure Canvas Users API Update user settings.
  description: Update user settings..
  termsOfService: https://www.canvaslms.com/policies/api-policy
  version: v1
host: canvas.instructure.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /courses/{course_id}/settings:
    get:
      summary: Get course settings
      description: Get course settings.
      operationId: get-course-settings
      x-api-path-slug: coursescourse-idsettings-get
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Settings
    put:
      summary: Update course settings
      description: Update course settings.
      operationId: update-course-settings
      x-api-path-slug: coursescourse-idsettings-put
      parameters:
      - in: query
        name: allow_student_discussion_editing
        description: Let students edit or delete their own discussion posts
      - in: query
        name: allow_student_discussion_topics
        description: Let students create discussion topics
      - in: query
        name: allow_student_forum_attachments
        description: Let students attach files to discussions
      - in: query
        name: allow_student_organized_groups
        description: Let students organize their own groups
      - in: query
        name: hide_distribution_graphs
        description: Hide grade distribution graphs from students
      - in: query
        name: hide_final_grades
        description: Hide totals in student grades summary
      - in: query
        name: lock_all_announcements
        description: Disable comments on announcements
      - in: query
        name: restrict_student_future_view
        description: Restrict students from viewing courses before start date
      - in: query
        name: restrict_student_past_view
        description: Restrict students from viewing courses after end date
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Settings
  /users/{id}/settings:
    get:
      summary: Update user settings.
      description: Update user settings..
      operationId: update-user-settings
      x-api-path-slug: usersidsettings-get
      parameters:
      - in: query
        name: manual_mark_as_read
        description: If true, require user to manually mark discussion posts as read
          (don&#39;tnauto-mark as read)
      responses:
        200:
          description: OK
      tags:
      - Users
      - Id
      - Settings
    put:
      summary: Update user settings.
      description: Update user settings..
      operationId: update-user-settings
      x-api-path-slug: usersidsettings-put
      parameters:
      - in: query
        name: manual_mark_as_read
        description: If true, require user to manually mark discussion posts as read
          (don&#39;tnauto-mark as read)
      responses:
        200:
          description: OK
      tags:
      - Users
      - Id
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