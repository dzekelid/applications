---
swagger: "2.0"
x-collection-name: MasterCard
x-complete: 0
info:
  title: Mastercard Add App
  description: |-
    When you are permissioned onto the network, you will be issued one or
    more `id`s to use. You may then send or update configurations of the
    transaction message types you wish to use. These are specified using
    Protocol Buffer version 3 files as specified
    [here](https://developers.google.com/protocol-buffers/docs/proto3)
    This specification may be sent either as the canonical JSON transform
    or the native `.proto` file encoded as hex, base58 or base64.
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