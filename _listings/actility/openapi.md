swagger: "2.0"
x-collection-name: Actility
x-complete: 1
info:
  title: ThingPark DX Maker API
  description: api-providing-features-for-device-makers-such-as-preprovisioning-on-standalone-join-servers-
  version: 1.0.0
host: dx-api.thingpark.com
basePath: /maker/v011/api
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