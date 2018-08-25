---
swagger: "2.0"
x-collection-name: AWS Elastic Beanstalk
x-complete: 1
info:
  title: AWS Elastic Beanstalk API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeApplications:
    get:
      summary: Describe Applications
      description: Returns the descriptions of existing applications.
      operationId: describeApplications
      x-api-path-slug: actiondescribeapplications-get
      parameters:
      - in: query
        name: ApplicationNames.member.N
        description: If specified, AWS Elastic Beanstalk restricts the returned descriptions
          to only include      those with the specified names
        type: string
      responses:
        200:
          description: OK
      tags:
      - Applications
---