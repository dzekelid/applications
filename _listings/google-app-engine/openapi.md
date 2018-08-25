---
swagger: "2.0"
x-collection-name: Google App Engine
x-complete: 1
info:
  title: Google App Engine Admin
  description: provisions-and-manages-app-engine-applications-
  contact:
    name: Google
    url: https://google.com
  version: v1
host: appengine.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/apps/{appsId}:repair:
    post:
      summary: Repair App
      description: Recreates the required App Engine features for the specified App
        Engine application, for example a Cloud Storage bucket or App Engine service
        account. Use this method if you receive an error message about a missing feature,
        for example, Error retrieving the App Engine service account.
      operationId: appengine.apps.repair
      x-api-path-slug: v1appsappsidrepair-post
      parameters:
      - in: path
        name: appsId
        description: Part of `name`
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - App
---