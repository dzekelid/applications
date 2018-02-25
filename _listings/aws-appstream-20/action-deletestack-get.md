---
swagger: "2.0"
info:
  title: AWS AppStream 2.0 API
  description: Amazon AppStream 2.0 is a fully managed, secure application streaming
    service that allows you to stream desktop applications from AWS to any device
    running a web browser, without rewriting them. Amazon AppStream 2.0 provides users
    instant-on access to the applications they need, and a responsive, fluid user
    experience on the device of their choice.
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DeleteStack&k=1:
    get:
      summary: Delete Stack
      description: Deletes the stack
      operationId: DeleteStack
      parameters:
      - in: query
        name: Name
        description: The name of the stack to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - stack
definitions: []
x-collection-name: AWS AppStream 2.0
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