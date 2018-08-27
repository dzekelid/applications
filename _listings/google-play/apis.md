---
name: Google Play
x-slug: google-play
description: 'The Google Play Developer API allows you to perform a number of publishing
  and app-management tasks. It includes two components: The Subscriptions and In-App
  Purchases API lets you manage in-app purchases and subscriptions. The Publishing
  API lets you upload and publish apps, and perform other publishing-related tasks.'
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-play.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Applications
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/google-play/apis.md
specificationVersion: "0.14"
apis:
- name: Google Play - Create App Edit
  x-api-slug: packagenameedits-post
  description: Creates a new edit for an app, populated with the app's current state.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-play.png
  humanURL: https://play.google.com/store
  baseURL: https:///
  tags: Google APIs, Android, Mobile, Gaming, Games, Movies, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/google-play/packagenameedits-post-openapi.md
- name: Google Play - Delete App Edit
  x-api-slug: packagenameeditseditid-delete
  description: Deletes an edit for an app. Creating a new edit will automatically
    delete any of your previous edits so this method need only be called if you want
    to preemptively abandon an edit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-play.png
  humanURL: https://play.google.com/store
  baseURL: https:///
  tags: Google APIs, Android, Mobile, Gaming, Games, Movies, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/google-play/packagenameeditseditid-delete-openapi.md
- name: Google Play - DGetelete App Edit
  x-api-slug: packagenameeditseditid-get
  description: Returns information about the edit specified. Calls will fail if the
    edit is no long active (e.g. has been deleted, superseded or expired).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-play.png
  humanURL: https://play.google.com/store
  baseURL: https:///
  tags: Google APIs, Android, Mobile, Gaming, Games, Movies, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/google-play/packagenameeditseditid-get-openapi.md
- name: Google Play - Create APK
  x-api-slug: packagenameeditseditidapksexternallyhosted-post
  description: Creates a new APK without uploading the APK itself to Google Play,
    instead hosting the APK at a specified URL. This function is only available to
    enterprises using Google Play for Work whose application is configured to restrict
    distribution to the enterprise domain.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-play.png
  humanURL: https://play.google.com/store
  baseURL: https:///
  tags: Google APIs, Android, Mobile, Gaming, Games, Movies, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/google-play/packagenameeditseditidapksexternallyhosted-post-openapi.md
- name: Google Play - Get App Detail
  x-api-slug: packagenameeditseditiddetails-get
  description: Fetches app details for this edit. This includes the default language
    and developer support contact information.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-play.png
  humanURL: https://play.google.com/store
  baseURL: https:///
  tags: Google APIs, Android, Mobile, Gaming, Games, Movies, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/google-play/packagenameeditseditiddetails-get-openapi.md
- name: Google Play - Update App Detail
  x-api-slug: packagenameeditseditiddetails-patch
  description: Updates app details for this edit. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-play.png
  humanURL: https://play.google.com/store
  baseURL: https:///
  tags: Google APIs, Android, Mobile, Gaming, Games, Movies, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/google-play/packagenameeditseditiddetails-patch-openapi.md
- name: Google Play - Update App Detail
  x-api-slug: packagenameeditseditiddetails-put
  description: Updates app details for this edit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-play.png
  humanURL: https://play.google.com/store
  baseURL: https:///
  tags: Google APIs, Android, Mobile, Gaming, Games, Movies, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/google-play/packagenameeditseditiddetails-put-openapi.md
- name: Google Play - Delete App Detail
  x-api-slug: packagenameeditseditidlistings-delete
  description: Deletes all localized listings from an edit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-play.png
  humanURL: https://play.google.com/store
  baseURL: https:///
  tags: Google APIs, Android, Mobile, Gaming, Games, Movies, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/google-play/packagenameeditseditidlistings-delete-openapi.md
- name: Google Play - Get App Details
  x-api-slug: packagenameeditseditidlistings-get
  description: Returns all of the localized store listings attached to this edit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-play.png
  humanURL: https://play.google.com/store
  baseURL: https:///
  tags: Google APIs, Android, Mobile, Gaming, Games, Movies, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/google-play/packagenameeditseditidlistings-get-openapi.md
- name: Google Play - Set Played
  x-api-slug: applicationsplayed-post
  description: Indicate that the the currently authenticated user is playing your
    application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-play.png
  humanURL: https://play.google.com/store
  baseURL: https:///
  tags: Google APIs, Android, Mobile, Gaming, Games, Movies, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/google-play/applicationsplayed-post-openapi.md
- name: Google Play - Get Application
  x-api-slug: applicationsapplicationid-get
  description: Retrieves the metadata of the application with the given ID. If the
    requested application is not available for the specified platformType, the returned
    response will not include any instance data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-play.png
  humanURL: https://play.google.com/store
  baseURL: https:///
  tags: Google APIs, Android, Mobile, Gaming, Games, Movies, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/google-play/applicationsapplicationid-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.people.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.play.stack.network
- type: x-blog
  url: https://blog.google/products/google-play/
- type: x-blog-rss
  url: https://blog.google/products/google-play/rss
- type: x-developer
  url: https://developers.google.com/android-publisher/
- type: x-facebook
  url: https://www.facebook.com/GooglePlay
- type: x-getting-started
  url: https://developers.google.com/android-publisher/getting_started
- type: x-twitter
  url: https://twitter.com/GooglePlay
- type: x-website
  url: https://play.google.com/store
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---