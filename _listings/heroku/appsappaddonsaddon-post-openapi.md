---
swagger: "2.0"
x-collection-name: Heroku
x-complete: 0
info:
  title: Heroku Add Application Addons
  description: Install an addon to an app.
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
  /apps/{app}/addons:
    parameters:
      summary: Parameter Application Addons
      description: Parameter application addons.
      operationId: parametersAppsAppAddons
      x-api-path-slug: appsappaddons-parameters
      responses:
        200:
          description: OK
      tags:
      - Parameter
      - Application
      - ons
    get:
      summary: Get Application Addons
      description: List addons installed on an app.
      operationId: getAppsAppAddons
      x-api-path-slug: appsappaddons-get
      parameters:
      - in: header
        name: Accept
        description: Content type
      - in: query
        name: Accept
        description: Content type
      - in: query
        name: app
        description: The app name
      - in: path
        name: app
      responses:
        200:
          description: OK
      tags:
      - Application
      - ons
  /apps/{app}/addons/{addon}:
    post:
      summary: Add Application Addons
      description: Install an addon to an app.
      operationId: postAppsAppAddonsAddon
      x-api-path-slug: appsappaddonsaddon-post
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
      - Application
      - ons
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