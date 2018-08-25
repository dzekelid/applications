---
swagger: "2.0"
x-collection-name: Predix
x-complete: 0
info:
  title: Predix AppHub ARCS Get all the registered microapps
  description: Get the registered microapps for the given tenant
  termsOfService: Terms of service
  contact:
    name: 'Digital Predix AppHub ARCS: Development'
  version: 1.0.0
host: predix-apphub-arcs-prod.run.aws-usw02-pr.ice.predix.io
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /apps:
    get:
      summary: Get all the registered microapps
      description: Get the registered microapps for the given tenant
      operationId: getAllRegisteredAppsUsingGET
      x-api-path-slug: apps-get
      responses:
        200:
          description: OK
      tags:
      - Apps
    post:
      summary: Register the microapp
      description: Register the microapps
      operationId: registerAppUsingPOST
      x-api-path-slug: apps-post
      parameters:
      - in: body
        name: request
        description: request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Apps
    put:
      summary: Update the microapp
      description: Update the microapps
      operationId: updateAppUsingPUT
      x-api-path-slug: apps-put
      parameters:
      - in: body
        name: request
        description: request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Apps
  /apps/{uuid}:
    get:
      summary: Get the registered microapp
      description: Get the registered microapp for the given uri
      operationId: getRegisterAppUsingGET
      x-api-path-slug: appsuuid-get
      parameters:
      - in: path
        name: uuid
        description: uuid
      responses:
        200:
          description: OK
      tags:
      - Apps
      - Uuid
    delete:
      summary: Unregister the microapp
      description: Unregister the microapp
      operationId: unRegisterAppUsingDELETE
      x-api-path-slug: appsuuid-delete
      parameters:
      - in: path
        name: uuid
        description: uuid
      responses:
        200:
          description: OK
      tags:
      - Apps
      - Uuid
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