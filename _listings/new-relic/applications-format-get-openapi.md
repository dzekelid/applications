---
swagger: "2.0"
x-collection-name: New Relic
x-complete: 0
info:
  title: New Relic Get Applications. Format
  version: 1.0.0
  description: "This API endpoint returns a paginated\nlist of the Applications associated
    with your New Relic account. The time range for summary data is the last 10 minutes.\n\nApplications
    can be filtered by their name, hosts, the list of application IDs or the application
    language as\nreported by the agents.\n\nSee our documentation for a discussion
    and examples of\nusing  filters \nand summary data output."
basePath: v2/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /applications.{format}:
    get:
      summary: Get Applications. Format
      description: "This API endpoint returns a paginated\nlist of the Applications
        associated with your New Relic account. The time range for summary data is
        the last 10 minutes.\n\nApplications can be filtered by their name, hosts,
        the list of application IDs or the application language as\nreported by the
        agents.\n\nSee our documentation for a discussion and examples of\nusing  filters
        \nand summary data output."
      operationId: getApplications.Format
      x-api-path-slug: applications-format-get
      parameters:
      - in: query
        name: filter[host]
        description: Filter by application host
        type: string
      - in: query
        name: filter[ids]
        description: Filter by application ids
        type: list
      - in: query
        name: filter[language]
        description: Filter by application language
        type: string
      - in: query
        name: filter[name]
        description: Filter by application name
        type: string
      - in: query
        name: page
        description: Pagination index
        type: integer
      responses:
        200:
          description: OK
      tags:
      - Applications.
      - Format
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