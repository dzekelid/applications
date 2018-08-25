---
swagger: "2.0"
x-collection-name: Heroku
x-complete: 1
info:
  title: Heroku
  description: manage-your-heroku-apps-configs-collaborators--resources
  version: "1"
host: api.heroku.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /apps:
    parameters:
      summary: Parameters Applications
      description: Parameters applications.
      operationId: parametersApps
      x-api-path-slug: apps-parameters
      responses:
        200:
          description: OK
      tags:
      - Parameters
      - Applications
    get:
      summary: Get Applications
      description: Get applications.
      operationId: getApps
      x-api-path-slug: apps-get
      parameters:
      - in: header
        name: Accept
        description: Content type
      - in: query
        name: Accept
        description: Content type
      responses:
        200:
          description: OK
      tags:
      - Applications
    post:
      summary: Add Applications
      description: Add applications.
      operationId: postApps
      x-api-path-slug: apps-post
      parameters:
      - in: header
        name: Accept
        description: Content type
      - in: query
        name: Accept
        description: Content type
      responses:
        200:
          description: OK
      tags:
      - Applications
  /apps/{app}/addons/{addon}:
    parameters:
      summary: Parameters Applications Addons
      description: Parameters applications addons.
      operationId: parametersAppsAppAddonsAddon
      x-api-path-slug: appsappaddonsaddon-parameters
      responses:
        200:
          description: OK
      tags:
      - Parameters
      - Applications
      - ons
    delete:
      summary: Delete Applications Addons
      description: Uninstall an addon from an app.
      operationId: deleteAppsAppAddonsAddon
      x-api-path-slug: appsappaddonsaddon-delete
      parameters:
      - in: header
        name: Accept
        description: Content type
      - in: query
        name: Accept
        description: Content type
      - in: query
        name: addon
        description: the addon name
      - in: path
        name: addon
      - in: query
        name: app
        description: The app name
      - in: path
        name: app
      responses:
        200:
          description: OK
      tags:
      - Applications
      - ons
  /apps/{name}:
    parameters:
      summary: Parameters Applications Name
      description: Parameters applications name.
      operationId: parametersAppsName
      x-api-path-slug: appsname-parameters
      responses:
        200:
          description: OK
      tags:
      - Parameters
      - Applications
      - Name
    get:
      summary: Get Applications Name
      description: Get applications name.
      operationId: getAppsName
      x-api-path-slug: appsname-get
      parameters:
      - in: query
        name: Accept
        description: Content type
      - in: header
        name: Accept
        description: Content type
      - in: query
        name: name
        description: The app name
      - in: path
        name: name
      responses:
        200:
          description: OK
      tags:
      - Applications
      - Name
    delete:
      summary: Delete Applications Name
      description: Delete applications name.
      operationId: deleteAppsName
      x-api-path-slug: appsname-delete
      parameters:
      - in: query
        name: Accept
        description: Content type
      - in: header
        name: Accept
        description: Content type
      - in: query
        name: name
        description: The app name
      - in: path
        name: name
      responses:
        200:
          description: OK
      tags:
      - Applications
      - Name
---