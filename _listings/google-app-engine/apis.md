---
name: Google App Engine
x-slug: google-app-engine
description: 'Build modern web and mobile applications on an open cloud platform:
  bring your own language runtimes, frameworks, and third party libraries. Google
  App Engine is a fully managed platform that completely abstracts away infrastructure
  so you focus only on code. Go from zero to planet-scale and see why some of today&rsquo;s
  most successful companies power their applications on App Engine.'
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-app-engine-icon.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Applications
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/google-app-engine/apis.md
specificationVersion: "0.14"
apis:
- name: Google App Engine Admin - Create App
  x-api-slug: v1apps-post
  description: 'Creates an App Engine application for a Google Cloud Platform project.
    Required fields: id - The ID of the target Cloud Platform project. location -
    The region (https://cloud.google.com/appengine/docs/locations) where you want
    the App Engine application located.For more information about App Engine applications,
    see Managing Projects, Applications, and Billing (https://cloud.google.com/appengine/docs/python/console/).'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-app-engine-icon.png
  humanURL: https://cloud.google.com/appengine/
  baseURL: ://appengine.googleapis.com//
  tags: Google APIs, Compute, Cloud, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/google-app-engine/v1apps-post-openapi.md
- name: Google App Engine Admin - Get App
  x-api-slug: v1appsappsid-get
  description: Gets information about an application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-app-engine-icon.png
  humanURL: https://cloud.google.com/appengine/
  baseURL: ://appengine.googleapis.com//
  tags: Google APIs, Compute, Cloud, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/google-app-engine/v1appsappsid-get-openapi.md
- name: Google App Engine Admin - Update App
  x-api-slug: v1appsappsid-patch
  description: 'Updates the specified Application resource. You can update the following
    fields: auth_domain - Google authentication domain for controlling user access
    to the application. default_cookie_expiration - Cookie expiration policy for the
    application.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-app-engine-icon.png
  humanURL: https://cloud.google.com/appengine/
  baseURL: ://appengine.googleapis.com//
  tags: Google APIs, Compute, Cloud, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/google-app-engine/v1appsappsid-patch-openapi.md
- name: Google App Engine Admin - Repair App
  x-api-slug: v1appsappsidrepair-post
  description: Recreates the required App Engine features for the specified App Engine
    application, for example a Cloud Storage bucket or App Engine service account.
    Use this method if you receive an error message about a missing feature, for example,
    Error retrieving the App Engine service account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-app-engine-icon.png
  humanURL: https://cloud.google.com/appengine/
  baseURL: ://appengine.googleapis.com//
  tags: Google APIs, Compute, Cloud, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/google-app-engine/v1appsappsidrepair-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.api.discovery.service.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.app.engine.stack.network
- type: x-code-page
  url: https://cloud.google.com/appengine/docs/admin-api/client-libraries
- type: x-developer
  url: https://cloud.google.com/appengine/docs/admin-api/
- type: x-documentation
  url: https://cloud.google.com/appengine/docs/admin-api/apis
- type: x-getting-started
  url: https://cloud.google.com/appengine/docs/admin-api/getting-started/
- type: x-how-to-guides
  url: https://cloud.google.com/appengine/docs/admin-api/how-to
- type: x-launcher
  url: https://cloud.google.com/launcher/
- type: x-pricing
  url: https://cloud.google.com/pricing/
- type: x-sla
  url: https://cloud.google.com/appengine/sla
- type: x-website
  url: https://cloud.google.com/appengine/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---