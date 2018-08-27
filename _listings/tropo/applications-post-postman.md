{
  "info": {
    "name": "Tropo Post Applications",
    "_postman_id": "f419db0b-dc8a-4d1e-b9e4-0259cd64aa6a",
    "description": "Post applications.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Applications",
      "item": [
        {
          "id": "256f342b-678b-40b7-9fac-d395cbf83dea",
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
              "id": "b16fadbb-4317-4bd6-81b8-d20e84824be5"
            }
          ]
        },
        {
          "id": "a51c3d7e-4d95-4113-ba3c-baeb87d35b5b",
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
              "id": "a965e169-ad6a-4b54-b551-c64d6346248b"
            }
          ]
        },
        {
          "id": "7b1f27fd-d669-48f2-a703-c59c0646ef23",
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
              "id": "7003bd77-74e2-4f0b-a9d9-375a3eb15aa4"
            }
          ]
        }
      ]
    }
  ]
}