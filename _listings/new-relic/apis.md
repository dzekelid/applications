---
name: New Relic
x-slug: new-relic
description: New Relic offers SaaS Software Analytics Platform that offers Application
  Performance Management and Real User Monitoring for Cloud and Data Center deployed
  web applications implemented in Ruby, Java, .NET, Python, PHP, Node.js. New Relic
  also offers mobile monitoring solutions for iOS and Android applications.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/newrelic-logo-square.png
x-kinRank: "8"
x-alexaRank: ""
tags: Applications
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/new-relic/apis.md
specificationVersion: "0.14"
apis:
- name: New Relic Get Applications Application  Deployments. Format
  x-api-slug: new-relic
  description: |-
    This API endpoint returns a paginated list of the deployments associated with a given application.

    See our documentation for a discussion on output pagination.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/newrelic-logo-square.png
  humanURL: https://newrelic.com/
  baseURL: https:///v2///applications/{application_id}/deployments.{format}
  tags: Applications, Application, , Deployments., Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/new-relic/applicationsapplication-iddeploymentsformat-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/new-relic/applicationsapplication-iddeploymentsformat-get-openapi.md
- name: New Relic Add Applications Application  Deployments. Format
  x-api-slug: new-relic
  description: "This API endpoint creates a deployment record for a given application.\nDeployment
    records are created with the following attributes:\n\nRequired:\n\_\_- Application
    ID\n\_\_- Revision, such as a git SHA\n\nOptional:\n\_\_- Changelog \n\_\_- Description
    \n\_\_- User posting the deployment\n\nNote that the time of your deployment will
    be recorded as the current time in UTC."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/newrelic-logo-square.png
  humanURL: https://newrelic.com/
  baseURL: https:///v2///applications/{application_id}/deployments.{format}
  tags: Applications, Application, , Deployments., Format
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/new-relic/applicationsapplication-iddeploymentsformat-post-openapi.md
- name: New Relic Delete Applications Application  Deployments  . Format
  x-api-slug: new-relic
  description: "This API endpoint deletes the specified deployment record.\n\nNote:
    Admin User\u2019s API Key is required."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/newrelic-logo-square.png
  humanURL: https://newrelic.com/
  baseURL: https:///v2///applications/{application_id}/deployments/{id}.{format}
  tags: Applications, Application, , Deployments, , ., Format
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/new-relic/applicationsapplication-iddeploymentsidformat-delete-openapi.md
- name: New Relic Get Applications Application  Hosts. Format
  x-api-slug: new-relic
  description: "This API endpoint returns a \npaginated list of hosts associated with
    the given application. The time range for summary data is the last 10 minutes.\n\nApplication
    hosts can be filtered by hostname, or the list of application host IDs.\n\nSee
    our documentation for a discussion and examples of\nusing  filters \nand summary
    data output."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/newrelic-logo-square.png
  humanURL: https://newrelic.com/
  baseURL: https:///v2///applications/{application_id}/hosts.{format}
  tags: Applications, Application, , Hosts., Format
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/new-relic/applicationsapplication-idhostsformat-get-openapi.md
- name: New Relic Get Applications Application  Hosts  . Format
  x-api-slug: new-relic
  description: |-
    This API endpoint returns a single application host, identified by ID. The time range for summary data is the last 10 minutes.

    See our documentation for a discussion of
    summary data output.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/newrelic-logo-square.png
  humanURL: https://newrelic.com/
  baseURL: https:///v2///applications/{application_id}/hosts/{id}.{format}
  tags: Applications, Application, , Hosts, , ., Format
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/new-relic/applicationsapplication-idhostsidformat-get-openapi.md
- name: New Relic Get Applications Application  Hosts Host  Metrics. Format
  x-api-slug: new-relic
  description: |-
    Return a list of known metrics and their value names for the given resource.

    See our documentation for a discussion
    on  output pagination
    and for examples of requesting and using metric values.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/newrelic-logo-square.png
  humanURL: https://newrelic.com/
  baseURL: https:///v2///applications/{application_id}/hosts/{host_id}/metrics.{format}
  tags: Applications, Application, , Hosts, Host, , Metrics., Format
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/new-relic/applicationsapplication-idhostshost-idmetricsformat-get-openapi.md
- name: New Relic Get Applications Application  Hosts Host  Metrics Data. Format
  x-api-slug: new-relic
  description: "This API endpoint returns a list of values for each of the requested
    metrics. The list of available metrics\ncan be returned using the Metric Name
    API endpoint.\n\nMetric data can be filtered by a number of parameters, including
    multiple names and values, and by time range.\nMetric names and values will be
    matched intelligently in the background.\n\nYou can also retrieve a summarized
    data point across the entire time range selected by using the summarize\nparameter.\n\nSee
    our documentation for a discussion on \noutput pagination,  time range \nrelated
    considerations, and for examples of requesting and using metric values."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/newrelic-logo-square.png
  humanURL: https://newrelic.com/
  baseURL: https:///v2///applications/{application_id}/hosts/{host_id}/metrics/data.{format}
  tags: Applications, Application, , Hosts, Host, , Metrics, Data., Format
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/new-relic/applicationsapplication-idhostshost-idmetricsdataformat-get-openapi.md
- name: New Relic Get Applications Application  Instances. Format
  x-api-slug: new-relic
  description: "This API endpoint returns a \npaginated list of instances associated
    with the given application. The time range for summary data is the last 10 minutes.\n\nApplication
    instances can be filtered by hostname, or the list of application instance IDs.\n\nSee
    our documentation for a discussion and examples of\nusing  filters \nand summary
    data output."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/newrelic-logo-square.png
  humanURL: https://newrelic.com/
  baseURL: https:///v2///applications/{application_id}/instances.{format}
  tags: Applications, Application, , Instances., Format
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/new-relic/applicationsapplication-idinstancesformat-get-openapi.md
- name: New Relic Get Applications Application  Instances  . Format
  x-api-slug: new-relic
  description: |-
    This API endpoint returns a single application instance, identified by ID. The time range for summary data is the last 10 minutes.

    See our documentation for a discussion of
     summary data output.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/newrelic-logo-square.png
  humanURL: https://newrelic.com/
  baseURL: https:///v2///applications/{application_id}/instances/{id}.{format}
  tags: Applications, Application, , Instances, , ., Format
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/new-relic/applicationsapplication-idinstancesidformat-get-openapi.md
- name: New Relic Get Applications Application  Instances Instance  Metrics. Format
  x-api-slug: new-relic
  description: |-
    Return a list of known metrics and their value names for the given resource.

    See our documentation for a discussion
    on  output pagination
    and for examples of requesting and using metric values.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/newrelic-logo-square.png
  humanURL: https://newrelic.com/
  baseURL: https:///v2///applications/{application_id}/instances/{instance_id}/metrics.{format}
  tags: Applications, Application, , Instances, Instance, , Metrics., Format
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/new-relic/applicationsapplication-idinstancesinstance-idmetricsformat-get-openapi.md
- name: New Relic Get Applications Application  Instances Instance  Metrics Data.
    Format
  x-api-slug: new-relic
  description: "This API endpoint returns a list of values for each of the requested
    metrics. The list of available metrics\ncan be returned using the Metric Name
    API endpoint.\n\nMetric data can be filtered by a number of parameters, including
    multiple names and values, and by time range.\nMetric names and values will be
    matched intelligently in the background.\n\nYou can also retrieve a summarized
    data point across the entire time range selected by using the summarize\nparameter.\n\nSee
    our documentation for a discussion on \noutput pagination,  time range \nrelated
    considerations, and for examples of requesting and using metric values."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/newrelic-logo-square.png
  humanURL: https://newrelic.com/
  baseURL: https:///v2///applications/{application_id}/instances/{instance_id}/metrics/data.{format}
  tags: Applications, Application, , Instances, Instance, , Metrics, Data., Format
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/new-relic/applicationsapplication-idinstancesinstance-idmetricsdataformat-get-openapi.md
- name: New Relic Get Applications. Format
  x-api-slug: new-relic
  description: "This API endpoint returns a paginated\nlist of the Applications associated
    with your New Relic account. The time range for summary data is the last 10 minutes.\n\nApplications
    can be filtered by their name, hosts, the list of application IDs or the application
    language as\nreported by the agents.\n\nSee our documentation for a discussion
    and examples of\nusing  filters \nand summary data output."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/newrelic-logo-square.png
  humanURL: https://newrelic.com/
  baseURL: https:///v2///applications.{format}
  tags: Applications., Format
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/new-relic/applicationsformat-get-openapi.md
- name: New Relic Get Applications  . Format
  x-api-slug: new-relic
  description: |-
    This API endpoint returns a single Application, identified by ID. The time range for summary data is the last 10 minutes.

    See our documentation for a discussion of the
     summary data output.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/newrelic-logo-square.png
  humanURL: https://newrelic.com/
  baseURL: https:///v2///applications/{id}.{format}
  tags: Applications, , ., Format
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/new-relic/applicationsidformat-get-openapi.md
- name: New Relic Put Applications  . Format
  x-api-slug: new-relic
  description: |-
    This API endpoint allows you to update certain parameters of your application.

    The input is expected to be in JSON or XML format in the body parameter of the PUT request. The exact
    schema is defined below. Any extra parameters passed in the body will be ignored.

    See our documentation for a discussion and simple example of
     updating
    an application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/newrelic-logo-square.png
  humanURL: https://newrelic.com/
  baseURL: https:///v2///applications/{id}.{format}
  tags: Applications, , ., Format
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/new-relic/applicationsidformat-put-openapi.md
- name: New Relic Delete Applications  . Format
  x-api-slug: new-relic
  description: |-
    This API endpoint deletes an application and all of its reported data.

    WARNING: Only applications that have stopped reporting can be deleted. This is an irreversible process
    which will delete all reported data for this application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/newrelic-logo-square.png
  humanURL: https://newrelic.com/
  baseURL: https:///v2///applications/{id}.{format}
  tags: Applications, , ., Format
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/new-relic/applicationsidformat-delete-openapi.md
- name: New Relic Get Applications Application  Metrics. Format
  x-api-slug: new-relic
  description: |-
    Return a list of known metrics and their value names for the given resource.

    See our documentation for a discussion
    on  output pagination
    and for examples of requesting and using metric values.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/newrelic-logo-square.png
  humanURL: https://newrelic.com/
  baseURL: https:///v2///applications/{application_id}/metrics.{format}
  tags: Applications, Application, , Metrics., Format
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/new-relic/applicationsapplication-idmetricsformat-get-openapi.md
- name: New Relic Get Applications Application  Metrics Data. Format
  x-api-slug: new-relic
  description: "This API endpoint returns a list of values for each of the requested
    metrics. The list of available metrics\ncan be returned using the Metric Name
    API endpoint.\n\nMetric data can be filtered by a number of parameters, including
    multiple names and values, and by time range.\nMetric names and values will be
    matched intelligently in the background.\n\nYou can also retrieve a summarized
    data point across the entire time range selected by using the summarize\nparameter.\n\nSee
    our documentation for a discussion on \noutput pagination,  time range \nrelated
    considerations, and for examples of requesting and using metric values."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/newrelic-logo-square.png
  humanURL: https://newrelic.com/
  baseURL: https:///v2///applications/{application_id}/metrics/data.{format}
  tags: Applications, Application, , Metrics, Data., Format
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/new-relic/applicationsapplication-idmetricsdataformat-get-openapi.md
- name: New Relic Get Browser Applications. Format
  x-api-slug: new-relic
  description: |-
    This API endpoint returns a list of the Browser Applications associated with your New Relic account.

    Browser Applications can be filtered by their name, or by the application IDs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/newrelic-logo-square.png
  humanURL: https://newrelic.com/
  baseURL: https:///v2///browser_applications.{format}
  tags: Browser, Applications., Format
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/new-relic/browser-applicationsformat-get-openapi.md
- name: New Relic Add Browser Applications. Format
  x-api-slug: new-relic
  description: This API endpoint allows you to create a standalone Browser Application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/newrelic-logo-square.png
  humanURL: https://newrelic.com/
  baseURL: https:///v2///browser_applications.{format}
  tags: Browser, Applications., Format
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/new-relic/browser-applicationsformat-post-openapi.md
- name: New Relic Get Mobile Applications. Format
  x-api-slug: new-relic
  description: |-
    This API endpoint returns a list of the Mobile Applications associated with your New Relic account.

    MobileApplications can be filtered by their name, or by the application IDs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/newrelic-logo-square.png
  humanURL: https://newrelic.com/
  baseURL: https:///v2///mobile_applications.{format}
  tags: Mobile, Applications., Format
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/new-relic/mobile-applicationsformat-get-openapi.md
- name: New Relic Get Mobile Applications  . Format
  x-api-slug: new-relic
  description: This API endpoint returns a single Mobile Application, identified by
    ID. The time range for summary data is the last 30 minutes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/newrelic-logo-square.png
  humanURL: https://newrelic.com/
  baseURL: https:///v2///mobile_applications/{id}.{format}
  tags: Mobile, Applications, , ., Format
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/new-relic/mobile-applicationsidformat-get-openapi.md
- name: New Relic Get Mobile Applications Mobile Application  Metrics. Format
  x-api-slug: new-relic
  description: |-
    Return a list of known metrics and their value names for the given resource.

    See our documentation for a discussion
    on  output pagination
    and for examples of requesting and using metric values.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/newrelic-logo-square.png
  humanURL: https://newrelic.com/
  baseURL: https:///v2///mobile_applications/{mobile_application_id}/metrics.{format}
  tags: Mobile, Applications, Mobile, Application, , Metrics., Format
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/new-relic/mobile-applicationsmobile-application-idmetricsformat-get-openapi.md
- name: New Relic Get Mobile Applications Mobile Application  Metrics Data. Format
  x-api-slug: new-relic
  description: "This API endpoint returns a list of values for each of the requested
    metrics. The list of available metrics\ncan be returned using the Metric Name
    API endpoint.\n\nMetric data can be filtered by a number of parameters, including
    multiple names and values, and by time range.\nMetric names and values will be
    matched intelligently in the background.\n\nYou can also retrieve a summarized
    data point across the entire time range selected by using the summarize\nparameter.\n\nSee
    our documentation for a discussion on \noutput pagination,  time range \nrelated
    considerations, and for examples of requesting and using metric values."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/newrelic-logo-square.png
  humanURL: https://newrelic.com/
  baseURL: https:///v2///mobile_applications/{mobile_application_id}/metrics/data.{format}
  tags: Mobile, Applications, Mobile, Application, , Metrics, Data., Format
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/new-relic/mobile-applicationsmobile-application-idmetricsdataformat-get-openapi.md
- name: New Relic
  x-api-slug: new-relic
  description: New Relic offers SaaS Software Analytics Platform that offers Application
    Performance Management and Real User Monitoring for Cloud and Data Center deployed
    web applications implemented in Ruby, Java, .NET, Python, PHP, Node.js. New Relic
    also offers mobile monitoring solutions for iOS and Android applications.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/newrelic-logo-square.png
  humanURL: https://newrelic.com/
  baseURL: https:///v2/
  tags: Applications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/applications/master/_listings/new-relic/openapi.md
x-common:
- type: x-blog
  url: https://blog.newrelic.com/
- type: x-blog-rss
  url: https://blog.newrelic.com/feed/
- type: x-developer
  url: https://rpm.newrelic.com/api/explore/
- type: x-github
  url: https://github.com/newrelic
- type: x-twitter
  url: https://twitter.com/NewRelic
- type: x-website
  url: https://newrelic.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---