---
swagger: "2.0"
x-collection-name: AWS Simple Notification Service
x-complete: 0
info:
  title: AWS Simple Notification Service API List Platform Applications
  version: 1.0.0
  description: |-
    Lists the platform application objects for the supported push notification services, such as
          APNS and GCM.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreatePlatformApplication:
    get:
      summary: Create Platform Application
      description: |-
        Creates a platform application object for one of the supported push notification services,
              such as APNS and GCM, to which devices and mobile apps may register.
      operationId: createPlatformApplication
      x-api-path-slug: actioncreateplatformapplication-get
      parameters:
      - in: query
        name: |-
          Attributes
                      , Attributes.entry.N.key (key), Attributesentry.N.value (value)
        description: For a list of attributes, see SetPlatformApplicationAttributes
        type: string
      - in: query
        name: Name
        description: Application names must be made up of only uppercase and lowercase
          ASCII letters, numbers, underscores, hyphens, and periods, and must be between
          1 and 256 characters long
        type: string
      - in: query
        name: Platform
        description: 'The following platforms are supported: ADM (Amazon Device Messaging),
          APNS (Apple Push Notification Service), APNS_SANDBOX, and GCM (Google Cloud
          Messaging)'
        type: string
      responses:
        200:
          description: OK
      tags:
      - Platform Applications
  /?Action=DeletePlatformApplication:
    get:
      summary: Delete Platform Application
      description: |-
        Deletes a platform application object for one of the supported push notification services,
              such as APNS and GCM.
      operationId: deletePlatformApplication
      x-api-path-slug: actiondeleteplatformapplication-get
      parameters:
      - in: query
        name: PlatformApplicationArn
        description: PlatformApplicationArn of platform application object to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Platform Applications
  /?Action=GetPlatformApplicationAttributes:
    get:
      summary: Get Platform Application Attributes
      description: |-
        Retrieves the attributes of the platform application object for the supported push
              notification services, such as APNS and GCM.
      operationId: getPlatformApplicationAttributes
      x-api-path-slug: actiongetplatformapplicationattributes-get
      parameters:
      - in: query
        name: PlatformApplicationArn
        description: PlatformApplicationArn for GetPlatformApplicationAttributesInput
        type: string
      responses:
        200:
          description: OK
      tags:
      - Platform Applications
  /?Action=ListPlatformApplications:
    get:
      summary: List Platform Applications
      description: |-
        Lists the platform application objects for the supported push notification services, such as
              APNS and GCM.
      operationId: listPlatformApplications
      x-api-path-slug: actionlistplatformapplications-get
      parameters:
      - in: query
        name: NextToken
        description: NextToken string is used when calling ListPlatformApplications
          action to retrieve additional records that are available after the first
          page results
        type: string
      responses:
        200:
          description: OK
      tags:
      - Platform Applications
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