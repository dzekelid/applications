---
swagger: "2.0"
x-collection-name: AWS CodeDeploy
x-complete: 1
info:
  title: AWS CodeDeploy API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=BatchGetApplications:
    get:
      summary: Batch Get Applications
      description: Gets information about one or more applications.
      operationId: batchGetApplications
      x-api-path-slug: actionbatchgetapplications-get
      parameters:
      - in: query
        name: applicationNames
        description: A list of application names separated by spaces
        type: string
      responses:
        200:
          description: OK
      tags:
      - Applications
  /?Action=ListApplications:
    get:
      summary: List Applications
      description: |-
        Lists the applications registered with the applicable IAM user or AWS
                    account.
      operationId: listApplications
      x-api-path-slug: actionlistapplications-get
      parameters:
      - in: query
        name: nextToken
        description: An identifier returned from the previous list applications call
        type: string
      responses:
        200:
          description: OK
      tags:
      - Applications
---