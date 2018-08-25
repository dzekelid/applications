---
swagger: "2.0"
x-collection-name: Yapily
x-complete: 1
info:
  title: Yapily API
  description: to-access-endpoints-that-require-authentication-use-your-application-key-and-secret-created-in-the-dashboard-httpsdashboard-yapily-com
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
  /users/{uuid}:
    get:
      summary: Get an application user
      description: Get an application user.
      operationId: getUserUsingGET
      x-api-path-slug: usersuuid-get
      parameters:
      - in: path
        name: uuid
        description: uuid
      responses:
        200:
          description: OK
      tags:
      - Application
      - User
    put:
      summary: Update an application user
      description: Update an application user.
      operationId: updateUserUsingPUT
      x-api-path-slug: usersuuid-put
      parameters:
      - in: body
        name: applicationUser
        description: applicationUser
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: uuid
        description: uuid
      responses:
        200:
          description: OK
      tags:
      - Application
      - User
---