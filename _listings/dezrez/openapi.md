---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 1
info:
  title: Dezrez.Rezi.Client.Api
  version: 1.0.0
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/tenantreferncing/application/{applicationId}/referencingresult:
    get:
      summary: Get the details of an individual application referencing result
      description: Get the details of an individual application referencing result.
      operationId: TenantReferencing_GetApplicationStatusByapplicationId
      x-api-path-slug: apitenantreferncingapplicationapplicationidreferencingresult-get
      parameters:
      - in: path
        name: applicationId
        description: The id of the application to retrieve results for
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Details
      - Of
      - Individual
      - Application
      - Referencing
      - Result
---