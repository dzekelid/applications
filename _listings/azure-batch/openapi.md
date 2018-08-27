swagger: "2.0"
x-collection-name: Azure Batch
x-complete: 1
info:
  title: BatchManagement
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Batch/batchAccounts/{accountName}/applications/{applicationId}
  : put:
      summary: Application Create
      description: Adds an application to the specified Batch account.
      operationId: Application_Create
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameapplicationsapplicationid-put
      parameters:
      - in: path
        name: accountName
        description: The name of the Batch account
      - in: path
        name: applicationId
        description: The ID of the application
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The parameters for the request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group that contains the Batch account
      responses:
        200:
          description: OK
      tags:
      - Application
    delete:
      summary: Application Delete
      description: Deletes an application.
      operationId: Application_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameapplicationsapplicationid-delete
      parameters:
      - in: path
        name: accountName
        description: The name of the Batch account
      - in: path
        name: applicationId
        description: The ID of the application
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group that contains the Batch account
      responses:
        200:
          description: OK
      tags:
      - Application
    get:
      summary: Application Get
      description: Gets information about the specified application.
      operationId: Application_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameapplicationsapplicationid-get
      parameters:
      - in: path
        name: accountName
        description: The name of the Batch account
      - in: path
        name: applicationId
        description: The ID of the application
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group that contains the Batch account
      responses:
        200:
          description: OK
      tags:
      - Application
    patch:
      summary: Application Update
      description: Updates settings for the specified application.
      operationId: Application_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameapplicationsapplicationid-patch
      parameters:
      - in: path
        name: accountName
        description: The name of the Batch account
      - in: path
        name: applicationId
        description: The ID of the application
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The parameters for the request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group that contains the Batch account
      responses:
        200:
          description: OK
      tags:
      - Application
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Batch/batchAccounts/{accountName}/applications
  : get:
      summary: Application List
      description: Lists all of the applications in the specified account.
      operationId: Application_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-batchbatchaccountsaccountnameapplications-get
      parameters:
      - in: path
        name: accountName
        description: The name of the Batch account
      - in: query
        name: maxresults
        description: The maximum number of items to return in the response
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group that contains the Batch account
      responses:
        200:
          description: OK
      tags:
      - Application