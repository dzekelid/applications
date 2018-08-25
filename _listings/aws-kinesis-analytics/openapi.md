---
swagger: "2.0"
x-collection-name: AWS Kinesis Analytics
x-complete: 1
info:
  title: AWS Kinesis Analytics API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=ListApplications:
    get:
      summary: List Applications
      description: Returns a list of Amazon Kinesis Analytics applications in your
        account.
      operationId: listApplications
      x-api-path-slug: actionlistapplications-get
      responses:
        200:
          description: OK
      tags:
      - Applications
---