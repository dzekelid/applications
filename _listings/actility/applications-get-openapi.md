---
swagger: "2.0"
x-collection-name: Actility
x-complete: 0
info:
  title: ThingPark DX Core API Applications retrieval
  description: Retrieves a list of applications existing within authorized scopes.
    In case of an operator or a vendor scope, it retrieves all applications available.
    In case of a subscriber scope, it retrieves all applications within subscribed
    offers. In case of a supplier scope, it retrieves all applications provided by
    that supplier.
  version: 1.0.0
host: dx-api.thingpark.com
basePath: /core/v141/api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /applications:
    get:
      summary: Applications retrieval
      description: Retrieves a list of applications existing within authorized scopes.
        In case of an operator or a vendor scope, it retrieves all applications available.
        In case of a subscriber scope, it retrieves all applications within subscribed
        offers. In case of a supplier scope, it retrieves all applications provided
        by that supplier.
      operationId: retrieves-a-list-of-applications-existing-within-authorized-scopes-in-case-of-an-operator-or-a-vendo
      x-api-path-slug: applications-get
      parameters:
      - in: query
        name: applicationId
        description: Id of the application to search for
      responses:
        200:
          description: OK
      tags:
      - Applications
      - Retrieval
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