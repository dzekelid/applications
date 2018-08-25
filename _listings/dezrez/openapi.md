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
  /api/tenantreferncing/addapplication/{caseId}/{tenancyRoleId}/{personId}/{productId}:
    post:
      summary: Creates a tenancy referencing application for a case using the details
        supplied
      description: Creates a tenancy referencing application for a case using the
        details supplied.
      operationId: TenantReferencing_CreateApplicationBycaseIdBytenancyRoleIdBypersonIdByproductId
      x-api-path-slug: apitenantreferncingaddapplicationcaseidtenancyroleidpersonidproductid-post
      parameters:
      - in: path
        name: caseId
        description: The id of the case to add the Application to
      - in: path
        name: personId
        description: The id of the individual the application is for
      - in: path
        name: productId
        description: The id of the product the client has chosen
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: tenancyRoleId
        description: The role id of the tenancy the case is linked to
      responses:
        200:
          description: OK
      tags:
      - Creates
      - Tenancy
      - Referencing
      - Applicationa
      - Case
      - Using
      - Details
      - Supplied
  /api/tenantreferncing/addguarantor/{caseId}/{tenancyRoleId}/{personId}:
    post:
      summary: Adds a Guarantor to a tenancy referencing application for a case using
        the details supplied
      description: Adds a guarantor to a tenancy referencing application for a case
        using the details supplied.
      operationId: TenantReferencing_CreateApplicationBycaseIdBytenancyRoleIdBypersonId
      x-api-path-slug: apitenantreferncingaddguarantorcaseidtenancyroleidpersonid-post
      parameters:
      - in: path
        name: caseId
        description: The id of the case to add the Guarantor to
      - in: path
        name: personId
        description: The id of the individual the application is for
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: tenancyRoleId
        description: The role id of the tenancy the case is linked to
      responses:
        200:
          description: OK
      tags:
      - S
      - Guarantor
      - To
      - Tenancy
      - Referencing
      - Applicationa
      - Case
      - Using
      - Details
      - Supplied
  /api/tenantreferncing/submitapplication/{caseId}:
    put:
      summary: Submits an individual referencing application for processing
      description: Submits an individual referencing application for processing.
      operationId: TenantReferencing_SubmitApplicationForReferencingBycaseId
      x-api-path-slug: apitenantreferncingsubmitapplicationcaseid-put
      parameters:
      - in: path
        name: caseId
        description: The id of the case to submit the application for
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Submits
      - Individual
      - Referencing
      - Applicationprocessing
  /api/tenantreferncing/applications/{caseId}:
    get:
      summary: Gets all tenancy referencing applications for the caseId provided
      description: Gets all tenancy referencing applications for the caseid provided.
      operationId: TenantReferencing_GetApplicationsBycaseId
      x-api-path-slug: apitenantreferncingapplicationscaseid-get
      parameters:
      - in: path
        name: caseId
        description: The id of the case to get applications from
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - S
      - ""
      - Tenancy
      - Referencing
      - Applicationsthe
      - CaseId
      - Provided
---