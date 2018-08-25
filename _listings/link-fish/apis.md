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
- name: link.fish
  x-api-slug: link-fish
  description: api-to-easily-extract-data-from-websites--base-urlall-urls-referenced-in-the-documentation-have-the-following-basehttpsapi-link-fishthe-rest-api-is-only-served-over-https--to-ensure-data-privacy-unencrypted-http-is-not-supported--authenticationhttp-requests-to-the-rest-api-are-protected-with-http-basic-authenticationhttpsen-wikipedia-orgwikibasic-access-authentication--you-will-use-the-email-address-of-your-link-fish-account-as-the-username-and-your-api-access-token-as-the-password-for-http-basic-authentication-if-you-do-not-have-an-account-yet-go-to-httpslink-fishapihttpslink-fishapi-and-create-one-first-you-will-receive-the-api-access-token-automatically-via-email-after-you-signed-up--to-generate-a-new-token-and-invalidate-the-current-one-log-into-your-link-fish--account-at-httpsapp-link-fishhttpsapp-link-fish-and-go-to-plugins--api-dashboardthere-you-can-also-see-how-many-credits-you-used-already--errorsthe-api-uses-standard-http-status-codes-to-indicate-the-success-or-failure-of-the-api-call--the-body-of-the-response-will-be-json-in-the-following-format--status-http-status-code--message-error-messagelike-for-example-when-the-authorization-is-not-provided-or-wrong--status-401--message-unauthorized-request-idseach-api-request-has-an-associated-request-identifier--you-can-find-it-in-the-response-headers-under-xlfrequestid--in-case-you-have-problems-please-provide-this-identifier-that-we-can-help-you-as-good-and-fast-as-possible-examplexlfrequestid-f7f0036f5277421ab143f7a151571d18-item-formatthe-data-is-by-default-deeply-nested--so-if-it-should-be-checked-if-there-is-an-offer-with-a-price-the-whole-tree-has-to-be-checked--to-make-that-simpler-it-is-also-possible-to-return-the-data-flat--if-selected-it-will-flatten-the-tree-by-copying-all-the-data-to-the-main-level-under-a-property-with-the-name-of-its-type-and-link-the-data-internally-information-we-created-a-node-module-which-allows-converting-between-the-two-formats--it-did-not-get-open-sourced-yet--if-you-are-in-need-simply-contact-us-via-apilink-fish--response-content-typeby-default-all-data-gets-returned-as-json--if-the-data-should-be-returned-as-xml-add-the-following-headeraccept-applicationxml-creditsdepending-on-the-request-made-a-different-amount-of-credits-get-charged--how-many-which-request-costs-can-be-found-on-the-api-pricing-pagehttplink-fishapipricing--additionally-does-a--header-named-xlfcreditscharged-get-added-to-each-successful-response-with-the-amount-of-credits-charged-examplexlfcreditscharged-1you-can-check-anytime-how-many-credits-you-did-use-already-by-logging-into-your-link-fish--account-at-httpsapp-link-fishhttpsapp-link-fish-and-checking-under--plugins--api-dashboardif-you-have-problems-questions-or-improvement-advice-please-send-us-an-email-to-apilink-fish
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/link-fish-logo.png
  humanURL: http://link.fish
  baseURL: https://api.link.fish//
  tags: Links, Content, Scraping, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/link-fish/urlsapps-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/link-fish/urlsapps-get-openapi.md
- name: link.fish
  x-api-slug: link-fish
  description: api-to-easily-extract-data-from-websites--base-urlall-urls-referenced-in-the-documentation-have-the-following-basehttpsapi-link-fishthe-rest-api-is-only-served-over-https--to-ensure-data-privacy-unencrypted-http-is-not-supported--authenticationhttp-requests-to-the-rest-api-are-protected-with-http-basic-authenticationhttpsen-wikipedia-orgwikibasic-access-authentication--you-will-use-the-email-address-of-your-link-fish-account-as-the-username-and-your-api-access-token-as-the-password-for-http-basic-authentication-if-you-do-not-have-an-account-yet-go-to-httpslink-fishapihttpslink-fishapi-and-create-one-first-you-will-receive-the-api-access-token-automatically-via-email-after-you-signed-up--to-generate-a-new-token-and-invalidate-the-current-one-log-into-your-link-fish--account-at-httpsapp-link-fishhttpsapp-link-fish-and-go-to-plugins--api-dashboardthere-you-can-also-see-how-many-credits-you-used-already--errorsthe-api-uses-standard-http-status-codes-to-indicate-the-success-or-failure-of-the-api-call--the-body-of-the-response-will-be-json-in-the-following-format--status-http-status-code--message-error-messagelike-for-example-when-the-authorization-is-not-provided-or-wrong--status-401--message-unauthorized-request-idseach-api-request-has-an-associated-request-identifier--you-can-find-it-in-the-response-headers-under-xlfrequestid--in-case-you-have-problems-please-provide-this-identifier-that-we-can-help-you-as-good-and-fast-as-possible-examplexlfrequestid-f7f0036f5277421ab143f7a151571d18-item-formatthe-data-is-by-default-deeply-nested--so-if-it-should-be-checked-if-there-is-an-offer-with-a-price-the-whole-tree-has-to-be-checked--to-make-that-simpler-it-is-also-possible-to-return-the-data-flat--if-selected-it-will-flatten-the-tree-by-copying-all-the-data-to-the-main-level-under-a-property-with-the-name-of-its-type-and-link-the-data-internally-information-we-created-a-node-module-which-allows-converting-between-the-two-formats--it-did-not-get-open-sourced-yet--if-you-are-in-need-simply-contact-us-via-apilink-fish--response-content-typeby-default-all-data-gets-returned-as-json--if-the-data-should-be-returned-as-xml-add-the-following-headeraccept-applicationxml-creditsdepending-on-the-request-made-a-different-amount-of-credits-get-charged--how-many-which-request-costs-can-be-found-on-the-api-pricing-pagehttplink-fishapipricing--additionally-does-a--header-named-xlfcreditscharged-get-added-to-each-successful-response-with-the-amount-of-credits-charged-examplexlfcreditscharged-1you-can-check-anytime-how-many-credits-you-did-use-already-by-logging-into-your-link-fish--account-at-httpsapp-link-fishhttpsapp-link-fish-and-checking-under--plugins--api-dashboardif-you-have-problems-questions-or-improvement-advice-please-send-us-an-email-to-apilink-fish
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/link-fish-logo.png
  humanURL: http://link.fish
  baseURL: https://api.link.fish//
  tags: Links, Content, Scraping, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/link-fish/urlsapps-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/link-fish/urlsapps-get-openapi.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/link-fish/urlsapps-get-openapi.md
- name: link.fish
  x-api-slug: link-fish
  description: Automatically get the information of the websites you are interested
    in and work with it together with others in real-time. Depending on the page you
    bookmark link.fish automatically extracts the data you actually care about. No
    matter if bedrooms for apartments, rating of movies or the cook time of your favorite
    recipe. Invite other people to your collection to work with them or make it public
    for everbody to see. All changes made will immediately be visible by everyone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/link-fish-logo.png
  humanURL: http://link.fish
  baseURL: https://api.link.fish//
  tags: Applications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/link-fish/openapi.md
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