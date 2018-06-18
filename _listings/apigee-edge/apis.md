---
name: Apigee Edge
x-slug: apigee-edge
description: Apigee Edge is a platform for developing and managing API proxies. Think
  of a proxy as an abstraction layer that fronts for your backend service APIs and
  provides value-added features like security, rate limiting, quotas, analytics, and
  more. The primary consumers of Edge API proxies are app developers who want to use
  your backend services.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
x-kinRank: "8"
x-alexaRank: "0"
tags: Applications
created: "2018-06-17"
modified: "2018-06-17"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/apis.md
specificationVersion: "0.14"
apis:
- name: Apigee Edge Get Organizations Name Developers Developer Email Apps
  x-api-slug: apigee-edge
  description: Provides an expanded view of a developer's collection of apps .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/apps
  tags: Organizations,Developers,Developer,Email,Applications,s
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namedevelopersdeveloper-emailapps-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namedevelopersdeveloper-emailapps-get-openapi.md
- name: Apigee Edge Post Organizations Name Developers Developer Email Apps
  x-api-slug: apigee-edge
  description: Creates an app associated with a developer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/apps
  tags: Organizations,Developers,Developer,Email,Applications,s
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namedevelopersdeveloper-emailapps-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namedevelopersdeveloper-emailapps-post-openapi.md
- name: Apigee Edge Get Organizations Name Developers Developer Email Apps App Name
  x-api-slug: apigee-edge
  description: Gets a count of all API resources in the API products accessible by
    a developer app .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/apps/{app_name}
  tags: Organizations,Developers,Developer,Email,Applications,
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namedevelopersdeveloper-emailappsapp-name-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namedevelopersdeveloper-emailappsapp-name-get-openapi.md
- name: Apigee Edge Put Organizations Name Developers Developer Email Apps App Name
  x-api-slug: apigee-edge
  description: Updates the app to get a new set of consumer credentials.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/apps/{app_name}
  tags: Organizations,Developers,Developer,Email,Applications,
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namedevelopersdeveloper-emailappsapp-name-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namedevelopersdeveloper-emailappsapp-name-put-openapi.md
- name: Apigee Edge Post Organizations Name Developers Developer Email Apps App Name
  x-api-slug: apigee-edge
  description: Revokes a Developer App, disabling access to all API Products .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/apps/{app_name}
  tags: Organizations,Developers,Developer,Email,Applications,
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namedevelopersdeveloper-emailappsapp-name-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namedevelopersdeveloper-emailappsapp-name-post-openapi.md
- name: Apigee Edge Delete Organizations Name Developers Developer Email Apps App
    Name
  x-api-slug: apigee-edge
  description: Delete a Developer's App.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/apps/{app_name}
  tags: Organizations,Developers,Developer,Email,Applications,
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namedevelopersdeveloper-emailappsapp-name-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namedevelopersdeveloper-emailappsapp-name-delete-openapi.md
- name: Apigee Edge Get Organizations Name Developers Developer Email Apps App Name
    Keys Consumer Key
  x-api-slug: apigee-edge
  description: Returns details for a consumer key for a developer app .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/apps/{app_name}/keys/{consumer_key}
  tags: Organizations,Developers,Developer,Email,Applications,,Keys,Consumer,Key
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namedevelopersdeveloper-emailappsapp-namekeysconsumer-key-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namedevelopersdeveloper-emailappsapp-namekeysconsumer-key-get-openapi.md
- name: Apigee Edge Post Organizations Name Developers Developer Email Apps App Name
    Keys Consumer Key
  x-api-slug: apigee-edge
  description: Revokes a developer app key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/apps/{app_name}/keys/{consumer_key}
  tags: Organizations,Developers,Developer,Email,Applications,,Keys,Consumer,Key
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namedevelopersdeveloper-emailappsapp-namekeysconsumer-key-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namedevelopersdeveloper-emailappsapp-namekeysconsumer-key-post-openapi.md
- name: Apigee Edge Delete Organizations Name Developers Developer Email Apps App
    Name Keys Consumer Key
  x-api-slug: apigee-edge
  description: Deletes a consumer key that belongs to an app.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/apps/{app_name}/keys/{consumer_key}
  tags: Organizations,Developers,Developer,Email,Applications,,Keys,Consumer,Key
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namedevelopersdeveloper-emailappsapp-namekeysconsumer-key-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namedevelopersdeveloper-emailappsapp-namekeysconsumer-key-delete-openapi.md
- name: Apigee Edge Post Organizations Name Developers Developer Email Apps App Name
    Keys Consumer Key Apiproducts Apiproduct Name
  x-api-slug: apigee-edge
  description: Revokes the association of an API Product with a Developer App's consumer
    key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/apps/{app_name}/keys/{consumer_key}/apiproducts/{apiproduct_name}
  tags: Organizations,Developers,Developer,Email,Applications,,Keys,Consumer,Key,API,Products,API,Productss
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namedevelopersdeveloper-emailappsapp-namekeysconsumer-keyapiproductsapiproduct-name-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namedevelopersdeveloper-emailappsapp-namekeysconsumer-keyapiproductsapiproduct-name-post-openapi.md
- name: Apigee Edge Delete Organizations Name Developers Developer Email Apps App
    Name Keys Consumer Key Apiproducts Apiproduct Name
  x-api-slug: apigee-edge
  description: Removes an API product from a developer app key profile, and thereby
    renders the developer app unable to access the URIs defined in the API product
    specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/apps/{app_name}/keys/{consumer_key}/apiproducts/{apiproduct_name}
  tags: Organizations,Developers,Developer,Email,Applications,,Keys,Consumer,Key,API,Products,API,Productss
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namedevelopersdeveloper-emailappsapp-namekeysconsumer-keyapiproductsapiproduct-name-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namedevelopersdeveloper-emailappsapp-namekeysconsumer-keyapiproductsapiproduct-name-delete-openapi.md
- name: Apigee Edge Get Organizations Name Developers Developer Email Apps App Name
    Oauth1accesstokens
  x-api-slug: apigee-edge
  description: Get count of OAuth 1.0 access tokens for a developer's app.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/apps/{app_name}/oauth1accesstokens
  tags: Organizations,Developers,Developer,Email,Applications,,Oauth1accesstokens
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namedevelopersdeveloper-emailappsapp-nameoauth1accesstokens-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namedevelopersdeveloper-emailappsapp-nameoauth1accesstokens-get-openapi.md
- name: Apigee Edge Get Organizations Name Developers Developer Email Apps App Name
    Oauth2accesstokens
  x-api-slug: apigee-edge
  description: Get count of    OAuth 2.0 access tokens for a developer's app.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/apps/{app_name}/oauth2accesstokens
  tags: Organizations,Developers,Developer,Email,Applications,,Oauth2accesstokens
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namedevelopersdeveloper-emailappsapp-nameoauth2accesstokens-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namedevelopersdeveloper-emailappsapp-nameoauth2accesstokens-get-openapi.md
- name: Apigee Edge Get Organizations Name Developers Developer Email Apps App Name
    Keys Consumer Key Oauth1accesstokens
  x-api-slug: apigee-edge
  description: Get count of OAuth 1.0 access tokens for a developer's app key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/apps/{app_name}/keys/{consumer_key}/oauth1accesstokens
  tags: Organizations,Developers,Developer,Email,Applications,,Keys,Consumer,Key,Oauth1accesstokens
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namedevelopersdeveloper-emailappsapp-namekeysconsumer-keyoauth1accesstokens-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namedevelopersdeveloper-emailappsapp-namekeysconsumer-keyoauth1accesstokens-get-openapi.md
- name: Apigee Edge Get Organizations Name Developers Developer Email Apps App Name
    Keys Consumer Key Oauth2accesstokens
  x-api-slug: apigee-edge
  description: Get count of OAuth 2.0 access tokens for a developer's app key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/apps/{app_name}/keys/{consumer_key}/oauth2accesstokens
  tags: Organizations,Developers,Developer,Email,Applications,,Keys,Consumer,Key,Oauth2accesstokens
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namedevelopersdeveloper-emailappsapp-namekeysconsumer-keyoauth2accesstokens-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namedevelopersdeveloper-emailappsapp-namekeysconsumer-keyoauth2accesstokens-get-openapi.md
- name: Apigee Edge Get Organizations Name Companies Company Name Apps
  x-api-slug: apigee-edge
  description: Gets an expanded list company apps .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}/apps
  tags: Organizations,Companies,Companies,Applications,s
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namecompaniescompany-nameapps-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namecompaniescompany-nameapps-get-openapi.md
- name: Apigee Edge Post Organizations Name Companies Company Name Apps
  x-api-slug: apigee-edge
  description: Creates an app for a company.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}/apps
  tags: Organizations,Companies,Companies,Applications,s
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namecompaniescompany-nameapps-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namecompaniescompany-nameapps-post-openapi.md
- name: Apigee Edge Get Organizations Name Companies Company Name Apps App Name
  x-api-slug: apigee-edge
  description: Gets the count    of API resources for a company app.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}/apps/{app_name}
  tags: Organizations,Companies,Companies,Applications,
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namecompaniescompany-nameappsapp-name-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namecompaniescompany-nameappsapp-name-get-openapi.md
- name: Apigee Edge Post Organizations Name Companies Company Name Apps App Name
  x-api-slug: apigee-edge
  description: Updates an existing company app.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}/apps/{app_name}
  tags: Organizations,Companies,Companies,Applications,
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namecompaniescompany-nameappsapp-name-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namecompaniescompany-nameappsapp-name-post-openapi.md
- name: Apigee Edge Delete Organizations Name Companies Company Name Apps App Name
  x-api-slug: apigee-edge
  description: Deletes a company app.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}/apps/{app_name}
  tags: Organizations,Companies,Companies,Applications,
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namecompaniescompany-nameappsapp-name-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namecompaniescompany-nameappsapp-name-delete-openapi.md
- name: Apigee Edge Get Organizations Name Companies Company Name Apps App Name Keys
    Consumer Key
  x-api-slug: apigee-edge
  description: Gets the consumer key issued to a company app.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}/apps/{app_name}/keys/{consumer_key}
  tags: Organizations,Companies,Companies,Applications,,Keys,Consumer,Key
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namecompaniescompany-nameappsapp-namekeysconsumer-key-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namecompaniescompany-nameappsapp-namekeysconsumer-key-get-openapi.md
- name: Apigee Edge Post Organizations Name Companies Company Name Apps App Name Keys
    Consumer Key
  x-api-slug: apigee-edge
  description: Revokes the specific key of a company app.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}/apps/{app_name}/keys/{consumer_key}
  tags: Organizations,Companies,Companies,Applications,,Keys,Consumer,Key
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namecompaniescompany-nameappsapp-namekeysconsumer-key-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namecompaniescompany-nameappsapp-namekeysconsumer-key-post-openapi.md
- name: Apigee Edge Delete Organizations Name Companies Company Name Apps App Name
    Keys Consumer Key
  x-api-slug: apigee-edge
  description: Deletes a company app key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}/apps/{app_name}/keys/{consumer_key}
  tags: Organizations,Companies,Companies,Applications,,Keys,Consumer,Key
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namecompaniescompany-nameappsapp-namekeysconsumer-key-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namecompaniescompany-nameappsapp-namekeysconsumer-key-delete-openapi.md
- name: Apigee Edge Get Organizations Name Companies Company Name Appfamilies
  x-api-slug: apigee-edge
  description: An expanded list of all app families in an organization, listing Apps
    in the collection.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}/appfamilies
  tags: Organizations,Companies,Companies,Applications,Families
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namecompaniescompany-nameappfamilies-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namecompaniescompany-nameappfamilies-get-openapi.md
- name: Apigee Edge Post Organizations Name Companies Company Name Appfamilies
  x-api-slug: apigee-edge
  description: Creates an app family.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}/appfamilies
  tags: Organizations,Companies,Companies,Applications,Families
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namecompaniescompany-nameappfamilies-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namecompaniescompany-nameappfamilies-post-openapi.md
- name: Apigee Edge Get Organizations Name Companies Company Name Appfamilies Appfamily
    Name
  x-api-slug: apigee-edge
  description: Gets a list of apps in an appfamily.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}/appfamilies/{appfamily_name}
  tags: Organizations,Companies,Companies,Applications,Families,Applications,family
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namecompaniescompany-nameappfamiliesappfamily-name-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namecompaniescompany-nameappfamiliesappfamily-name-get-openapi.md
- name: Apigee Edge Post Organizations Name Companies Company Name Appfamilies Appfamily
    Name
  x-api-slug: apigee-edge
  description: Updates an existing app family.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}/appfamilies/{appfamily_name}
  tags: Organizations,Companies,Companies,Applications,Families,Applications,family
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namecompaniescompany-nameappfamiliesappfamily-name-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namecompaniescompany-nameappfamiliesappfamily-name-post-openapi.md
- name: Apigee Edge Delete Organizations Name Companies Company Name Appfamilies Appfamily
    Name
  x-api-slug: apigee-edge
  description: Deletes an App Family and all Apps it contains.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}/appfamilies/{appfamily_name}
  tags: Organizations,Companies,Companies,Applications,Families,Applications,family
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namecompaniescompany-nameappfamiliesappfamily-name-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namecompaniescompany-nameappfamiliesappfamily-name-delete-openapi.md
- name: Apigee Edge Delete Organizations Name Companies Company Name Appfamilies Appfamily
    Name Apps App Name
  x-api-slug: apigee-edge
  description: Removes an App from an App Family.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}/appfamilies/{appfamily_name}/apps/{app_name}
  tags: Organizations,Companies,Companies,Applications,Families,Applications,family,Applications,
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namecompaniescompany-nameappfamiliesappfamily-nameappsapp-name-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namecompaniescompany-nameappfamiliesappfamily-nameappsapp-name-delete-openapi.md
- name: Apigee Edge Get Organizations Name Developers Developer Email Appfamilies
  x-api-slug: apigee-edge
  description: An expanded list of all app families in an organization, listing Apps
    in the collection
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/appfamilies
  tags: Organizations,Developers,Developer,Email,Applications,Families
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namedevelopersdeveloper-emailappfamilies-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namedevelopersdeveloper-emailappfamilies-get-openapi.md
- name: Apigee Edge Post Organizations Name Developers Developer Email Appfamilies
  x-api-slug: apigee-edge
  description: Creates an app family for developers.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/appfamilies
  tags: Organizations,Developers,Developer,Email,Applications,Families
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namedevelopersdeveloper-emailappfamilies-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namedevelopersdeveloper-emailappfamilies-post-openapi.md
- name: Apigee Edge Get Organizations Name Developers Developer Email Appfamilies
    Appfamily Name
  x-api-slug: apigee-edge
  description: Gets a list of apps in an appfamily.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/appfamilies/{appfamily_name}
  tags: Organizations,Developers,Developer,Email,Applications,Families,Applications,family
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namedevelopersdeveloper-emailappfamiliesappfamily-name-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namedevelopersdeveloper-emailappfamiliesappfamily-name-get-openapi.md
- name: Apigee Edge Post Organizations Name Developers Developer Email Appfamilies
    Appfamily Name
  x-api-slug: apigee-edge
  description: Updates an existing app family.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/appfamilies/{appfamily_name}
  tags: Organizations,Developers,Developer,Email,Applications,Families,Applications,family
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namedevelopersdeveloper-emailappfamiliesappfamily-name-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namedevelopersdeveloper-emailappfamiliesappfamily-name-post-openapi.md
- name: Apigee Edge Delete Organizations Name Developers Developer Email Appfamilies
    Appfamily Name
  x-api-slug: apigee-edge
  description: Deletes an App Family and all Apps it contains.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/appfamilies/{appfamily_name}
  tags: Organizations,Developers,Developer,Email,Applications,Families,Applications,family
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namedevelopersdeveloper-emailappfamiliesappfamily-name-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namedevelopersdeveloper-emailappfamiliesappfamily-name-delete-openapi.md
- name: Apigee Edge Delete Organizations Name Developers Developer Email Appfamilies
    Appfamily Name Apps App Name
  x-api-slug: apigee-edge
  description: Removes an App from an App Family.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/appfamilies/{appfamily_name}/apps/{app_name}
  tags: Organizations,Developers,Developer,Email,Applications,Families,Applications,family,Applications,
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namedevelopersdeveloper-emailappfamiliesappfamily-nameappsapp-name-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/organizationsorg-namedevelopersdeveloper-emailappfamiliesappfamily-nameappsapp-name-delete-openapi.md
- name: Apigee Edge
  x-api-slug: apigee-edge
  description: Apigee Edge is a platform for developing and managing API proxies.
    Think of a proxy as an abstraction layer that fronts for your backend service
    APIs and provides value-added features like security, rate limiting, quotas, analytics,
    and more. The primary consumers of Edge API proxies are app developers who want
    to use your backend services.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1/
  tags: Applications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/apigee-edge/openapi.md
x-common:
- type: x-website
  url: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---