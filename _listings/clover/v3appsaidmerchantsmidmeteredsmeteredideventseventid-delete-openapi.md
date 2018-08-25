---
swagger: "2.0"
x-collection-name: Clover
x-complete: 0
info:
  title: Clover Delete an app billing metered event, if not charged.
  version: 1.0.0
  description: This deletes an app billing metered event, if the event has not been
    charged yet. See https://docs.clover.com/launch/billing/ for more information.
    Requires an OAuth generated token.
host: /merchants
basePath: https://api.clover.com
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v3/apps/{aId}/merchants/{mId}/notifications:
    post:
      summary: Create a notification for an app
      description: 'Push a message to all merchant devices that have your app installed
        and are listening for notifications.  For details on how to use Clover''s
        Android SDK to receive notifications see: https://github.com/clover/android-examples/tree/master/pushnotificationexample'
      operationId: CreateMerchantAppNotification
      x-api-path-slug: v3appsaidmerchantsmidnotifications-post
      parameters:
      - in: path
        name: aId
        description: App Id
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: mId
        description: Merchant Id
      responses:
        200:
          description: OK
      tags:
      - Apps
      - Merchants
      - Notifications
  /v3/apps/{aId}/devices/{dId}/notifications:
    post:
      summary: Create a notification for a device
      description: 'Push a message to a device that has your app installed and is
        listening for notifications.  For details on how to use Clover''s Android
        SDK to receive notifications see: https://github.com/clover/android-examples/tree/master/pushnotificationexample'
      operationId: CreateDeviceAppNotification
      x-api-path-slug: v3appsaiddevicesdidnotifications-post
      parameters:
      - in: path
        name: aId
        description: App Id
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: dId
        description: Developer Id
      responses:
        200:
          description: OK
      tags:
      - Apps
      - Devices
      - DId
      - Notifications
  /v3/apps/{aId}/merchants/{mId}/billing_info:
    get:
      summary: Get merchant's billing information for an app
      description: Gives detailed information about the status of the merchant's billing
        for the app including current subscription tier and trial status. Requires
        an OAuth generated token.
      operationId: GetMerchantBillingInfo
      x-api-path-slug: v3appsaidmerchantsmidbilling-info-get
      parameters:
      - in: path
        name: aId
        description: App Id
      - in: path
        name: mId
        description: Merchant Id
      responses:
        200:
          description: OK
      tags:
      - Apps
      - Merchants
      - Billing
      - Info
  /v3/apps/{aId}/merchants/{mId}/metereds/{meteredId}:
    post:
      summary: Create an app billing metered event
      description: This creates an app billing metered event. The amount Clover will
        charge the specified merchant is based on the cost specified for this metered
        object in the Developer Dashboard. The merchant will be billed during their
        next scheduled billing cycle. Passing "count" as a query parameter will bill
        the merchant for that number of metered events. "count" must be passed as
        a query parameter in order to function properly ??? if passed in the request
        body, it will be ignored. If not specified, "count" will default to 1. See
        https://docs.clover.com/launch/billing/ for more information. Requires an
        OAuth generated token.
      operationId: CreateMerchantAppMeteredEvent
      x-api-path-slug: v3appsaidmerchantsmidmeteredsmeteredid-post
      parameters:
      - in: path
        name: aId
        description: App Id
      - in: path
        name: meteredId
        description: Metered Id
      - in: path
        name: mId
        description: Merchant Id
      responses:
        200:
          description: OK
      tags:
      - Apps
      - Merchants
      - Metereds
      - MeteredId
    get:
      summary: Get the app metered billing events for an app metered, e.g. all the
        billing events for the event 'reservation'
      description: Get the app metered billing events for an app metered, e.g. all
        the billing events for the event 'reservation'.
      operationId: GetMerchantAppMeteredEvents
      x-api-path-slug: v3appsaidmerchantsmidmeteredsmeteredid-get
      parameters:
      - in: path
        name: aId
        description: App Id
      - in: path
        name: meteredId
        description: Metered Id
      - in: path
        name: mId
        description: Merchant Id
      responses:
        200:
          description: OK
      tags:
      - Apps
      - Merchants
      - Metereds
      - MeteredId
  /v3/apps/{aId}/merchants/{mId}/metereds/{meteredId}/events/{eventId}:
    get:
      summary: Get an app billing metered event
      description: This enables you to fetch the details on a merchants app billing
        metered event. Requires an OAuth generated token.
      operationId: GetMerchantAppMeteredEvent
      x-api-path-slug: v3appsaidmerchantsmidmeteredsmeteredideventseventid-get
      parameters:
      - in: path
        name: aId
        description: App Id
      - in: path
        name: eventId
      - in: path
        name: meteredId
        description: Metered Id
      - in: path
        name: mId
        description: Merchant Id
      responses:
        200:
          description: OK
      tags:
      - Apps
      - Merchants
      - Metereds
      - MeteredId
      - Events
      - EventId
    delete:
      summary: Delete an app billing metered event, if not charged.
      description: This deletes an app billing metered event, if the event has not
        been charged yet. See https://docs.clover.com/launch/billing/ for more information.
        Requires an OAuth generated token.
      operationId: DeleteMerchantAppMeteredEvent
      x-api-path-slug: v3appsaidmerchantsmidmeteredsmeteredideventseventid-delete
      parameters:
      - in: path
        name: aId
        description: App Id
      - in: path
        name: eventId
      - in: path
        name: meteredId
        description: Metered Id
      - in: path
        name: mId
        description: Merchant Id
      responses:
        200:
          description: OK
      tags:
      - Apps
      - Merchants
      - Metereds
      - MeteredId
      - Events
      - EventId
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