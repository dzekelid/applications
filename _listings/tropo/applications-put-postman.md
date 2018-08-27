{
  "info": {
    "name": "Tropo Put Applications",
    "_postman_id": "226a6781-97d5-4d7d-9bb6-fc7fd903774f",
    "description": "Put applications.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Applications",
      "item": [
        {
          "id": "ee97ee5e-f3b1-4b51-bde7-b6a9534486df",
          "name": "getApplications",
          "request": {
            "url": "http://api.tropo.com/v1/applications?Content-Type=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get applications."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "25a3a1d5-594b-4522-87a2-bcf614f98ef2"
            }
          ]
        },
        {
          "id": "bb443f6b-cf44-4644-bbe5-4943dff52773",
          "name": "putApplications",
          "request": {
            "url": "http://api.tropo.com/v1/applications?Content-Type=%7B%7D",
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Put applications."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0a6764e9-b050-4c6b-9ab7-171b829cc3bc"
            }
          ]
        },
        {
          "id": "e6372633-0f04-4ea1-9428-4c2c8ae1a66b",
          "name": "postApplications",
          "request": {
            "url": "http://api.tropo.com/v1/applications?Content-Type=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Post applications."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dfd5c39c-615d-446b-961d-a952bf7019d9"
            }
          ]
        },
        {
          "id": "f2eefe09-d62b-4e1b-9bd3-a9841971675e",
          "name": "deleteApplications",
          "request": {
            "url": "http://api.tropo.com/v1/applications?Content-Type=%7B%7D",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete applications."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "89109627-047d-40ca-9428-8b9e0ab9f7ac"
            }
          ]
        }
      ]
    }
  ]
}