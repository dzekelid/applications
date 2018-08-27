swagger: "2.0"
x-collection-name: Respoke
x-complete: 1
info:
  title: Respoke REST API
  description: add-live-voice-video-text-and-data-features-to-your-website-or-app-
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