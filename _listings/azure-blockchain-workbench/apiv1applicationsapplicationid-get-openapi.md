---
swagger: "2.0"
x-collection-name: Azure Blockchain Workbench
x-complete: 0
info:
  title: Azure Blockchain Workbench Get Applications
  description: |-
    Gets the blockchain application matching a specific application ID. Users who are Workbench administrators get
                 the blockchain application. Non-Workbench administrators get the blockchain application if they have at least one associated
                 application role or is associated with a smart contract instance role.
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/checkers/checkApplication:
    post:
      summary: Post Checkers Check Application
      description: Checks if the supplied application configuration file is valid
        for Workbench.
      operationId: CheckApplicationPost
      x-api-path-slug: apiv1checkerscheckapplication-post
      parameters:
      - in: formData
        name: appFile
        description: Upload Application File
      responses:
        200:
          description: OK
      tags:
      - Checkers
      - Check
      - Application
  /api/v1/applications:
    get:
      summary: Get Applications
      description: |-
        Lists all blockchain applications to which a user has access in Workbench. Users who are Workbench administrators get
                     all blockchain applications. Non-Workbench administrators get all blockchain applications for which they have at least one
                     associated application role or an associated smart contract instance role.
      operationId: ApplicationsGet
      x-api-path-slug: apiv1applications-get
      parameters:
      - in: query
        name: enabled
        description: A Boolean for whether to filter the result set to only enabled
          applications
      - in: query
        name: skip
        description: The number of entries to skip in the result set
      - in: query
        name: sortBy
        description: The field to sort
      - in: query
        name: top
        description: The maximum number of entries to return in the result set
      responses:
        200:
          description: OK
      tags:
      - Applications
    post:
      summary: Post Applications
      description: |-
        Creates a new blockchain application. This method can only be performed by users who are
                     Workbench administrators.
      operationId: ApplicationsPost
      x-api-path-slug: apiv1applications-post
      parameters:
      - in: formData
        name: appFile
        description: Upload Application File
      responses:
        200:
          description: OK
      tags:
      - Applications
  /api/v1/applications/contractCode/{contractCodeId}:
    get:
      summary: Get Applications Contract Code
      description: |-
        Get the blockchain smart contract implementation matching a specific
                     contract code id. Users who are Workbench administrators get the specified smart contract implementation.
                     Non-Workbench administrators get the smart contract implementation if they have at least one associated application
                     role or is associated with a smart contract instance role.
      operationId: ContractCodeGet
      x-api-path-slug: apiv1applicationscontractcodecontractcodeid-get
      parameters:
      - in: path
        name: contractCodeId
        description: The id of the contract code
      responses:
        200:
          description: OK
      tags:
      - Applications
      - Contract
      - Code
    delete:
      summary: Delete Applications Contract Code
      description: |-
        Deletes the specified blockchain smart contract implementation of a specific blockchain application.
                     This method can only be performed by users who are Workbench administrators.
                     NOTE: not currently implemented
      operationId: ContractCodeDelete
      x-api-path-slug: apiv1applicationscontractcodecontractcodeid-delete
      parameters:
      - in: path
        name: contractCodeId
        description: The id of the contract code
      responses:
        200:
          description: OK
      tags:
      - Applications
      - Contract
      - Code
  /api/v1/applications/workflows/{workflowId}:
    get:
      summary: Get Applications Workflows
      description: |-
        Get a workflow matching a specific workflow ID.
                     Users who are Workbench administrators get the workflow. Non-Workbench administrators get the workflow if they
                     have at least one associated application role or is associated with a smart contract instance role.
      operationId: WorkflowGet
      x-api-path-slug: apiv1applicationsworkflowsworkflowid-get
      parameters:
      - in: path
        name: workflowId
        description: The id of the workflow
      responses:
        200:
          description: OK
      tags:
      - Applications
      - Workflows
  /api/v1/applications/{applicationId}:
    get:
      summary: Get Applications
      description: |-
        Gets the blockchain application matching a specific application ID. Users who are Workbench administrators get
                     the blockchain application. Non-Workbench administrators get the blockchain application if they have at least one associated
                     application role or is associated with a smart contract instance role.
      operationId: ApplicationGet
      x-api-path-slug: apiv1applicationsapplicationid-get
      parameters:
      - in: path
        name: applicationId
        description: The id of the application
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