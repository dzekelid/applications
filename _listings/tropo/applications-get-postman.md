{
  "info": {
    "name": "Tropo Get Applications",
    "_postman_id": "f0fef864-e79a-46fe-8ecf-050018550e02",
    "description": "Get applications.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Applications",
      "item": [
        {
          "id": "0d0ff639-3545-4c8f-87f3-504dcc1ff0fd",
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
              "id": "123d1bda-666f-4c7c-b102-01aca2cbf0fd"
            }
          ]
        },
        {
          "id": "a3b0dff9-40d6-4b39-885e-b59fa2b476dd",
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
              "id": "c745f80e-b60d-46fc-8bf3-4aaedb55a22d"
            }
          ]
        }
      ]
    }
  ]
}