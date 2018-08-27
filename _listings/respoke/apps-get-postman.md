{
  "info": {
    "name": "Respoke REST API Apps",
    "_postman_id": "88d82970-48c5-4d79-9da2-548431bd15d7",
    "description": "Create an app.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Admin",
      "item": [
        {
          "id": "ac55a07e-666c-4b3a-8676-ac0f5c2a28e5",
          "name": "postAdminSessions",
          "request": {
            "url": "http://api.respoke.io/v1/admin-sessions/?password=%7B%7D&username=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Log in with the account username and password. Get an Admin-Token."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9248a401-d1b3-4927-a08f-83e7fdcea2dc"
            }
          ]
        }
      ]
    },
    {
      "name": "Adminsessions",
      "item": [
        {
          "id": "bbc27833-dc24-4f79-aa65-b1069ca88141",
          "name": "postAdminsessions",
          "request": {
            "url": "http://api.respoke.io/v1/adminsessions/?password=%7B%7D&username=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Full API permissions are obtained by POSTing your username and password to [base]/adminsessions."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c315f445-a853-4afa-b9a5-d2cca9832fe2"
            }
          ]
        }
      ]
    },
    {
      "name": "Appauthsessions",
      "item": [
        {
          "id": "68d82484-de89-47ce-83a9-a6339cc493f9",
          "name": "postAppauthsessions",
          "request": {
            "url": "http://api.respoke.io/v1/appauthsessions/?App-Token=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Your users authenticate to Respoke using an App-Token obtained when they POST your tokenId to [base]/appauthsessions."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "84e92f74-95b2-49ee-9714-72cc38747928"
            }
          ]
        }
      ]
    },
    {
      "name": "Apps",
      "item": [
        {
          "id": "35c2e4f1-32e3-4413-b27f-af0700c9d53e",
          "name": "getApps",
          "request": {
            "url": "http://api.respoke.io/v1/apps/",
            "method": "GET",
            "header": [
              {
                "key": "Admin-Token",
                "value": "{}",
                "description": "Your admin token",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Create an app."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a435040e-0543-485d-9281-5aab9150151c"
            }
          ]
        }
      ]
    }
  ]
}