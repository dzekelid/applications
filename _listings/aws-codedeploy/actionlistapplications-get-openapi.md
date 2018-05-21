---
swagger: "2.0"
x-collection-name: AWS CodeDeploy
x-complete: 0
info:
  title: AWS CodeDeploy API List Applications
  version: 1.0.0
  description: |-
    Lists the applications registered with the applicable IAM user or AWS
                account.
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
  /?Action=CreateApplication:
    get:
      summary: Create Application
      description: Creates an application.
      operationId: createApplication
      x-api-path-slug: actioncreateapplication-get
      parameters:
      - in: query
        name: applicationName
        description: The name of the application
        type: string
      responses:
        200:
          description: OK
      tags:
      - Applications
  /?Action=DeleteApplication:
    get:
      summary: Delete Application
      description: Deletes an application.
      operationId: deleteApplication
      x-api-path-slug: actiondeleteapplication-get
      parameters:
      - in: query
        name: applicationName
        description: The name of an AWS CodeDeploy application associated with the
          applicable IAM user            or AWS account
        type: string
      responses:
        200:
          description: OK
      tags:
      - Applications
  /?Action=GetApplication:
    get:
      summary: Get Application
      description: Gets information about an application.
      operationId: getApplication
      x-api-path-slug: actiongetapplication-get
      parameters:
      - in: query
        name: applicationName
        description: The name of an AWS CodeDeploy application associated with the
          applicable IAM user            or AWS account
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