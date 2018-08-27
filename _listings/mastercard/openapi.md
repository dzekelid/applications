swagger: "2.0"
x-collection-name: MasterCard
x-complete: 1
info:
  title: MasterCard
  description: as-a-technology-company-in-the-global-payments-business-we-operate-the-worlds-fastest-payments-processing-network-connecting-consumers-financial-institutions-merchants-governments-and-businesses-in-more-than-210-countries-and-territories--mastercards-products-and-solutions-make-everyday-commerce-activities--such-as-shopping-traveling-running-a-business-and-managing-finances--easier-more-secure-and-more-efficient-for-everyone-
  version: 1.0.0
host: eas5stl0.mastercard.int:13046
basePath: /z0/core/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /app/{id}:
    get:
      summary: Get App
      description: |-
        Information about an application referenced by the `id` parameter. If
        you are permissioned to that application, this will also return the
        message definitions you will need to comply with to issue valid transaction
        entries for that application.
      operationId: getApp
      x-api-path-slug: appid-get
      parameters:
      - in: path
        name: id
      - in: header
        name: MCWSSAML
        description: SAML Authorization
      responses:
        200:
          description: OK
      tags:
      - Blockchain
      - App
    post:
      summary: Add App
      description: |-
        When you are permissioned onto the network, you will be issued one or
        more `id`s to use. You may then send or update configurations of the
        transaction message types you wish to use. These are specified using
        Protocol Buffer version 3 files as specified
        [here](https://developers.google.com/protocol-buffers/docs/proto3)
        This specification may be sent either as the canonical JSON transform
        or the native `.proto` file encoded as hex, base58 or base64.
      operationId: postApp
      x-api-path-slug: appid-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: header
        name: MCWSSAML
        description: SAML Authorization
      responses:
        200:
          description: OK
      tags:
      - Blockchain
      - App