---
swagger: "2.0"
x-collection-name: AWS Simple Notification Service
x-complete: 1
info:
  title: AWS Simple Notification Service API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=ListPlatformApplications:
    get:
      summary: List Platform Applications
      description: |-
        Lists the platform application objects for the supported push notification services, such as
              APNS and GCM.
      operationId: listPlatformApplications
      x-api-path-slug: actionlistplatformapplications-get
      parameters:
      - in: query
        name: NextToken
        description: NextToken string is used when calling ListPlatformApplications
          action to retrieve additional records that are available after the first
          page results
        type: string
      responses:
        200:
          description: OK
      tags:
      - Platform Applications
---