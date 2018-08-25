---
swagger: "2.0"
x-collection-name: Mattermost
x-complete: 0
info:
  title: Mattermost API Get webapp plugins
  description: |-
    Get a list of web app plugins installed and activated on the server.

    ##### Permissions
    No permissions required.

    __Minimum server version__: 4.4
  termsOfService: https://about.mattermost.com/default-terms/
  version: 4.0.0
host: your-mattermost-url.com
basePath: /api/v4
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /plugins/webapp:
    get:
      summary: Get webapp plugins
      description: |-
        Get a list of web app plugins installed and activated on the server.

        ##### Permissions
        No permissions required.

        __Minimum server version__: 4.4
      operationId: get-a-list-of-web-app-plugins-installed-and-activated-on-the-server-permissionsno-permissions-requir
      x-api-path-slug: pluginswebapp-get
      responses:
        200:
          description: OK
      tags:
      - Webapp
      - Plugins
  /oauth/apps:
    get:
      summary: Get OAuth apps
      description: |-
        Get a page of OAuth 2.0 client applications registered with Mattermost.
        ##### Permissions
        With `manage_oauth` permission, the apps registered by the logged in user are returned. With `manage_system_wide_oauth` permission, all apps regardless of creator are returned.
      operationId: get-a-page-of-oauth-20-client-applications-registered-with-mattermost-permissionswith-manage-oauth-p
      x-api-path-slug: oauthapps-get
      parameters:
      - in: query
        name: page
        description: The page to select
      - in: query
        name: per_page
        description: The number of apps per page
      responses:
        200:
          description: OK
      tags:
      - OAuth
      - Apps
  /users/{user_id}/oauth/apps/authorized:
    get:
      summary: Get authorized OAuth apps
      description: |-
        Get a page of OAuth 2.0 client applications authorized to access a user's account.
        ##### Permissions
        Must be authenticated as the user or have `edit_other_users` permission.
      operationId: get-a-page-of-oauth-20-client-applications-authorized-to-access-a-users-account-permissionsmust-be-a
      x-api-path-slug: usersuser-idoauthappsauthorized-get
      parameters:
      - in: query
        name: page
        description: The page to select
      - in: query
        name: per_page
        description: The number of apps per page
      - in: path
        name: user_id
        description: User GUID
      responses:
        200:
          description: OK
      tags:
      - Authorized
      - OAuth
      - Apps
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