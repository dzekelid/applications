{
  "info": {
    "name": "Dezrez Submits an individual referencing application for processing",
    "_postman_id": "b7d63f25-a705-48c7-807f-dbd6b73b9654",
    "description": "Submits an individual referencing application for processing.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Creates",
      "item": [
        {
          "id": "41e4e137-6897-4494-89b3-c623f073d9fd",
          "name": "TenantReferencing_CreateApplicationBycaseIdBytenancyRoleIdBypersonIdByproductId",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.dezrez.com",
              "path": [
                "api/tenantreferncing/addapplication/:caseId/:tenancyRoleId/:personId/:productId"
              ],
              "variable": [
                {
                  "id": "caseId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "personId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "productId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "tenancyRoleId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "header": [
              {
                "key": "Rezi-Api-Version",
                "value": "{}",
                "description": "Specifies which version of the API to call",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Creates a tenancy referencing application for a case using the details supplied."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "607ee57d-0d54-4785-8669-60e93e1a9d26"
            }
          ]
        }
      ]
    },
    {
      "name": "S",
      "item": [
        {
          "id": "1c8a41ab-ae8e-416f-a51d-8f840e7221c8",
          "name": "TenantReferencing_CreateApplicationBycaseIdBytenancyRoleIdBypersonId",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.dezrez.com",
              "path": [
                "api/tenantreferncing/addguarantor/:caseId/:tenancyRoleId/:personId"
              ],
              "variable": [
                {
                  "id": "caseId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "personId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "tenancyRoleId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "header": [
              {
                "key": "Rezi-Api-Version",
                "value": "{}",
                "description": "Specifies which version of the API to call",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Adds a guarantor to a tenancy referencing application for a case using the details supplied."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a375b992-f0e8-4042-b75e-969df60dfe33"
            }
          ]
        },
        {
          "id": "4ddb05f1-2a03-4451-9d7d-655706d63b3b",
          "name": "TenantReferencing_GetApplicationsBycaseId",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.dezrez.com",
              "path": [
                "api/tenantreferncing/applications/:caseId"
              ],
              "variable": [
                {
                  "id": "caseId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Rezi-Api-Version",
                "value": "{}",
                "description": "Specifies which version of the API to call",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets all tenancy referencing applications for the caseid provided."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "712fafa1-3067-45e6-97b2-f2da8dbbc444"
            }
          ]
        }
      ]
    },
    {
      "name": "Submits",
      "item": [
        {
          "id": "44bac45e-e793-44fc-b887-105f0572b353",
          "name": "TenantReferencing_SubmitApplicationForReferencingBycaseId",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.dezrez.com",
              "path": [
                "api/tenantreferncing/submitapplication/:caseId"
              ],
              "variable": [
                {
                  "id": "caseId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "header": [
              {
                "key": "Rezi-Api-Version",
                "value": "{}",
                "description": "Specifies which version of the API to call",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Submits an individual referencing application for processing."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f8b1ea30-8066-423f-b96d-20a3fd3d9a53"
            }
          ]
        }
      ]
    }
  ]
}