---
swagger: "2.0"
x-collection-name: Predix
x-complete: 0
info:
  title: Predix AppHub ARCS Get the registered microapp
  description: Get the registered microapp for the given uri
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
  /v1/resource/{resourceIdentifier}:
    get:
      summary: Retrieves the resource for the given zone. The resourceIdentifier must
        be URL encoded in application/x-www-form-urlencoded format with UTF-8.
      description: Retrieves the resource for the given zone. the resourceidentifier
        must be url encoded in application/x-www-form-urlencoded format with utf-8..
      operationId: getResourceV1UsingGET
      x-api-path-slug: v1resourceresourceidentifier-get
      parameters:
      - in: query
        name: includeInheritedAttributes
        description: includeInheritedAttributes
      - in: path
        name: resourceIdentifier
        description: resourceIdentifier
      responses:
        200:
          description: Successful response
      tags:
      - Retrieves
      - Resourcethe
      - Given
      - Zone
      - ""
      - ResourceIdentifier
      - Must
      - Be
      - URL
      - Encoded
      - In
      - Application
      - X-www-form-urlencoded
      - Format
      - UTF-8
    put:
      summary: Creates/Updates a given resource for a given zone. The resourceIdentifier
        must be URL encoded in application/x-www-form-urlencoded format with UTF-8.
      description: Creates/updates a given resource for a given zone. the resourceidentifier
        must be url encoded in application/x-www-form-urlencoded format with utf-8..
      operationId: putResourceV1UsingPUT_1
      x-api-path-slug: v1resourceresourceidentifier-put
      parameters:
      - in: body
        name: resource
        description: resource
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceIdentifier
        description: resourceIdentifier
      responses:
        200:
          description: Successful response
      tags:
      - Creates
      - S
      - Given
      - Resourcea
      - Given
      - Zone
      - ""
      - ResourceIdentifier
      - Must
      - Be
      - URL
      - Encoded
      - In
      - Application
      - X-www-form-urlencoded
      - Format
      - UTF-8
    delete:
      summary: Deletes the resource for a given zone. The resourceIdentifier must
        be URL encoded in application/x-www-form-urlencoded format with UTF-8.
      description: Deletes the resource for a given zone. the resourceidentifier must
        be url encoded in application/x-www-form-urlencoded format with utf-8..
      operationId: deleteResourceV1UsingDELETE
      x-api-path-slug: v1resourceresourceidentifier-delete
      parameters:
      - in: path
        name: resourceIdentifier
        description: resourceIdentifier
      responses:
        200:
          description: Successful response
      tags:
      - S
      - Resourcea
      - Given
      - Zone
      - ""
      - ResourceIdentifier
      - Must
      - Be
      - URL
      - Encoded
      - In
      - Application
      - X-www-form-urlencoded
      - Format
      - UTF-8
  /v1/subject/{subjectIdentifier}:
    get:
      summary: Retrieves the subject for the given zone. The subjectIdentifier must
        be URL encoded in application/x-www-form-urlencoded format with UTF-8.
      description: Retrieves the subject for the given zone. the subjectidentifier
        must be url encoded in application/x-www-form-urlencoded format with utf-8..
      operationId: getSubjectUsingGET
      x-api-path-slug: v1subjectsubjectidentifier-get
      parameters:
      - in: query
        name: includeInheritedAttributes
        description: includeInheritedAttributes
      - in: path
        name: subjectIdentifier
        description: subjectIdentifier
      responses:
        200:
          description: Successful response
      tags:
      - Retrieves
      - Subjectthe
      - Given
      - Zone
      - ""
      - SubjectIdentifier
      - Must
      - Be
      - URL
      - Encoded
      - In
      - Application
      - X-www-form-urlencoded
      - Format
      - UTF-8
    delete:
      summary: Deletes the subject for a given zone. The subjectIdentifier must be
        URL encoded in application/x-www-form-urlencoded format with UTF-8.
      description: Deletes the subject for a given zone. the subjectidentifier must
        be url encoded in application/x-www-form-urlencoded format with utf-8..
      operationId: deleteSubjectUsingDELETE_1
      x-api-path-slug: v1subjectsubjectidentifier-delete
      parameters:
      - in: path
        name: subjectIdentifier
        description: subjectIdentifier
      responses:
        200:
          description: Successful response
      tags:
      - S
      - Subjecta
      - Given
      - Zone
      - ""
      - SubjectIdentifier
      - Must
      - Be
      - URL
      - Encoded
      - In
      - Application
      - X-www-form-urlencoded
      - Format
      - UTF-8
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