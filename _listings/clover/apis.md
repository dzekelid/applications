---
name: Clover
x-slug: clover
description: Clover, a First Data company, builds the largest open-architecture point
  of sale solution aimed at small &amp; medium sized business owners. Our products
  are changing the consumer/merchant experience for the better, opening avenues for
  seamless customer-merchant interactions. There are five versions of Clover, including
  the Clover Station, Clover Mobile, Clover Mini, Clover Go, and Clover Flex. With
  Clover, First Data is aiming to create the largest open architecture operating system
  for commerce-enabling solutions and applications for business owners.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
x-kinRank: "7"
x-alexaRank: "23096"
tags: Applications
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/clover/apis.md
specificationVersion: "0.14"
apis:
- name: ' - Create a notification for an app'
  x-api-slug: v3appsaidmerchantsmidnotifications-post
  description: 'Push a message to all merchant devices that have your app installed
    and are listening for notifications.  For details on how to use Clover''s Android
    SDK to receive notifications see: https://github.com/clover/android-examples/tree/master/pushnotificationexample'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/clover/v3appsaidmerchantsmidnotifications-post-openapi.md
- name: ' - Create a notification for a device'
  x-api-slug: v3appsaiddevicesdidnotifications-post
  description: 'Push a message to a device that has your app installed and is listening
    for notifications.  For details on how to use Clover''s Android SDK to receive
    notifications see: https://github.com/clover/android-examples/tree/master/pushnotificationexample'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/clover/v3appsaiddevicesdidnotifications-post-openapi.md
- name: ' - Get merchant''s billing information for an app'
  x-api-slug: v3appsaidmerchantsmidbilling-info-get
  description: Gives detailed information about the status of the merchant's billing
    for the app including current subscription tier and trial status. Requires an
    OAuth generated token.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/clover/v3appsaidmerchantsmidbilling-info-get-openapi.md
- name: ' - Create an app billing metered event'
  x-api-slug: v3appsaidmerchantsmidmeteredsmeteredid-post
  description: This creates an app billing metered event. The amount Clover will charge
    the specified merchant is based on the cost specified for this metered object
    in the Developer Dashboard. The merchant will be billed during their next scheduled
    billing cycle. Passing "count" as a query parameter will bill the merchant for
    that number of metered events. "count" must be passed as a query parameter in
    order to function properly ??? if passed in the request body, it will be ignored.
    If not specified, "count" will default to 1. See https://docs.clover.com/launch/billing/
    for more information. Requires an OAuth generated token.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/clover/v3appsaidmerchantsmidmeteredsmeteredid-post-openapi.md
- name: ' - Get the app metered billing events for an app metered, e.g. all the billing
    events for the event ''reservation'''
  x-api-slug: v3appsaidmerchantsmidmeteredsmeteredid-get
  description: Get the app metered billing events for an app metered, e.g. all the
    billing events for the event 'reservation'.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/clover/v3appsaidmerchantsmidmeteredsmeteredid-get-openapi.md
- name: ' - Get an app billing metered event'
  x-api-slug: v3appsaidmerchantsmidmeteredsmeteredideventseventid-get
  description: This enables you to fetch the details on a merchants app billing metered
    event. Requires an OAuth generated token.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/clover/v3appsaidmerchantsmidmeteredsmeteredideventseventid-get-openapi.md
- name: ' - Delete an app billing metered event, if not charged.'
  x-api-slug: v3appsaidmerchantsmidmeteredsmeteredideventseventid-delete
  description: This deletes an app billing metered event, if the event has not been
    charged yet. See https://docs.clover.com/launch/billing/ for more information.
    Requires an OAuth generated token.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/clover/v3appsaidmerchantsmidmeteredsmeteredideventseventid-delete-openapi.md
- name: ' - Create a notification for an app'
  x-api-slug: v3appsaidmerchantsmidnotifications-post
  description: 'Push a message to all merchant devices that have your app installed
    and are listening for notifications.  For details on how to use Clover''s Android
    SDK to receive notifications see: https://github.com/clover/android-examples/tree/master/pushnotificationexample'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/clover/v3appsaidmerchantsmidnotifications-post-openapi.md
- name: ' - Create a notification for a device'
  x-api-slug: v3appsaiddevicesdidnotifications-post
  description: 'Push a message to a device that has your app installed and is listening
    for notifications.  For details on how to use Clover''s Android SDK to receive
    notifications see: https://github.com/clover/android-examples/tree/master/pushnotificationexample'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/clover/v3appsaiddevicesdidnotifications-post-openapi.md
- name: ' - Get merchant''s billing information for an app'
  x-api-slug: v3appsaidmerchantsmidbilling-info-get
  description: Gives detailed information about the status of the merchant's billing
    for the app including current subscription tier and trial status. Requires an
    OAuth generated token.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/clover/v3appsaidmerchantsmidbilling-info-get-openapi.md
- name: ' - Create an app billing metered event'
  x-api-slug: v3appsaidmerchantsmidmeteredsmeteredid-post
  description: This creates an app billing metered event. The amount Clover will charge
    the specified merchant is based on the cost specified for this metered object
    in the Developer Dashboard. The merchant will be billed during their next scheduled
    billing cycle. Passing "count" as a query parameter will bill the merchant for
    that number of metered events. "count" must be passed as a query parameter in
    order to function properly ??? if passed in the request body, it will be ignored.
    If not specified, "count" will default to 1. See https://docs.clover.com/launch/billing/
    for more information. Requires an OAuth generated token.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/clover/v3appsaidmerchantsmidmeteredsmeteredid-post-openapi.md
- name: ' - Get the app metered billing events for an app metered, e.g. all the billing
    events for the event ''reservation'''
  x-api-slug: v3appsaidmerchantsmidmeteredsmeteredid-get
  description: Get the app metered billing events for an app metered, e.g. all the
    billing events for the event 'reservation'.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/clover/v3appsaidmerchantsmidmeteredsmeteredid-get-openapi.md
- name: ' - Get an app billing metered event'
  x-api-slug: v3appsaidmerchantsmidmeteredsmeteredideventseventid-get
  description: This enables you to fetch the details on a merchants app billing metered
    event. Requires an OAuth generated token.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/clover/v3appsaidmerchantsmidmeteredsmeteredideventseventid-get-openapi.md
- name: ' - Delete an app billing metered event, if not charged.'
  x-api-slug: v3appsaidmerchantsmidmeteredsmeteredideventseventid-delete
  description: This deletes an app billing metered event, if the event has not been
    charged yet. See https://docs.clover.com/launch/billing/ for more information.
    Requires an OAuth generated token.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/clover/v3appsaidmerchantsmidmeteredsmeteredideventseventid-delete-openapi.md
- name: ' - Delete an app billing metered event, if not charged.'
  x-api-slug: v3appsaidmerchantsmidmeteredsmeteredideventseventid-delete
  description: This deletes an app billing metered event, if the event has not been
    charged yet. See https://docs.clover.com/launch/billing/ for more information.
    Requires an OAuth generated token.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/clover/v3appsaidmerchantsmidmeteredsmeteredideventseventid-delete-openapi.md
- name: ' - Get an app billing metered event'
  x-api-slug: v3appsaidmerchantsmidmeteredsmeteredideventseventid-get
  description: This enables you to fetch the details on a merchants app billing metered
    event. Requires an OAuth generated token.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/clover/v3appsaidmerchantsmidmeteredsmeteredideventseventid-get-openapi.md
- name: ' - Get the app metered billing events for an app metered, e.g. all the billing
    events for the event ''reservation'''
  x-api-slug: v3appsaidmerchantsmidmeteredsmeteredid-get
  description: Get the app metered billing events for an app metered, e.g. all the
    billing events for the event 'reservation'.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/clover/v3appsaidmerchantsmidmeteredsmeteredid-get-openapi.md
- name: ' - Create an app billing metered event'
  x-api-slug: v3appsaidmerchantsmidmeteredsmeteredid-post
  description: This creates an app billing metered event. The amount Clover will charge
    the specified merchant is based on the cost specified for this metered object
    in the Developer Dashboard. The merchant will be billed during their next scheduled
    billing cycle. Passing "count" as a query parameter will bill the merchant for
    that number of metered events. "count" must be passed as a query parameter in
    order to function properly ??? if passed in the request body, it will be ignored.
    If not specified, "count" will default to 1. See https://docs.clover.com/launch/billing/
    for more information. Requires an OAuth generated token.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/clover/v3appsaidmerchantsmidmeteredsmeteredid-post-openapi.md
- name: ' - Get merchant''s billing information for an app'
  x-api-slug: v3appsaidmerchantsmidbilling-info-get
  description: Gives detailed information about the status of the merchant's billing
    for the app including current subscription tier and trial status. Requires an
    OAuth generated token.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/clover/v3appsaidmerchantsmidbilling-info-get-openapi.md
- name: ' - Create a notification for a device'
  x-api-slug: v3appsaiddevicesdidnotifications-post
  description: 'Push a message to a device that has your app installed and is listening
    for notifications.  For details on how to use Clover''s Android SDK to receive
    notifications see: https://github.com/clover/android-examples/tree/master/pushnotificationexample'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/clover/v3appsaiddevicesdidnotifications-post-openapi.md
- name: ' - Create a notification for an app'
  x-api-slug: v3appsaidmerchantsmidnotifications-post
  description: 'Push a message to all merchant devices that have your app installed
    and are listening for notifications.  For details on how to use Clover''s Android
    SDK to receive notifications see: https://github.com/clover/android-examples/tree/master/pushnotificationexample'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/clover/v3appsaidmerchantsmidnotifications-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://cloudflare.api.gallery.streamdata.io
- type: x-api-stack
  url: http://clover.stack.network
- type: x-crunchbase
  url: https://crunchbase.com/organization/clover
- type: x-developer
  url: https://www.clover.com/developers
- type: x-documentation
  url: https://docs.clover.com/
- type: x-github
  url: https://github.com/clover
- type: x-twitter
  url: https://twitter.com/CloverPOS
- type: x-website
  url: https://www.clover.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---