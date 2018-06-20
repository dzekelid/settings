---
name: SendGrid
x-slug: sendgrid
description: Delivering your transactional and marketing emails through the worlds
  largest cloud-based email delivery platform. Send with confidence.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
x-kinRank: "9"
x-alexaRank: "9582"
tags: Settings
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/apis.md
specificationVersion: "0.14"
apis:
- name: SendGrid Get Access Settings Activity
  x-api-slug: sendgrid
  description: |-
    **This endpoint allows you to retrieve a list of all of the IP addresses that recently attempted to access your account either through the User Interface or the API.**

    IP Access Management allows you to control which IP addresses can be used to access your account, either through the User Interface or the API. There is no limit to the number of IP addresses that you can add to your whitelist. It is possible to remove your own IP address from the whitelist, thus preventing yourself from accessing your account.

    For more information, please see our [User Guide](http://sendgrid.com/docs/User_Guide/Settings/ip_access_management.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//access_settings/activity
  tags: Email,Access, Settings, Activity
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/access-settingsactivity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/access-settingsactivity-get-openapi.md
- name: SendGrid Delete Access Settings Whitelist
  x-api-slug: sendgrid
  description: |-
    **This endpoint allows you to remove one or more IPs from your IP whitelist.**

    You can remove one IP at a time, or you can remove multiple IP addresses.

    IP Access Management allows you to control which IP addresses can be used to access your account, either through the User Interface or the API. There is no limit to the number of IP addresses that you can add to your whitelist. It is possible to remove your own IP address from the whitelist, thus preventing yourself from accessing your account.

    For more information, please see our [User Guide](http://sendgrid.com/docs/User_Guide/Settings/ip_access_management.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//access_settings/whitelist
  tags: Email,Access, Settings, Whitelist
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/access-settingswhitelist-delete-openapi.md
- name: SendGrid Get Access Settings Whitelist
  x-api-slug: sendgrid
  description: |-
    **This endpoint allows you to retrieve a list of IP addresses that are currently whitelisted.**

    IP Access Management allows you to control which IP addresses can be used to access your account, either through the User Interface or the API. There is no limit to the number of IP addresses that you can add to your whitelist. It is possible to remove your own IP address from the whitelist, thus preventing yourself from accessing your account.

    For more information, please see our [User Guide](http://sendgrid.com/docs/User_Guide/Settings/ip_access_management.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//access_settings/whitelist
  tags: Email,Access, Settings, Whitelist
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/access-settingswhitelist-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/access-settingswhitelist-get-openapi.md
- name: SendGrid Add Access Settings Whitelist
  x-api-slug: sendgrid
  description: |-
    **This endpoint allows you to add one or more IP addresses to your IP whitelist.**

    When adding an IP to your whitelist, include the IP address in an array. You can whitelist one IP at a time, or you can whitelist multiple IPs at once.

    IP Access Management allows you to control which IP addresses can be used to access your account, either through the User Interface or the API. There is no limit to the number of IP addresses that you can add to your whitelist. It is possible to remove your own IP address from the whitelist, thus preventing yourself from accessing your account.

    For more information, please see our [User Guide](http://sendgrid.com/docs/User_Guide/Settings/ip_access_management.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//access_settings/whitelist
  tags: Email,Access, Settings, Whitelist
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/access-settingswhitelist-post-openapi.md
- name: SendGrid Delete Access Settings Whitelist Rule
  x-api-slug: sendgrid
  description: |-
    **This endpoint allows you to remove a specific IP address from your IP whitelist.**

    When removing a specific IP address from your whitelist, you must include the ID in your call.

    IP Access Management allows you to control which IP addresses can be used to access your account, either through the User Interface or the API. There is no limit to the number of IP addresses that you can add to your whitelist. It is possible to remove your own IP address from the whitelist, thus preventing yourself from accessing your account.

    For more information, please see our [User Guide](http://sendgrid.com/docs/User_Guide/Settings/ip_access_management.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//access_settings/whitelist/{rule_id}
  tags: Email,Access, Settings, Whitelist, Rule
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/access-settingswhitelistrule-id-delete-openapi.md
- name: SendGrid Get Access Settings Whitelist Rule
  x-api-slug: sendgrid
  description: |-
    **This endpoint allows you to retreive a specific IP address that has been whitelisted.**

    You must include the ID for the specific IP address you want to retrieve in your call.

    IP Access Management allows you to control which IP addresses can be used to access your account, either through the User Interface or the API. There is no limit to the number of IP addresses that you can add to your whitelist. It is possible to remove your own IP address from the whitelist, thus preventing yourself from accessing your account.

    For more information, please see our [User Guide](http://sendgrid.com/docs/User_Guide/Settings/ip_access_management.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//access_settings/whitelist/{rule_id}
  tags: Email,Access, Settings, Whitelist, Rule
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/access-settingswhitelistrule-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/access-settingswhitelistrule-id-get-openapi.md
- name: SendGrid Get Mail Settings
  x-api-slug: sendgrid
  description: "**This endpoint allows you to retrieve a list of all mail settings.**\n\nMail
    settings allow you to tell SendGrid specific things to do to every email that
    you send to your recipients over SendGrid\u2019s [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html)
    or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//mail_settings
  tags: Email,Mail, Settings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/mail-settings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/mail-settings-get-openapi.md
- name: SendGrid Get Mail Settings Address Whitelist
  x-api-slug: sendgrid
  description: "**This endpoint allows you to retrieve your current email address
    whitelist settings.**\n\nThe address whitelist setting whitelists a specified
    email address or domain for which mail should never be suppressed. For example,
    you own the domain \u201Cexample.com,\u201D and one or more of your recipients
    use email@example.com addresses, by placing example.com in the address whitelist
    setting, all bounces, blocks, and unsubscribes logged for that domain will be
    ignored and sent as if under normal sending conditions.\n\nMail settings allow
    you to tell SendGrid specific things to do to every email that you send to your
    recipients over SendGrid\u2019s [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html)
    or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//mail_settings/address_whitelist
  tags: Email,Mail, Settings, Address, Whitelist
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/mail-settingsaddress-whitelist-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/mail-settingsaddress-whitelist-get-openapi.md
- name: SendGrid Patch Mail Settings Address Whitelist
  x-api-slug: sendgrid
  description: "**This endpoint allows you to update your current email address whitelist
    settings.**\n\nThe address whitelist setting whitelists a specified email address
    or domain for which mail should never be suppressed. For example, you own the
    domain \u201Cexample.com,\u201D and one or more of your recipients use email@example.com
    addresses, by placing example.com in the address whitelist setting, all bounces,
    blocks, and unsubscribes logged for that domain will be ignored and sent as if
    under normal sending conditions.\n\nMail settings allow you to tell SendGrid specific
    things to do to every email that you send to your recipients over SendGrid\u2019s
    [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html) or [SMTP
    Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//mail_settings/address_whitelist
  tags: Email,Mail, Settings, Address, Whitelist
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/mail-settingsaddress-whitelist-patch-openapi.md
- name: SendGrid Get Mail Settings Bcc
  x-api-slug: sendgrid
  description: "**This endpoint allows you to retrieve your current BCC mail settings.**\n\nWhen
    the BCC mail setting is enabled, SendGrid will automatically send a blind carbon
    copy (BCC) to an address for every email sent without adding that address to the
    header. Please note that only one email address may be entered in this field,
    if you wish to distribute BCCs to multiple addresses you will need to create a
    distribution group or use forwarding rules.\n\nMail settings allow you to tell
    SendGrid specific things to do to every email that you send to your recipients
    over SendGrid\u2019s [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html)
    or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//mail_settings/bcc
  tags: Email,Mail, Settings, Bcc
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/mail-settingsbcc-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/mail-settingsbcc-get-openapi.md
- name: SendGrid Patch Mail Settings Bcc
  x-api-slug: sendgrid
  description: "**This endpoint allows you to update your current BCC mail settings.**\n\nWhen
    the BCC mail setting is enabled, SendGrid will automatically send a blind carbon
    copy (BCC) to an address for every email sent without adding that address to the
    header. Please note that only one email address may be entered in this field,
    if you wish to distribute BCCs to multiple addresses you will need to create a
    distribution group or use forwarding rules.\n\nMail settings allow you to tell
    SendGrid specific things to do to every email that you send to your recipients
    over SendGrid\u2019s [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html)
    or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//mail_settings/bcc
  tags: Email,Mail, Settings, Bcc
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/mail-settingsbcc-patch-openapi.md
- name: SendGrid Get Mail Settings Bounce Purge
  x-api-slug: sendgrid
  description: "**This endpoint allows you to retrieve your current bounce purge settings.**\n\nThis
    setting allows you to set a schedule for SendGrid to automatically delete contacts
    from your soft and hard bounce suppression lists.\n\nMail settings allow you to
    tell SendGrid specific things to do to every email that you send to your recipients
    over SendGrid\u2019s [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html)
    or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//mail_settings/bounce_purge
  tags: Email,Mail, Settings, Bounce, Purge
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/mail-settingsbounce-purge-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/mail-settingsbounce-purge-get-openapi.md
- name: SendGrid Patch Mail Settings Bounce Purge
  x-api-slug: sendgrid
  description: "**This endpoint allows you to update your current bounce purge settings.**\n\nThis
    setting allows you to set a schedule for SendGrid to automatically delete contacts
    from your soft and hard bounce suppression lists.\n\nMail settings allow you to
    tell SendGrid specific things to do to every email that you send to your recipients
    over SendGrid\u2019s [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html)
    or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//mail_settings/bounce_purge
  tags: Email,Mail, Settings, Bounce, Purge
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/mail-settingsbounce-purge-patch-openapi.md
- name: SendGrid Get Mail Settings Footer
  x-api-slug: sendgrid
  description: "**This endpoint allows you to retrieve your current Footer mail settings.**\n\nThe
    footer setting will insert a custom footer at the bottom of the text and HTML
    bodies. Use the embedded HTML editor and plain text entry fields to create the
    content of the footers to be inserted into your emails.\n\nMail settings allow
    you to tell SendGrid specific things to do to every email that you send to your
    recipients over SendGrid\u2019s [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html)
    or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//mail_settings/footer
  tags: Email,Mail, Settings, Footer
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/mail-settingsfooter-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/mail-settingsfooter-get-openapi.md
- name: SendGrid Patch Mail Settings Footer
  x-api-slug: sendgrid
  description: "**This endpoint allows you to update your current Footer mail settings.**\n\nThe
    footer setting will insert a custom footer at the bottom of the text and HTML
    bodies. Use the embedded HTML editor and plain text entry fields to create the
    content of the footers to be inserted into your emails.\n\nMail settings allow
    you to tell SendGrid specific things to do to every email that you send to your
    recipients over SendGrid\u2019s [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html)
    or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//mail_settings/footer
  tags: Email,Mail, Settings, Footer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/mail-settingsfooter-patch-openapi.md
- name: SendGrid Get Mail Settings Forward Bounce
  x-api-slug: sendgrid
  description: "**This endpoint allows you to retrieve your current bounce forwarding
    mail settings.**\n\nActivating this setting allows you to specify an email address
    to which bounce reports are forwarded.\n\nMail settings allow you to tell SendGrid
    specific things to do to every email that you send to your recipients over SendGrid\u2019s
    [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html) or [SMTP
    Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//mail_settings/forward_bounce
  tags: Email,Mail, Settings, Forward, Bounce
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/mail-settingsforward-bounce-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/mail-settingsforward-bounce-get-openapi.md
- name: SendGrid Patch Mail Settings Forward Bounce
  x-api-slug: sendgrid
  description: "**This endpoint allows you to update your current bounce forwarding
    mail settings.**\n\nActivating this setting allows you to specify an email address
    to which bounce reports are forwarded.\n\nMail settings allow you to tell SendGrid
    specific things to do to every email that you send to your recipients over SendGrid\u2019s
    [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html) or [SMTP
    Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//mail_settings/forward_bounce
  tags: Email,Mail, Settings, Forward, Bounce
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/mail-settingsforward-bounce-patch-openapi.md
- name: SendGrid Get Mail Settings Forward Spam
  x-api-slug: sendgrid
  description: "**This endpoint allows you to retrieve your current Forward Spam mail
    settings.**\n\nEnabling the forward spam setting allows you to specify an email
    address to which spam reports will be forwarded.\n\nMail settings allow you to
    tell SendGrid specific things to do to every email that you send to your recipients
    over SendGrid\u2019s [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html)
    or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//mail_settings/forward_spam
  tags: Email,Mail, Settings, Forward, Spam
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/mail-settingsforward-spam-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/mail-settingsforward-spam-get-openapi.md
- name: SendGrid Patch Mail Settings Forward Spam
  x-api-slug: sendgrid
  description: "**This endpoint allows you to update your current Forward Spam mail
    settings.**\n\nEnabling the forward spam setting allows you to specify an email
    address to which spam reports will be forwarded.\n\nMail settings allow you to
    tell SendGrid specific things to do to every email that you send to your recipients
    over SendGrid\u2019s [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html)
    or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//mail_settings/forward_spam
  tags: Email,Mail, Settings, Forward, Spam
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/mail-settingsforward-spam-patch-openapi.md
- name: SendGrid Get Mail Settings Plain Content
  x-api-slug: sendgrid
  description: "**This endpoint allows you to retrieve your current Plain Content
    mail settings.**\n\nThe plain content setting will automatically convert any plain
    text emails that you send to HTML before sending.\n\nMail settings allow you to
    tell SendGrid specific things to do to every email that you send to your recipients
    over SendGrid\u2019s [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html)
    or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//mail_settings/plain_content
  tags: Email,Mail, Settings, Plain, Content
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/mail-settingsplain-content-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/mail-settingsplain-content-get-openapi.md
- name: SendGrid Patch Mail Settings Plain Content
  x-api-slug: sendgrid
  description: "**This endpoint allows you to update your current Plain Content mail
    settings.**\n\nThe plain content setting will automatically convert any plain
    text emails that you send to HTML before sending.\n\nMail settings allow you to
    tell SendGrid specific things to do to every email that you send to your recipients
    over SendGrid\u2019s [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html)
    or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//mail_settings/plain_content
  tags: Email,Mail, Settings, Plain, Content
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/mail-settingsplain-content-patch-openapi.md
- name: SendGrid Get Mail Settings Spam Check
  x-api-slug: sendgrid
  description: "**This endpoint allows you to retrieve your current Spam Checker mail
    settings.**\n\nThe spam checker filter notifies you when emails are detected that
    exceed a predefined spam threshold.\n\nMail settings allow you to tell SendGrid
    specific things to do to every email that you send to your recipients over SendGrid\u2019s
    [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html) or [SMTP
    Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//mail_settings/spam_check
  tags: Email,Mail, Settings, Spam, Check
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/mail-settingsspam-check-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/mail-settingsspam-check-get-openapi.md
- name: SendGrid Patch Mail Settings Spam Check
  x-api-slug: sendgrid
  description: "**This endpoint allows you to update your current spam checker mail
    settings.**\n\nThe spam checker filter notifies you when emails are detected that
    exceed a predefined spam threshold.\n\nMail settings allow you to tell SendGrid
    specific things to do to every email that you send to your recipients over SendGrid\u2019s
    [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html) or [SMTP
    Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//mail_settings/spam_check
  tags: Email,Mail, Settings, Spam, Check
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/mail-settingsspam-check-patch-openapi.md
- name: SendGrid Get Mail Settings Template
  x-api-slug: sendgrid
  description: "**This endpoint allows you to retrieve your current legacy email template
    settings.**\n\nThis setting refers to our original email templates. We currently
    support more fully featured [transactional templates](https://sendgrid.com/docs/User_Guide/Transactional_Templates/index.html).
    \n\nThe legacy email template setting wraps an HTML template around your email
    content. This can be useful for sending out marketing email and/or other HTML
    formatted messages.\n\nMail settings allow you to tell SendGrid specific things
    to do to every email that you send to your recipients over SendGrid\u2019s [Web
    API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html) or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//mail_settings/template
  tags: Email,Mail, Settings, Template
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/mail-settingstemplate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/mail-settingstemplate-get-openapi.md
- name: SendGrid Patch Mail Settings Template
  x-api-slug: sendgrid
  description: "**This endpoint allows you to update your current legacy email template
    settings.**\n\nThis setting refers to our original email templates. We currently
    support more fully featured [transactional templates](https://sendgrid.com/docs/User_Guide/Transactional_Templates/index.html).
    \n\nThe legacy email template setting wraps an HTML template around your email
    content. This can be useful for sending out marketing email and/or other HTML
    formatted messages.\n\nMail settings allow you to tell SendGrid specific things
    to do to every email that you send to your recipients over SendGrid\u2019s [Web
    API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html) or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//mail_settings/template
  tags: Email,Mail, Settings, Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/mail-settingstemplate-patch-openapi.md
- name: SendGrid Get Partner Settings
  x-api-slug: sendgrid
  description: |-
    **This endpoint allows you to retrieve a list of all partner settings that you can enable.**

    Our partner settings allow you to integrate your SendGrid account with our partners to increase your SendGrid experience and functionality. For more information about our partners, and how you can begin integrating with them, please visit our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/partners.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//partner_settings
  tags: Email,Partner, Settings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/partner-settings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/partner-settings-get-openapi.md
- name: SendGrid Get Partner Settings New Relic
  x-api-slug: sendgrid
  description: |-
    **This endpoint allows you to retrieve your current New Relic partner settings.**

    Our partner settings allow you to integrate your SendGrid account with our partners to increase your SendGrid experience and functionality. For more information about our partners, and how you can begin integrating with them, please visit our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/partners.html).

    By integrating with New Relic, you can send your SendGrid email statistics to your New Relic Dashboard. If you enable this setting, your stats will be sent to New Relic every 5 minutes. You will need your New Relic License Key to enable this setting. For more information, please see our [Classroom](https://sendgrid.com/docs/Classroom/Track/Collecting_Data/new_relic.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//partner_settings/new_relic
  tags: Email,Partner, Settings, New, Relic
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/partner-settingsnew-relic-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/partner-settingsnew-relic-get-openapi.md
- name: SendGrid Patch Partner Settings New Relic
  x-api-slug: sendgrid
  description: |-
    **This endpoint allows you to update or change your New Relic partner settings.**

    Our partner settings allow you to integrate your SendGrid account with our partners to increase your SendGrid experience and functionality. For more information about our partners, and how you can begin integrating with them, please visit our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/partners.html).

    By integrating with New Relic, you can send your SendGrid email statistics to your New Relic Dashboard. If you enable this setting, your stats will be sent to New Relic every 5 minutes. You will need your New Relic License Key to enable this setting. For more information, please see our [Classroom](https://sendgrid.com/docs/Classroom/Track/Collecting_Data/new_relic.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//partner_settings/new_relic
  tags: Email,Partner, Settings, New, Relic
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/partner-settingsnew-relic-patch-openapi.md
- name: SendGrid Get Tracking Settings
  x-api-slug: sendgrid
  description: |-
    **This endpoint allows you to retrieve a list of all tracking settings that you can enable on your account.**

    You can track a variety of the actions your recipients may take when interacting with your emails including opening your emails, clicking on links in your emails, and subscribing to (or unsubscribing from) your emails.

    For more information about tracking, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/tracking.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//tracking_settings
  tags: Email,Tracking, Settings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/tracking-settings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/tracking-settings-get-openapi.md
- name: SendGrid Get Tracking Settings Click
  x-api-slug: sendgrid
  description: |-
    **This endpoint allows you to retrieve your current click tracking setting.**

    You can track a variety of the actions your recipients may take when interacting with your emails including opening your emails, clicking on links in your emails, and subscribing to (or unsubscribing from) your emails.

    For more information about tracking, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/tracking.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//tracking_settings/click
  tags: Email,Tracking, Settings, Click
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/tracking-settingsclick-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/tracking-settingsclick-get-openapi.md
- name: SendGrid Patch Tracking Settings Click
  x-api-slug: sendgrid
  description: |-
    **This endpoint allows you to change your current click tracking setting. You can enable, or disable, click tracking using this endpoint.**

    You can track a variety of the actions your recipients may take when interacting with your emails including opening your emails, clicking on links in your emails, and subscribing to (or unsubscribing from) your emails.

    For more information about tracking, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/tracking.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//tracking_settings/click
  tags: Email,Tracking, Settings, Click
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/tracking-settingsclick-patch-openapi.md
- name: SendGrid Get Tracking Settings Google Analytics
  x-api-slug: sendgrid
  description: "**This endpoint allows you to retrieve your current setting for Google
    Analytics.**\n\nFor more information about using Google Analytics, please refer
    to [Google\u2019s URL Builder](https://support.google.com/analytics/answer/1033867?hl=en)
    and their article on [\"Best Practices for Campaign Building\"](https://support.google.com/analytics/answer/1037445).\n\nWe
    default the settings to Google\u2019s recommendations. For more information, see
    [Google Analytics Demystified](https://sendgrid.com/docs/Classroom/Track/Collecting_Data/google_analytics_demystified_ga_statistics_vs_sg_statistics.html).\n\nYou
    can track a variety of the actions your recipients may take when interacting with
    your emails including opening your emails, clicking on links in your emails, and
    subscribing to (or unsubscribing from) your emails.\n\nFor more information about
    tracking, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/tracking.html)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//tracking_settings/google_analytics
  tags: Email,Tracking, Settings, Google, Analytics
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/tracking-settingsgoogle-analytics-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/tracking-settingsgoogle-analytics-get-openapi.md
- name: SendGrid Patch Tracking Settings Google Analytics
  x-api-slug: sendgrid
  description: "**This endpoint allows you to update your current setting for Google
    Analytics.**\n\nFor more information about using Google Analytics, please refer
    to [Google\u2019s URL Builder](https://support.google.com/analytics/answer/1033867?hl=en)
    and their article on [\"Best Practices for Campaign Building\"](https://support.google.com/analytics/answer/1037445).\n\nWe
    default the settings to Google\u2019s recommendations. For more information, see
    [Google Analytics Demystified](https://sendgrid.com/docs/Classroom/Track/Collecting_Data/google_analytics_demystified_ga_statistics_vs_sg_statistics.html).\n\nYou
    can track a variety of the actions your recipients may take when interacting with
    your emails including opening your emails, clicking on links in your emails, and
    subscribing to (or unsubscribing from) your emails.\n\nFor more information about
    tracking, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/tracking.html)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//tracking_settings/google_analytics
  tags: Email,Tracking, Settings, Google, Analytics
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/tracking-settingsgoogle-analytics-patch-openapi.md
- name: SendGrid Get Tracking Settings Open
  x-api-slug: sendgrid
  description: "**This endpoint allows you to retrieve your current settings for open
    tracking.**\n\nOpen Tracking adds an invisible image at the end of the email which
    can track email opens. If the email recipient has images enabled on their email
    client, a request to SendGrid\u2019s server for the invisible image is executed
    and an open event is logged. These events are logged in the Statistics portal,
    Email Activity interface, and are reported by the Event Webhook.\n\nYou can track
    a variety of the actions your recipients may take when interacting with your emails
    including opening your emails, clicking on links in your emails, and subscribing
    to (or unsubscribing from) your emails.\n\nFor more information about tracking,
    please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/tracking.html)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//tracking_settings/open
  tags: Email,Tracking, Settings, Open
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/tracking-settingsopen-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/tracking-settingsopen-get-openapi.md
- name: SendGrid Patch Tracking Settings Open
  x-api-slug: sendgrid
  description: "**This endpoint allows you to update your current settings for open
    tracking.**\n\nOpen Tracking adds an invisible image at the end of the email which
    can track email opens. If the email recipient has images enabled on their email
    client, a request to SendGrid\u2019s server for the invisible image is executed
    and an open event is logged. These events are logged in the Statistics portal,
    Email Activity interface, and are reported by the Event Webhook.\n\nYou can track
    a variety of the actions your recipients may take when interacting with your emails
    including opening your emails, clicking on links in your emails, and subscribing
    to (or unsubscribing from) your emails.\n\nFor more information about tracking,
    please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/tracking.html)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//tracking_settings/open
  tags: Email,Tracking, Settings, Open
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/tracking-settingsopen-patch-openapi.md
- name: SendGrid Get Tracking Settings Subscription
  x-api-slug: sendgrid
  description: |-
    **This endpoint allows you to retrieve your current settings for subscription tracking.**

    Subscription tracking adds links to the bottom of your emails that allows your recipients to subscribe to, or unsubscribe from, your emails.

    You can track a variety of the actions your recipients may take when interacting with your emails including opening your emails, clicking on links in your emails, and subscribing to (or unsubscribing from) your emails.

    For more information about tracking, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/tracking.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//tracking_settings/subscription
  tags: Email,Tracking, Settings, Subscription
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/tracking-settingssubscription-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/tracking-settingssubscription-get-openapi.md
- name: SendGrid Patch Tracking Settings Subscription
  x-api-slug: sendgrid
  description: |-
    **This endpoint allows you to update your current settings for subscription tracking.**

    Subscription tracking adds links to the bottom of your emails that allows your recipients to subscribe to, or unsubscribe from, your emails.

    You can track a variety of the actions your recipients may take when interacting with your emails including opening your emails, clicking on links in your emails, and subscribing to (or unsubscribing from) your emails.

    For more information about tracking, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/tracking.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//tracking_settings/subscription
  tags: Email,Tracking, Settings, Subscription
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/tracking-settingssubscription-patch-openapi.md
- name: SendGrid Get User Settings Enforced Tls
  x-api-slug: sendgrid
  description: "**This endpoint allows you to retrieve your current Enforced TLS settings.**\n\nThe
    Enforced TLS settings specify whether or not the recipient is required to support
    TLS or have a valid certificate. See the [SMTP Ports User Guide](https://sendgrid.com/docs/Classroom/Basics/Email_Infrastructure/smtp_ports.html)
    for more information on opportunistic TLS.\n\n**Note:** If either setting is enabled
    and the recipient does not support TLS or have a valid certificate, we drop the
    message and send a block event with \u201CTLS required but not supported\u201D
    as the description."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//user/settings/enforced_tls
  tags: Email,User, Settings, Enforced, Tls
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/usersettingsenforced-tls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/usersettingsenforced-tls-get-openapi.md
- name: SendGrid Patch User Settings Enforced Tls
  x-api-slug: sendgrid
  description: "**This endpoint allows you to update your current Enforced TLS settings.**\n\nThe
    Enforced TLS settings specify whether or not the recipient is required to support
    TLS or have a valid certificate. See the [SMTP Ports User Guide](https://sendgrid.com/docs/Classroom/Basics/Email_Infrastructure/smtp_ports.html)
    for more information on opportunistic TLS.\n\n**Note:** If either setting is enabled
    and the recipient does not support TLS or have a valid certificate, we drop the
    message and send a block event with \u201CTLS required but not supported\u201D
    as the description."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//user/settings/enforced_tls
  tags: Email,User, Settings, Enforced, Tls
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/usersettingsenforced-tls-patch-openapi.md
- name: SendGrid Get User Webhooks Event Settings
  x-api-slug: sendgrid
  description: "**This endpoint allows you to retrieve your current event webhook
    settings.**\n\nIf an event type is marked as `true`, then the event webhook will
    include information about that event.\n\nSendGrid\u2019s Event Webhook will notify
    a URL of your choice via HTTP POST with information about events that occur as
    SendGrid processes your email.\n\nCommon uses of this data are to remove unsubscribes,
    react to spam reports, determine unengaged recipients, identify bounced email
    addresses, or create advanced analytics of your email program."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//user/webhooks/event/settings
  tags: Email,User, Webhooks, Event, Settings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/userwebhookseventsettings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/userwebhookseventsettings-get-openapi.md
- name: SendGrid Patch User Webhooks Event Settings
  x-api-slug: sendgrid
  description: "**This endpoint allows you to update your current event webhook settings.**\n\nIf
    an event type is marked as `true`, then the event webhook will include information
    about that event.\n\nSendGrid\u2019s Event Webhook will notify a URL of your choice
    via HTTP POST with information about events that occur as SendGrid processes your
    email.\n\nCommon uses of this data are to remove unsubscribes, react to spam reports,
    determine unengaged recipients, identify bounced email addresses, or create advanced
    analytics of your email program."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//user/webhooks/event/settings
  tags: Email,User, Webhooks, Event, Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/userwebhookseventsettings-patch-openapi.md
- name: SendGrid Get User Webhooks Parse Settings
  x-api-slug: sendgrid
  description: |-
    **This endpoint allows you to retrieve all of your current inbound parse settings.**

    The inbound parse webhook allows you to have incoming emails parsed, extracting some or all of the contnet, and then have that content POSTed by SendGrid to a URL of your choosing. For more information, please see our [User Guide](https://sendgrid.com/docs/API_Reference/Webhooks/parse.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//user/webhooks/parse/settings
  tags: Email,User, Webhooks, Parse, Settings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/userwebhooksparsesettings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/userwebhooksparsesettings-get-openapi.md
- name: SendGrid Add User Webhooks Parse Settings
  x-api-slug: sendgrid
  description: |-
    **This endpoint allows you to create a new inbound parse setting.**

    The inbound parse webhook allows you to have incoming emails parsed, extracting some or all of the content, and then have that content POSTed by SendGrid to a URL of your choosing. For more information, please see our [User Guide](https://sendgrid.com/docs/API_Reference/Webhooks/parse.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//user/webhooks/parse/settings
  tags: Email,User, Webhooks, Parse, Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/userwebhooksparsesettings-post-openapi.md
- name: SendGrid Delete User Webhooks Parse Settings Hostname
  x-api-slug: sendgrid
  description: |-
    **This endpoint allows you to delete a specific inbound parse setting.**

    The inbound parse webhook allows you to have incoming emails parsed, extracting some or all of the contnet, and then have that content POSTed by SendGrid to a URL of your choosing. For more information, please see our [User Guide](https://sendgrid.com/docs/API_Reference/Webhooks/parse.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//user/webhooks/parse/settings/{hostname}
  tags: Email,User, Webhooks, Parse, Settings, Hostname
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/userwebhooksparsesettingshostname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/userwebhooksparsesettingshostname-delete-openapi.md
- name: SendGrid Get User Webhooks Parse Settings Hostname
  x-api-slug: sendgrid
  description: |-
    **This endpoint allows you to retrieve a specific inbound parse setting.**

    The inbound parse webhook allows you to have incoming emails parsed, extracting some or all of the contnet, and then have that content POSTed by SendGrid to a URL of your choosing. For more information, please see our [User Guide](https://sendgrid.com/docs/API_Reference/Webhooks/parse.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//user/webhooks/parse/settings/{hostname}
  tags: Email,User, Webhooks, Parse, Settings, Hostname
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/userwebhooksparsesettingshostname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/userwebhooksparsesettingshostname-get-openapi.md
- name: SendGrid Patch User Webhooks Parse Settings Hostname
  x-api-slug: sendgrid
  description: |-
    **This endpoint allows you to update a specific inbound parse setting.**

    The inbound parse webhook allows you to have incoming emails parsed, extracting some or all of the contnet, and then have that content POSTed by SendGrid to a URL of your choosing. For more information, please see our [User Guide](https://sendgrid.com/docs/API_Reference/Webhooks/parse.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//user/webhooks/parse/settings/{hostname}
  tags: Email,User, Webhooks, Parse, Settings, Hostname
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/userwebhooksparsesettingshostname-patch-openapi.md
- name: SendGrid
  x-api-slug: sendgrid
  description: SendGrids cloud-based email infrastructure relieves businesses of the
    cost and complexity of maintaining custom email systems. SendGrid provides reliable
    delivery, scalability and real-time analytics along with flexible APIs that make
    custom integration a breeze.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/openapi.md
x-common:
- type: x--net-library
  url: https://sendgrid.com/docs/Code_Examples/csharp.html
- type: x-base
  url: https://api.sendgrid.com
- type: x-blog
  url: http://blog.sendgrid.com/
- type: x-blog-rss
  url: http://feeds.feedburner.com/sendgrid/CDXr
- type: x-contact-form
  url: https://sendgrid.com/contact
- type: x-crunchbase
  url: http://www.crunchbase.com/company/sendgrid
- type: x-crunchbase
  url: https://crunchbase.com/organization/sendgrid
- type: x-developer
  url: https://sendgrid.com/developers
- type: x-documentation
  url: https://sendgrid.com/docs/index.html
- type: x-email
  url: privacy@sendgrid.com
- type: x-email
  url: legal@sendgrid.com
- type: x-email
  url: dpo@sendgrid.com
- type: x-forum
  url: http://support.sendgrid.com/forums
- type: x-github
  url: https://github.com/sendgrid
- type: x-go-library
  url: https://sendgrid.com/docs/Code_Examples/go.html
- type: x-ios-library
  url: https://sendgrid.com/docs/Code_Examples/ios.html
- type: x-java-library
  url: https://sendgrid.com/docs/Code_Examples/java.html
- type: x-labs
  url: http://labs.sendgrid.com/
- type: x-node-js-library
  url: https://sendgrid.com/docs/Code_Examples/nodejs.html
- type: x-partners
  url: https://sendgrid.com/partners
- type: x-perl-library
  url: https://sendgrid.com/docs/Code_Examples/perl.html
- type: x-php-library
  url: https://sendgrid.com/docs/Code_Examples/php.html
- type: x-pricing
  url: https://sendgrid.com/transactional-email/pricing
- type: x-privacy
  url: https://sendgrid.com/privacy
- type: x-python-library
  url: https://sendgrid.com/docs/Code_Examples/python.html
- type: x-ruby-library
  url: https://sendgrid.com/docs/Code_Examples/ruby.html
- type: x-security
  url: https://sendgrid.com/security
- type: x-selfservice-registration
  url: https://sendgrid.com/user/signup
- type: x-terms-of-service
  url: https://sendgrid.com/tos
- type: x-twitter
  url: https://twitter.com/SendGrid
- type: x-website
  url: http://sendgrid.com
- type: x-website
  url: https://sendgrid.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---