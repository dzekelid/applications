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
      - Describe
      - Apps
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