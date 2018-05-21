---
swagger: "2.0"
x-collection-name: AWS OpsWorks
x-complete: 0
info:
  title: AWS OpsWorks API Describe Apps
  version: 1.0.0
  description: Requests a description of a specified set of apps.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateApp:
    get:
      summary: Create App
      description: Creates an app for a specified stack.
      operationId: createApp
      x-api-path-slug: actioncreateapp-get
      parameters:
      - in: query
        name: AppSource
        description: A Source object that specifies the app repository
        type: string
      - in: query
        name: Attributes
        description: One or more user-defined key/value pairs to be added to the stack
          attributes
        type: string
      - in: query
        name: DataSources
        description: The apps data source
        type: string
      - in: query
        name: Description
        description: A description of the app
        type: string
      - in: query
        name: Domains
        description: The app virtual host settings, with multiple domains separated
          by commas
        type: string
      - in: query
        name: EnableSsl
        description: Whether to enable SSL for the app
        type: string
      - in: query
        name: Environment
        description: An array of EnvironmentVariable objects that specify environment
          variables to be      associated with the app
        type: string
      - in: query
        name: Name
        description: The app name
        type: string
      - in: query
        name: Shortname
        description: The apps short name
        type: string
      - in: query
        name: SslConfiguration
        description: An SslConfiguration object with the SSL configuration
        type: string
      - in: query
        name: StackId
        description: The stack ID
        type: string
      - in: query
        name: Type
        description: The app type
        type: string
      responses:
        200:
          description: OK
      tags:
      - Applications
  /?Action=DeleteApp:
    get:
      summary: Delete App
      description: Deletes a specified app.
      operationId: deleteApp
      x-api-path-slug: actiondeleteapp-get
      parameters:
      - in: query
        name: AppId
        description: The app ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Applications
  /?Action=DescribeApps:
    get:
      summary: Describe Apps
      description: Requests a description of a specified set of apps.
      operationId: describeApps
      x-api-path-slug: actiondescribeapps-get
      parameters:
      - in: query
        name: AppIds
        description: An array of app IDs for the apps to be described
        type: string
      - in: query
        name: StackId
        description: The app stack ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Applications
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