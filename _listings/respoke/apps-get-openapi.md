---
swagger: "2.0"
x-collection-name: Respoke
x-complete: 0
info:
  title: Respoke Apps
  description: Create an app.
  termsOfService: https://www.respoke.io/files/respoke-tos-20141007.pdf
  version: v1
host: api.respoke.io
basePath: v1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  apps/:
    get:
      summary: Apps
      description: Create an app.
      operationId: getApps
      x-api-path-slug: apps-get
      parameters:
      - in: header
        name: Admin-Token
        description: Your admin token
      responses:
        200:
          description: OK
      tags:
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