---
swagger: "2.0"
x-collection-name: AWS OpsWorks
x-complete: 1
info:
  title: AWS OpsWorks API
  version: 1.0.0
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
---