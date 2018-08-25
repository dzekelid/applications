---
swagger: "2.0"
x-collection-name: AWS Elastic Beanstalk
x-complete: 1
info:
  title: AWS Elastic Beanstalk API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateApplication:
    get:
      summary: Create Application
      description: |-
        Creates an application that has one configuration template named default
              and no application versions.
      operationId: createApplication
      x-api-path-slug: actioncreateapplication-get
      parameters:
      - in: query
        name: ApplicationName
        description: The name of the application
        type: string
      - in: query
        name: Description
        description: Describes the application
        type: string
      - in: query
        name: ResourceLifecycleConfig
        description: Specify an application resource lifecycle configuration to prevent
          your application      from accumulating too many versions
        type: string
      responses:
        200:
          description: OK
      tags:
      - Applications
  /?Action=CreateApplicationVersion:
    get:
      summary: Create Application Version
      description: Creates an application version for the specified application.
      operationId: createApplicationVersion
      x-api-path-slug: actioncreateapplicationversion-get
      parameters:
      - in: query
        name: ApplicationName
        description: The name of the application
        type: string
      - in: query
        name: AutoCreateApplication
        description: Set to true to create an application with the specified name
          if it doesnt      already exist
        type: string
      - in: query
        name: BuildConfiguration
        description: Settings for an AWS CodeBuild build
        type: string
      - in: query
        name: Description
        description: Describes this version
        type: string
      - in: query
        name: Process
        description: Preprocesses and validates the environment manifest and configuration
          files in the      source bundle
        type: string
      - in: query
        name: SourceBuildInformation
        description: Specify a commit in an AWS CodeCommit Git repository to use as
          the source code for the      application version
        type: string
      - in: query
        name: SourceBundle
        description: The Amazon S3 bucket and key that identify the location of the
          source bundle for this      version
        type: string
      - in: query
        name: VersionLabel
        description: A label identifying this version
        type: string
      responses:
        200:
          description: OK
      tags:
      - Applications
  /?Action=DeleteApplication:
    get:
      summary: Delete Application
      description: |-
        Deletes the specified application along with all associated versions and
              configurations.
      operationId: deleteApplication
      x-api-path-slug: actiondeleteapplication-get
      parameters:
      - in: query
        name: ApplicationName
        description: The name of the application to delete
        type: string
      - in: query
        name: TerminateEnvByForce
        description: When set to true, running environments will be terminated before
          deleting the      application
        type: string
      responses:
        200:
          description: OK
      tags:
      - Applications
  /?Action=DescribeApplications:
    get:
      summary: Describe Applications
      description: Returns the descriptions of existing applications.
      operationId: describeApplications
      x-api-path-slug: actiondescribeapplications-get
      parameters:
      - in: query
        name: ApplicationNames.member.N
        description: If specified, AWS Elastic Beanstalk restricts the returned descriptions
          to only include      those with the specified names
        type: string
      responses:
        200:
          description: OK
      tags:
      - Applications
  /?Action=UpdateApplication:
    get:
      summary: Update Application
      description: Updates the specified application to have the specified properties.
      operationId: updateApplication
      x-api-path-slug: actionupdateapplication-get
      parameters:
      - in: query
        name: ApplicationName
        description: The name of the application to update
        type: string
      - in: query
        name: Description
        description: A new description for the application
        type: string
      responses:
        200:
          description: OK
      tags:
      - Applications
  /?Action=UpdateApplicationVersion:
    get:
      summary: Update Application Version
      description: Updates the specified application version to have the specified
        properties.
      operationId: updateApplicationVersion
      x-api-path-slug: actionupdateapplicationversion-get
      parameters:
      - in: query
        name: ApplicationName
        description: The name of the application associated with this version
        type: string
      - in: query
        name: Description
        description: A new description for this version
        type: string
      - in: query
        name: VersionLabel
        description: The name of the version to update
        type: string
      responses:
        200:
          description: OK
      tags:
      - Applications
  /?Action=RestartAppServer:
    get:
      summary: Restart App Server
      description: |-
        Causes the environment to restart the application container server running on each
              Amazon EC2 instance.
      operationId: restartAppServer
      x-api-path-slug: actionrestartappserver-get
      parameters:
      - in: query
        name: EnvironmentId
        description: The ID of the environment to restart the server for
        type: string
      - in: query
        name: EnvironmentName
        description: The name of the environment to restart the server for
        type: string
      responses:
        200:
          description: OK
      tags:
      - App Servers
---