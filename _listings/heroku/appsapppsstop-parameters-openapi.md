---
swagger: "2.0"
x-collection-name: Heroku
x-complete: 0
info:
  title: Heroku Parameters Application PS Stop
  description: Parameters application ps stop.
  version: "1"
host: api.heroku.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /apps/{app}/addons:
    parameters:
      summary: Parameter Application Addons
      description: Parameter application addons.
      operationId: parametersAppsAppAddons
      x-api-path-slug: appsappaddons-parameters
      responses:
        200:
          description: OK
      tags:
      - Parameter
      - Application
      - ons
    get:
      summary: Get Application Addons
      description: List addons installed on an app.
      operationId: getAppsAppAddons
      x-api-path-slug: appsappaddons-get
      parameters:
      - in: header
        name: Accept
        description: Content type
      - in: query
        name: Accept
        description: Content type
      - in: query
        name: app
        description: The app name
      - in: path
        name: app
      responses:
        200:
          description: OK
      tags:
      - Application
      - ons
  /apps/{app}/addons/{addon}:
    parameters:
      summary: Parameters Applications Addons
      description: Parameters applications addons.
      operationId: parametersAppsAppAddonsAddon
      x-api-path-slug: appsappaddonsaddon-parameters
      responses:
        200:
          description: OK
      tags:
      - Parameters
      - Applications
      - ons
    post:
      summary: Add Application Addons
      description: Install an addon to an app.
      operationId: postAppsAppAddonsAddon
      x-api-path-slug: appsappaddonsaddon-post
      parameters:
      - in: header
        name: Accept
        description: Content type
      - in: query
        name: Accept
        description: Content type
      - in: query
        name: addon
        description: the addon name
      - in: path
        name: addon
      - in: query
        name: app
        description: The app name
      - in: path
        name: app
      responses:
        200:
          description: OK
      tags:
      - Application
      - ons
    put:
      summary: Put Application Addons
      description: Upgrade an addon to an app.
      operationId: putAppsAppAddonsAddon
      x-api-path-slug: appsappaddonsaddon-put
      parameters:
      - in: header
        name: Accept
        description: Content type
      - in: query
        name: Accept
        description: Content type
      - in: query
        name: addon
        description: the addon name
      - in: path
        name: addon
      - in: query
        name: app
        description: The app name
      - in: path
        name: app
      responses:
        200:
          description: OK
      tags:
      - Put
      - Application
      - ons
    delete:
      summary: Delete Applications Addons
      description: Uninstall an addon from an app.
      operationId: deleteAppsAppAddonsAddon
      x-api-path-slug: appsappaddonsaddon-delete
      parameters:
      - in: header
        name: Accept
        description: Content type
      - in: query
        name: Accept
        description: Content type
      - in: query
        name: addon
        description: the addon name
      - in: path
        name: addon
      - in: query
        name: app
        description: The app name
      - in: path
        name: app
      responses:
        200:
          description: OK
      tags:
      - Applications
      - ons
  /apps:
    parameters:
      summary: Parameters Applications
      description: Parameters applications.
      operationId: parametersApps
      x-api-path-slug: apps-parameters
      responses:
        200:
          description: OK
      tags:
      - Parameters
      - Applications
    get:
      summary: Get Applications
      description: Get applications.
      operationId: getApps
      x-api-path-slug: apps-get
      parameters:
      - in: header
        name: Accept
        description: Content type
      - in: query
        name: Accept
        description: Content type
      responses:
        200:
          description: OK
      tags:
      - Applications
    post:
      summary: Add Applications
      description: Add applications.
      operationId: postApps
      x-api-path-slug: apps-post
      parameters:
      - in: header
        name: Accept
        description: Content type
      - in: query
        name: Accept
        description: Content type
      responses:
        200:
          description: OK
      tags:
      - Applications
  /apps/{name}:
    parameters:
      summary: Parameters Applications Name
      description: Parameters applications name.
      operationId: parametersAppsName
      x-api-path-slug: appsname-parameters
      responses:
        200:
          description: OK
      tags:
      - Parameters
      - Applications
      - Name
    get:
      summary: Get Applications Name
      description: Get applications name.
      operationId: getAppsName
      x-api-path-slug: appsname-get
      parameters:
      - in: query
        name: Accept
        description: Content type
      - in: header
        name: Accept
        description: Content type
      - in: query
        name: name
        description: The app name
      - in: path
        name: name
      responses:
        200:
          description: OK
      tags:
      - Applications
      - Name
    delete:
      summary: Delete Applications Name
      description: Delete applications name.
      operationId: deleteAppsName
      x-api-path-slug: appsname-delete
      parameters:
      - in: query
        name: Accept
        description: Content type
      - in: header
        name: Accept
        description: Content type
      - in: query
        name: name
        description: The app name
      - in: path
        name: name
      responses:
        200:
          description: OK
      tags:
      - Applications
      - Name
  /apps/{app}/collaborators:
    parameters:
      summary: Parameters Application Collaborators
      description: Parameters application collaborators.
      operationId: parametersAppsAppCollaborators
      x-api-path-slug: appsappcollaborators-parameters
      responses:
        200:
          description: OK
      tags:
      - Parameters
      - Application
      - Collaborators
    get:
      summary: Get Application Collaborators
      description: List collaborators for an app.
      operationId: getAppsAppCollaborators
      x-api-path-slug: appsappcollaborators-get
      parameters:
      - in: header
        name: Accept
        description: Content type
      - in: query
        name: Accept
        description: Content type
      - in: query
        name: app
        description: The app name
      - in: path
        name: app
      responses:
        200:
          description: OK
      tags:
      - Application
      - Collaborators
  /apps/{app}/collaborators/{email}:
    parameters:
      summary: Parameters Application Collaborators Email
      description: Parameters application collaborators email.
      operationId: parametersAppsAppCollaboratorsEmail
      x-api-path-slug: appsappcollaboratorsemail-parameters
      responses:
        200:
          description: OK
      tags:
      - Parameters
      - Application
      - Collaborators
      - Email
    delete:
      summary: Delete Application Collaborators Email
      description: Delete application collaborators email.
      operationId: deleteAppsAppCollaboratorsEmail
      x-api-path-slug: appsappcollaboratorsemail-delete
      parameters:
      - in: header
        name: Accept
        description: Content type
      - in: query
        name: Accept
        description: Content type
      - in: query
        name: app
        description: The app name
      - in: path
        name: app
      - in: query
        name: email
        description: The email of the user to remove as a collaborator
      - in: path
        name: email
      responses:
        200:
          description: OK
      tags:
      - Application
      - Collaborators
      - Email
  /apps/{app}/config_vars:
    parameters:
      summary: Parameters Application Config Variables
      description: Parameters application config variables.
      operationId: parametersAppsAppConfigVars
      x-api-path-slug: appsappconfig-vars-parameters
      responses:
        200:
          description: OK
      tags:
      - Parameters
      - Application
      - Config
      - Variables
    get:
      summary: Get Application Config Variables
      description: Get application config variables.
      operationId: getAppsAppConfigVars
      x-api-path-slug: appsappconfig-vars-get
      parameters:
      - in: header
        name: Accept
        description: Content type
      - in: query
        name: Accept
        description: Content type
      - in: query
        name: app
        description: The app name
      - in: path
        name: app
      responses:
        200:
          description: OK
      tags:
      - Application
      - Config
      - Variables
    put:
      summary: Put Application Config Variables
      description: Put application config variables.
      operationId: putAppsAppConfigVars
      x-api-path-slug: appsappconfig-vars-put
      parameters:
      - in: header
        name: Accept
        description: Content type
      - in: query
        name: Accept
        description: Content type
      - in: query
        name: app
        description: The app name
      - in: path
        name: app
      responses:
        200:
          description: OK
      tags:
      - Put
      - Application
      - Config
      - Variables
  /apps/{app}/config_vars/{key}:
    parameters:
      summary: Parameters Application Config Variables Key
      description: Parameters application config variables key.
      operationId: parametersAppsAppConfigVarsKey
      x-api-path-slug: appsappconfig-varskey-parameters
      responses:
        200:
          description: OK
      tags:
      - Parameters
      - Application
      - Config
      - Variables
      - Key
    delete:
      summary: Delete Application Config Variables Key
      description: Delete application config variables key.
      operationId: deleteAppsAppConfigVarsKey
      x-api-path-slug: appsappconfig-varskey-delete
      parameters:
      - in: header
        name: Accept
        description: Content type
      - in: query
        name: Accept
        description: Content type
      - in: query
        name: app
        description: The app name
      - in: path
        name: app
      - in: query
        name: key
        description: The config var to remove
      - in: path
        name: key
      responses:
        200:
          description: OK
      tags:
      - Application
      - Config
      - Variables
      - Key
  /apps/{app}/domains:
    parameters:
      summary: Parameters Application Domains
      description: Parameters application domains.
      operationId: parametersAppsAppDomains
      x-api-path-slug: appsappdomains-parameters
      responses:
        200:
          description: OK
      tags:
      - Parameters
      - Application
      - Domains
    get:
      summary: Get Application Domains
      description: List domains for an app.
      operationId: getAppsAppDomains
      x-api-path-slug: appsappdomains-get
      parameters:
      - in: header
        name: Accept
        description: Content type
      - in: query
        name: Accept
        description: Content type
      - in: query
        name: app
        description: The app name
      - in: path
        name: app
      responses:
        200:
          description: OK
      tags:
      - Application
      - Domains
  /apps/{app}/domains/{domain_name}:
    parameters:
      summary: Parameters Application Domain Name
      description: Parameters application domain name.
      operationId: parametersAppsAppDomainsDomainName
      x-api-path-slug: appsappdomainsdomain-name-parameters
      responses:
        200:
          description: OK
      tags:
      - Parameters
      - Application
      - Domain
      - Name
    delete:
      summary: Delete Application Domain Name
      description: Delete application domain name.
      operationId: deleteAppsAppDomainsDomainName
      x-api-path-slug: appsappdomainsdomain-name-delete
      parameters:
      - in: header
        name: Accept
        description: Content type
      - in: query
        name: Accept
        description: Content type
      - in: query
        name: app
        description: The app name
      - in: path
        name: app
      - in: query
        name: domain_name
        description: The domain to remove
      - in: path
        name: domain_name
      responses:
        200:
          description: OK
      tags:
      - Application
      - Domain
      - Name
  /apps/{app}/logs:
    parameters:
      summary: Parameters Application Logs
      description: Parameters application logs.
      operationId: parametersAppsAppLogs
      x-api-path-slug: appsapplogs-parameters
      responses:
        200:
          description: OK
      tags:
      - Parameters
      - Application
      - Logs
    get:
      summary: Get Application Logs
      description: Get application logs.
      operationId: getAppsAppLogs
      x-api-path-slug: appsapplogs-get
      parameters:
      - in: header
        name: Accept
        description: Content type
      - in: query
        name: Accept
        description: Content type
      - in: query
        name: app
        description: The app name
      - in: path
        name: app
      - in: query
        name: logplex
        description: Use logplex to stream logs (always true)
      - in: query
        name: num
        description: The number of lines to display
      - in: query
        name: ps
        description: Only display logs from a given process
      - in: query
        name: source
        description: Only display logs from a given source
      - in: query
        name: tail
        description: '1: continually stream logs - : display only num logs'
      responses:
        200:
          description: OK
      tags:
      - Application
      - Logs
  /apps/{app}/ps:
    parameters:
      summary: Parameters Application PS
      description: Parameters application ps.
      operationId: parametersAppsAppPs
      x-api-path-slug: appsappps-parameters
      responses:
        200:
          description: OK
      tags:
      - Parameters
      - Application
      - PS
    get:
      summary: Get Application PS
      description: List processes for an app.
      operationId: getAppsAppPs
      x-api-path-slug: appsappps-get
      parameters:
      - in: header
        name: Accept
        description: Content type
      - in: query
        name: Accept
        description: Content type
      - in: query
        name: app
        description: The app name
      - in: path
        name: app
      responses:
        200:
          description: OK
      tags:
      - Application
      - PS
    post:
      summary: Add Application PS
      description: Run a one-off process.
      operationId: postAppsAppPs
      x-api-path-slug: appsappps-post
      parameters:
      - in: header
        name: Accept
        description: Content type
      - in: query
        name: Accept
        description: Content type
      - in: query
        name: app
        description: The app name
      - in: path
        name: app
      - in: query
        name: attach
        description: 'true: use rendezvous to access stdin/stdout - : stream process
          output to the application log'
      - in: query
        name: command
        description: The command to run
      responses:
        200:
          description: OK
      tags:
      - Application
      - PS
  /apps/{app}/ps/restart:
    parameters:
      summary: Parameters Application PS Restart
      description: Parameters application ps restart.
      operationId: parametersAppsAppPsRestart
      x-api-path-slug: appsapppsrestart-parameters
      responses:
        200:
          description: OK
      tags:
      - Parameters
      - Application
      - PS
      - Restart
    post:
      summary: Add Application PS Restart
      description: Restart processes of an app. Specify either ps or type to restart
        only the specified processes. Leave both blank to restart the entire app.
      operationId: postAppsAppPsRestart
      x-api-path-slug: appsapppsrestart-post
      parameters:
      - in: header
        name: Accept
        description: Content type
      - in: query
        name: Accept
        description: Content type
      - in: query
        name: app
        description: The app name
      - in: path
        name: app
      - in: query
        name: ps
        description: The name of a process to restart
      - in: query
        name: type
        description: The type of process to restart
      responses:
        200:
          description: OK
      tags:
      - Application
      - PS
      - Restart
  /apps/{app}/ps/stop:
    parameters:
      summary: Parameters Application PS Stop
      description: Parameters application ps stop.
      operationId: parametersAppsAppPsStop
      x-api-path-slug: appsapppsstop-parameters
      responses:
        200:
          description: OK
      tags:
      - Parameters
      - Application
      - PS
      - Stop
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