---
swagger: "2.0"
x-collection-name: Akamai
x-complete: 0
info:
  title: Akamai API Modify an Application
  description: Modify an Application
  version: 1.0.0
host: developer.akamai.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /config-saas-registration/v1/applications/:
    get:
      summary: List Applications
      description: List Applications
      operationId: configsaasregistrationv1applicationscontractid
      x-api-path-slug: configsaasregistrationv1applications-get
      parameters:
      - in: query
        name: contractId
        description: such as A-1234
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Saas
      - Registration
      - Applications
      - Contract
    post:
      summary: Create a New Application
      description: Create a New Application
      operationId: configsaasregistrationv1applicationscontractid
      x-api-path-slug: configsaasregistrationv1applications-post
      parameters:
      - in: query
        name: contractId
        description: such as A-1234
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Saas
      - Registration
      - Applications
      - Contract
  /config-saas-registration/v1/applications/{surrogateId}/:
    get:
      summary: Get an Application
      description: Get an Application
      operationId: configsaasregistrationv1applicationssurrogateidcontractid
      x-api-path-slug: configsaasregistrationv1applicationssurrogateid-get
      parameters:
      - in: query
        name: contractId
        description: such as A-1234
        type: string
      - in: query
        name: surrogateId
        description: such as 123
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Saas
      - Registration
      - Applications
      - Surrogate
      - Contract
    delete:
      summary: Remove an Application
      description: Remove an Application
      operationId: configsaasregistrationv1applicationssurrogateidcontractid
      x-api-path-slug: configsaasregistrationv1applicationssurrogateid-delete
      parameters:
      - in: query
        name: contractId
        description: such as A-1234
        type: string
      - in: query
        name: surrogateId
        description: such as 123
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Saas
      - Registration
      - Applications
      - Surrogate
      - Contract
    put:
      summary: Modify an Application
      description: Modify an Application
      operationId: configsaasregistrationv1applicationssurrogateidcontractid
      x-api-path-slug: configsaasregistrationv1applicationssurrogateid-put
      parameters:
      - in: query
        name: contractId
        description: such as A-1234
        type: string
      - in: query
        name: surrogateId
        description: such as 123
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Saas
      - Registration
      - Applications
      - Surrogate
      - Contract
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