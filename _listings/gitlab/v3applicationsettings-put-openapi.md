---
swagger: "2.0"
x-collection-name: GitLab
x-complete: 0
info:
  title: GitLab Put Application Settings
  version: 1.0.0
  description: Modify application settings
host: localhost:3000
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v3/groups/{id}/notification_settings:
    get:
      summary: Get Groups Notification Settings
      description: This feature was introduced in GitLab 8.12
      operationId: getV3GroupsIdNotificationSettings
      x-api-path-slug: v3groupsidnotification-settings-get
      parameters:
      - in: path
        name: id
        description: The group ID or project ID or project NAMESPACE/PROJECT_NAME
      responses:
        200:
          description: OK
      tags:
      - Groups
      - Notification
      - Settings
    put:
      summary: Put Groups Notification Settings
      description: This feature was introduced in GitLab 8.12
      operationId: putV3GroupsIdNotificationSettings
      x-api-path-slug: v3groupsidnotification-settings-put
      parameters:
      - in: formData
        name: close_issue
        description: Enable/disable this notification
      - in: formData
        name: close_merge_request
        description: Enable/disable this notification
      - in: formData
        name: failed_pipeline
        description: Enable/disable this notification
      - in: path
        name: id
        description: The group ID or project ID or project NAMESPACE/PROJECT_NAME
      - in: formData
        name: level
        description: The group notification level
      - in: formData
        name: merge_merge_request
        description: Enable/disable this notification
      - in: formData
        name: new_issue
        description: Enable/disable this notification
      - in: formData
        name: new_merge_request
        description: Enable/disable this notification
      - in: formData
        name: new_note
        description: Enable/disable this notification
      - in: formData
        name: reassign_issue
        description: Enable/disable this notification
      - in: formData
        name: reassign_merge_request
        description: Enable/disable this notification
      - in: formData
        name: reopen_issue
        description: Enable/disable this notification
      - in: formData
        name: reopen_merge_request
        description: Enable/disable this notification
      - in: formData
        name: success_pipeline
        description: Enable/disable this notification
      responses:
        200:
          description: OK
      tags:
      - Groups
      - Notification
      - Settings
  /v3/projects/{id}/notification_settings:
    get:
      summary: Get Projects Notification Settings
      description: This feature was introduced in GitLab 8.12
      operationId: getV3ProjectsIdNotificationSettings
      x-api-path-slug: v3projectsidnotification-settings-get
      parameters:
      - in: path
        name: id
        description: The group ID or project ID or project NAMESPACE/PROJECT_NAME
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Notification
      - Settings
    put:
      summary: Put Projects Notification Settings
      description: This feature was introduced in GitLab 8.12
      operationId: putV3ProjectsIdNotificationSettings
      x-api-path-slug: v3projectsidnotification-settings-put
      parameters:
      - in: formData
        name: close_issue
        description: Enable/disable this notification
      - in: formData
        name: close_merge_request
        description: Enable/disable this notification
      - in: formData
        name: failed_pipeline
        description: Enable/disable this notification
      - in: path
        name: id
        description: The group ID or project ID or project NAMESPACE/PROJECT_NAME
      - in: formData
        name: level
        description: The project notification level
      - in: formData
        name: merge_merge_request
        description: Enable/disable this notification
      - in: formData
        name: new_issue
        description: Enable/disable this notification
      - in: formData
        name: new_merge_request
        description: Enable/disable this notification
      - in: formData
        name: new_note
        description: Enable/disable this notification
      - in: formData
        name: reassign_issue
        description: Enable/disable this notification
      - in: formData
        name: reassign_merge_request
        description: Enable/disable this notification
      - in: formData
        name: reopen_issue
        description: Enable/disable this notification
      - in: formData
        name: reopen_merge_request
        description: Enable/disable this notification
      - in: formData
        name: success_pipeline
        description: Enable/disable this notification
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Notification
      - Settings
  /v3/notification_settings:
    get:
      summary: Get Notification Settings
      description: This feature was introduced in GitLab 8.12
      operationId: getV3NotificationSettings
      x-api-path-slug: v3notification-settings-get
      responses:
        200:
          description: OK
      tags:
      - Notification
      - Settings
    put:
      summary: Put Notification Settings
      description: This feature was introduced in GitLab 8.12
      operationId: putV3NotificationSettings
      x-api-path-slug: v3notification-settings-put
      parameters:
      - in: formData
        name: close_issue
        description: Enable/disable this notification
      - in: formData
        name: close_merge_request
        description: Enable/disable this notification
      - in: formData
        name: failed_pipeline
        description: Enable/disable this notification
      - in: formData
        name: level
        description: The global notification level
      - in: formData
        name: merge_merge_request
        description: Enable/disable this notification
      - in: formData
        name: new_issue
        description: Enable/disable this notification
      - in: formData
        name: new_merge_request
        description: Enable/disable this notification
      - in: formData
        name: new_note
        description: Enable/disable this notification
      - in: formData
        name: notification_email
        description: The email address to send notifications
      - in: formData
        name: reassign_issue
        description: Enable/disable this notification
      - in: formData
        name: reassign_merge_request
        description: Enable/disable this notification
      - in: formData
        name: reopen_issue
        description: Enable/disable this notification
      - in: formData
        name: reopen_merge_request
        description: Enable/disable this notification
      - in: formData
        name: success_pipeline
        description: Enable/disable this notification
      responses:
        200:
          description: OK
      tags:
      - Notification
      - Settings
  /v3/application/settings:
    get:
      summary: Get Application Settings
      description: Get the current application settings
      operationId: getV3ApplicationSettings
      x-api-path-slug: v3applicationsettings-get
      responses:
        200:
          description: OK
      tags:
      - Application
      - Settings
    put:
      summary: Put Application Settings
      description: Modify application settings
      operationId: putV3ApplicationSettings
      x-api-path-slug: v3applicationsettings-put
      parameters:
      - in: formData
        name: admin_notification_email
        description: Abuse reports will be sent to this address if it is set
      - in: formData
        name: after_sign_out_path
        description: We will redirect users to this page after they sign out
      - in: formData
        name: after_sign_up_text
        description: Text shown after sign up
      - in: formData
        name: akismet_api_key
        description: Generate API key at http://www
      - in: formData
        name: akismet_enabled
        description: Helps prevent bots from creating issues
      - in: formData
        name: container_registry_token_expire_delay
        description: Authorization token duration (minutes)
      - in: formData
        name: default_branch_protection
        description: Determine if developers can push to master
      - in: formData
        name: default_group_visibility
        description: The default group visibility
      - in: formData
        name: default_projects_limit
        description: The maximum number of personal projects
      - in: formData
        name: default_project_visibility
        description: The default project visibility
      - in: formData
        name: default_snippet_visibility
        description: The default snippet visibility
      - in: formData
        name: disabled_oauth_sign_in_sources
        description: Disable certain OAuth sign-in sources
      - in: formData
        name: domain_blacklist
        description: Users with e-mail addresses that match these domain(s) will NOT
          be able to sign-up
      - in: formData
        name: domain_blacklist_enabled
        description: Enable domain blacklist for sign ups
      - in: formData
        name: domain_whitelist
        description: ONLY users with e-mail addresses that match these domain(s) will
          be able to sign-up
      - in: formData
        name: email_author_in_body
        description: Some email servers do not support overriding the email sender
          name
      - in: formData
        name: enabled_git_access_protocol
        description: Allow only the selected protocols to be used for Git access
      - in: formData
        name: gravatar_enabled
        description: Flag indicating if the Gravatar service is enabled
      - in: formData
        name: help_page_text
        description: Custom text displayed on the help page
      - in: formData
        name: home_page_url
        description: We will redirect non-logged in users to this page
      - in: formData
        name: housekeeping_bitmaps_enabled
        description: Creating pack file bitmaps makes housekeeping take a little longer
          but bitmaps should accelerate git clone performance
      - in: formData
        name: housekeeping_enabled
        description: Enable automatic repository housekeeping (git repack, git gc)
      - in: formData
        name: housekeeping_full_repack_period
        description: Number of Git pushes after which a full git repack is run
      - in: formData
        name: housekeeping_gc_period
        description: Number of Git pushes after which git gc is run
      - in: formData
        name: housekeeping_incremental_repack_period
        description: Number of Git pushes after which an incremental git repack is
          run
      - in: formData
        name: html_emails_enabled
        description: By default GitLab sends emails in HTML and plain text formats
          so mail clients can choose what format to use
      - in: formData
        name: import_sources
        description: Enabled sources for code import during project creation
      - in: formData
        name: koding_enabled
        description: Enable Koding
      - in: formData
        name: koding_url
        description: The Koding team URL
      - in: formData
        name: max_artifacts_size
        description: Set the maximum file size each builds artifacts can have
      - in: formData
        name: max_attachment_size
        description: Maximum attachment size in MB
      - in: formData
        name: metrics_enabled
        description: Enable the InfluxDB metrics
      - in: formData
        name: metrics_host
        description: The InfluxDB host
      - in: formData
        name: metrics_method_call_threshold
        description: A method call is only tracked when it takes longer to complete
          than the given amount of milliseconds
      - in: formData
        name: metrics_packet_size
        description: The amount of points to store in a single UDP packet
      - in: formData
        name: metrics_pool_size
        description: The amount of InfluxDB connections to open
      - in: formData
        name: metrics_port
        description: The UDP port to use for connecting to InfluxDB
      - in: formData
        name: metrics_sample_interval
        description: The sampling interval in seconds
      - in: formData
        name: metrics_timeout
        description: The amount of seconds after which an InfluxDB connection will
          time out
      - in: formData
        name: plantuml_enabled
        description: Enable PlantUML
      - in: formData
        name: plantuml_url
        description: The PlantUML server URL
      - in: formData
        name: recaptcha_enabled
        description: Helps prevent bots from creating accounts
      - in: formData
        name: recaptcha_private_key
        description: Generate private key at http://www
      - in: formData
        name: recaptcha_site_key
        description: Generate site key at http://www
      - in: formData
        name: repository_checks_enabled
        description: GitLab will periodically run git fsck in all project and wiki
          repositories to look for silent disk corruption issues
      - in: formData
        name: repository_storage
        description: Storage paths for new projects
      - in: formData
        name: require_two_factor_authentication
        description: Require all users to setup Two-factor authentication
      - in: formData
        name: restricted_visibility_levels
        description: Selected levels cannot be used by non-admin users for projects
          or snippets
      - in: formData
        name: send_user_confirmation_email
        description: Send confirmation email on sign-up
      - in: formData
        name: sentry_dsn
        description: Sentry Data Source Name
      - in: formData
        name: sentry_enabled
        description: 'Sentry is an error reporting and logging tool which is currently
          not shipped with GitLab, get it here: https://getsentry'
      - in: formData
        name: session_expire_delay
        description: Session duration in minutes
      - in: formData
        name: shared_runners_enabled
        description: Enable shared runners for new projects
      - in: formData
        name: shared_runners_text
        description: Shared runners text
      - in: formData
        name: sidekiq_throttling_enabled
        description: Enable Sidekiq Job Throttling
      - in: formData
        name: sidekiq_throttling_factor
        description: The factor by which the queues should be throttled
      - in: formData
        name: sidekiq_throttling_queus
        description: Choose which queues you wish to throttle
      - in: formData
        name: signin_enabled
        description: Flag indicating if sign in is enabled
      - in: formData
        name: signup_enabled
        description: Flag indicating if sign up is enabled
      - in: formData
        name: sign_in_text
        description: The sign in text of the GitLab application
      - in: formData
        name: two_factor_grace_period
        description: Amount of time (in hours) that users are allowed to skip forced
          configuration of two-factor authentication
      - in: formData
        name: user_default_external
        description: Newly registered users will by default be external
      - in: formData
        name: user_oauth_applications
        description: Allow users to register any application to use GitLab as an OAuth
          provider
      - in: formData
        name: version_check_enabled
        description: Let GitLab inform you when an update is available
      responses:
        200:
          description: OK
      tags:
      - Application
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