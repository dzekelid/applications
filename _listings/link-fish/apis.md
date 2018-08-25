---
name: link.fish
x-slug: link-fish
description: Automatically get the information of the websites you are interested
  in and work with it together with others in real-time. Depending on the page you
  bookmark link.fish automatically extracts the data you actually care about. No matter
  if bedrooms for apartments, rating of movies or the cook time of your favorite recipe.
  Invite other people to your collection to work with them or make it public for everbody
  to see. All changes made will immediately be visible by everyone.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/link-fish-logo.png
x-kinRank: "7"
x-alexaRank: "0"
tags: Applications
created: "2018-08-25"
modified: "2018-08-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/link-fish/apis.md
specificationVersion: "0.14"
apis:
- name: link.fish - Get mobile apps
  x-api-slug: urlsapps-get
  description: |-
    Visits the URL and checks if there are mobile apps on them and returns the found ones.

    Will by default return the app identifiers and not the full URL to the apps. To return URLs instead set the parameter "return_urls" to true.

    The URLs can also be created manually like this:

    | Property | URL                                                |
    | -------- | -------------------------------------------------- |
    | android  | https://play.google.com/store/apps/details?id={ID} |
    | ios      | https://itunes.apple.com/us/app/app-name/id{ID}    |

    Properties only get set when a value for it has been found. That means that if no app has been found only the property "url" will be set.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/link-fish-logo.png
  humanURL: http://link.fish
  baseURL: https://api.link.fish//
  tags: Links, Content, Scraping, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/link-fish/urlsapps-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/link-fish/urlsapps-get-openapi.md
- name: link.fish - Get mobile apps
  x-api-slug: urlsapps-get
  description: |-
    Visits the URL and checks if there are mobile apps on them and returns the found ones.

    Will by default return the app identifiers and not the full URL to the apps. To return URLs instead set the parameter "return_urls" to true.

    The URLs can also be created manually like this:

    | Property | URL                                                |
    | -------- | -------------------------------------------------- |
    | android  | https://play.google.com/store/apps/details?id={ID} |
    | ios      | https://itunes.apple.com/us/app/app-name/id{ID}    |

    Properties only get set when a value for it has been found. That means that if no app has been found only the property "url" will be set.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/link-fish-logo.png
  humanURL: http://link.fish
  baseURL: https://api.link.fish//
  tags: Links, Content, Scraping, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/link-fish/urlsapps-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/link-fish/urlsapps-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://learnifier.api.gallery.streamdata.io
- type: x-api-stack
  url: http://link.fish.stack.network
- type: x-developer
  url: https://link.fish/api/
- type: x-github
  url: https://github.com/link-fish
- type: x-twitter
  url: https://twitter.com/linkfish_
- type: x-website
  url: http://link.fish
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---