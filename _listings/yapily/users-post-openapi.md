---
swagger: "2.0"
x-collection-name: Yapily
x-complete: 0
info:
  title: Yapily Add an application user
  description: Add an application user.
  version: 1.0.0
host: api.yapily.com:443
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /me:
    get:
      summary: Returns the details of the application which owns the request credentials
      description: Returns the details of the application which owns the request credentials.
      operationId: getApplicationMeUsingGET
      x-api-path-slug: me-get
      responses:
        200:
          description: OK
      tags:
      - Returns
      - Details
      - Application
      - Which
      - Owns
      - Request
      - Credentials
  /users:
    get:
      summary: Get application users
      description: Get application users.
      operationId: getUsersUsingGET
      x-api-path-slug: users-get
      responses:
        200:
          description: OK
      tags:
      - Application
      - Users
    post:
      summary: Add an application user
      description: Add an application user.
      operationId: addUserUsingPOST
      x-api-path-slug: users-post
      parameters:
      - in: body
        name: applicationUser
        description: applicationUser
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Application
      - User
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