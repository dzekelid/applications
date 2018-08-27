---
swagger: "2.0"
x-collection-name: Heroku
x-complete: 0
info:
  title: Heroku Delete Application Collaborators Email
  description: Delete application collaborators email.
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
    put:
      summary: Put Application Addons
      description: Upgrade an addon to an app.
      operationId: putAppsAppAddonsAddon
      x-api-path-slug: appsappaddonsaddon-put
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
      - Put
      - Application
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
  /apps/{app}/collaborators:
    parameters:
      summary: Parameters Application Collaborators
      description: Parameters application collaborators.
      operationId: parametersAppsAppCollaborators
      x-api-path-slug: appsappcollaborators-parameters
      responses:
        200:
          description: OK
      tags:
      - Parameters
      - Application
      - Collaborators
    get:
      summary: Get Application Collaborators
      description: List collaborators for an app.
      operationId: getAppsAppCollaborators
      x-api-path-slug: appsappcollaborators-get
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
      - Collaborators
  /apps/{app}/collaborators/{email}:
    parameters:
      summary: Parameters Application Collaborators Email
      description: Parameters application collaborators email.
      operationId: parametersAppsAppCollaboratorsEmail
      x-api-path-slug: appsappcollaboratorsemail-parameters
      responses:
        200:
          description: OK
      tags:
      - Parameters
      - Application
      - Collaborators
      - Email
    delete:
      summary: Delete Application Collaborators Email
      description: Delete application collaborators email.
      operationId: deleteAppsAppCollaboratorsEmail
      x-api-path-slug: appsappcollaboratorsemail-delete
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
      - in: query
        name: email
        description: The email of the user to remove as a collaborator
      - in: path
        name: email
      responses:
        200:
          description: OK
      tags:
      - Application
      - Collaborators
      - Email
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