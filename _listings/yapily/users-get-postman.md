{
  "info": {
    "name": "Yapily Get application users",
    "_postman_id": "ca82349c-4b8c-45dd-b150-2efca2635735",
    "description": "Get application users.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Accounts",
      "item": [
        {
          "id": "28e7e59b-4a0c-45fc-a39f-ec1bea2f794a",
          "name": "getAccountsUsingGET",
          "request": {
            "url": "http://api.yapily.com:443/accounts",
            "method": "GET",
            "header": [
              {
                "key": "consent",
                "value": "{}",
                "description": "Consent Token",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get accounts."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "defd079d-33c1-4ead-8822-dcf64d77f4a1"
            }
          ]
        }
      ]
    },
    {
      "name": "Account",
      "item": [
        {
          "id": "4b2d771d-bcbf-4661-aaf1-12dea9004a5b",
          "name": "getAccountUsingGET",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.yapily.com",
              "path": [
                "accounts/:accountId"
              ],
              "port": "443",
              "variable": [
                {
                  "id": "accountId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "consent",
                "value": "{}",
                "description": "Consent Token",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ba586f50-cd41-4a69-97da-4dcc5d5670bd"
            }
          ]
        },
        {
          "id": "4507e7e5-6e8e-4be9-a370-ec092e9ef43d",
          "name": "getTransactionsUsingGET",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.yapily.com",
              "path": [
                "accounts/:accountId/transactions"
              ],
              "port": "443",
              "variable": [
                {
                  "id": "accountId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "consent",
                "value": "{}",
                "description": "Consent Token",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get account transactions."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8ee0cf0f-a2ad-473f-8aaa-e26095424f9f"
            }
          ]
        }
      ]
    },
    {
      "name": "Identity",
      "item": [
        {
          "id": "16fd8ae7-a75b-49a8-a41b-e8a813993f42",
          "name": "identityUsingGET",
          "request": {
            "url": "http://api.yapily.com:443/identity",
            "method": "GET",
            "header": [
              {
                "key": "consent",
                "value": "{}",
                "description": "Consent Token",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get identity."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "200a0b13-e1bf-44b0-93e1-0a6f3bcd57eb"
            }
          ]
        }
      ]
    },
    {
      "name": "Retrieves",
      "item": [
        {
          "id": "38942f47-c80f-4fc3-a0d0-a0fb5198b007",
          "name": "getInstitutionsUsingGET",
          "request": {
            "url": "http://api.yapily.com:443/institutions",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves the list of institutions available in yapily."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1bd007c6-e168-46d7-90ce-689e8c1756fa"
            }
          ]
        },
        {
          "id": "03e0b211-e574-4ef4-b7a6-bb4c9ec7970e",
          "name": "getInstitutionUsingGET",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.yapily.com",
              "path": [
                "institutions/:institutionId"
              ],
              "port": "443",
              "variable": [
                {
                  "id": "institutionId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves details of a specific institution available in yapily."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "34519b26-1359-46c0-be48-2312e4b3cc27"
            }
          ]
        },
        {
          "id": "ba39f365-d59b-4871-bef8-7e34173d5845",
          "name": "getPersonalCurrentAccountsUsingGET",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.yapily.com",
              "path": [
                "institutions/:institutionId/personal-current-accounts"
              ],
              "port": "443",
              "variable": [
                {
                  "id": "institutionId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves details of personal current accounts for an institution."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "edb187e6-f1a9-440e-95d5-cb60315058dc"
            }
          ]
        }
      ]
    },
    {
      "name": "Returns",
      "item": [
        {
          "id": "e020a3f9-6845-4373-8389-0026d94178f2",
          "name": "getApplicationMeUsingGET",
          "request": {
            "url": "http://api.yapily.com:443/me",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the details of the application which owns the request credentials."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f3167a2e-0349-4578-b8a9-162cd3bf8e31"
            }
          ]
        }
      ]
    },
    {
      "name": "Application",
      "item": [
        {
          "id": "bcdc6c2e-c8b4-473b-92d2-abbedcf0cb9c",
          "name": "getUsersUsingGET",
          "request": {
            "url": "http://api.yapily.com:443/users",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get application users."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2f17405b-a58a-4f11-9681-44d6bf490f3d"
            }
          ]
        }
      ]
    }
  ]
}