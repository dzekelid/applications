{
  "info": {
    "name": "Tropo Delete Applications",
    "_postman_id": "60990f19-d399-4a04-af4c-6dbf88f47fe4",
    "description": "Delete applications.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Applications",
      "item": [
        {
          "id": "f3ed33e7-d360-49a3-8808-4f8da6b42d2a",
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
              "id": "1bf38b1b-28d6-475f-bbbb-112dd1768c3f"
            }
          ]
        }
      ]
    }
  ]
}