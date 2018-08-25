---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 1
info:
  title: Dezrez.Rezi.Client.Api
  version: 1.0.0
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/locale/{culture}:
    get:
      summary: returns the json file containing localization for the app based on
        a culture string, and any custom values for the agent
      description: Returns the json file containing localization for the app based
        on a culture string, and any custom values for the agent.
      operationId: Locale_GetLocalisationFileByculture
      x-api-path-slug: apilocaleculture-get
      parameters:
      - in: path
        name: culture
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Returns
      - Json
      - File
      - Containing
      - Localizationthe
      - App
      - Based
      - "On"
      - Culture
      - String
      - ""
      - Any
      - Custom
      - Valuesthe
      - Agent
---