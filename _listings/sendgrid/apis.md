---
name: SendGrid
description: SendGrid is a cloud-based email service that delivers email on behalf
  of companies to increase deliverability and improve customer communications integration
  with new or existing email systems is done via SMTP or through a REST API, providing
  metrics on outgoing email, and handles unsubscribe links, abiding by anti-spam regulations.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sendgrid-logo.png
x-kinRank: "9"
x-alexaRank: ""
tags:
- Stack Network
- Stack
- Plans
- Partners
- Messaging
- Messaging
- Imports
- Email
- Email
- API LIfeycle
created: "2018-03-24"
modified: "2018-03-24"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/apis.yaml
specificationVersion: "0.14"
apis:
- name: SendGrid
  description: SendGrid is a cloud-based email service that delivers email on behalf
    of companies to increase deliverability and improve customer communications integration
    with new or existing email systems is done via SMTP or through a REST API, providing
    metrics on outgoing email, and handles unsubscribe links, abiding by anti-spam
    regulations
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sendgrid-logo.png
  humanURL: ""
  baseURL: https://api.sendgrid.com//v3
  tags: Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/user-webhooks-parse-settings-hostname-patch.md
- name: SendGrid Get Mail Settings Forward Bounce
  description: "**This endpoint allows you to retrieve your current bounce forwarding
    mail settings.**\n\nActivating this setting allows you to specify an email address
    to which bounce reports are forwarded.\n\nMail settings allow you to tell SendGrid
    specific things to do to every email that you send to your recipients over SendGrid\u2019s
    [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html) or [SMTP
    Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html)."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sendgrid-logo.png
  humanURL: https://sendgrid.com/
  baseURL: https://api.sendgrid.com//v3
  tags: Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/mail-settings-forward-bounce-get.md
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/mail-settings-forward-bounce-get-postman.md
- name: SendGrid Patch Tracking Settings Open
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
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sendgrid-logo.png
  humanURL: https://sendgrid.com/
  baseURL: https://api.sendgrid.com//v3
  tags: Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/settings/master/_listings/sendgrid/tracking-settings-open-patch.md
x-common:
- type: x-net-library
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
- type: x-developer
  url: https://sendgrid.com/developers
- type: x-documentation
  url: https://sendgrid.com/docs/index.html
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
- type: x-nodejs-library
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
  url: https://sendgrid.com/
- type: x-net-library
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
- type: x-developer
  url: https://sendgrid.com/developers
- type: x-documentation
  url: https://sendgrid.com/docs/index.html
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
- type: x-nodejs-library
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
  url: https://sendgrid.com/
- type: x-net-library
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
- type: x-developer
  url: https://sendgrid.com/developers
- type: x-documentation
  url: https://sendgrid.com/docs/index.html
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
- type: x-nodejs-library
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
  url: https://sendgrid.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---