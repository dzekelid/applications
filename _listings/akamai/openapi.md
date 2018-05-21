---
swagger: "2.0"
x-collection-name: Akamai
x-complete: 1
info:
  title: Akamai API
  description: the-akamai-api-for-managing-your-akamai-service
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
---