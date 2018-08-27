{
  "info": {
    "name": "AWS OpsWorks API Delete App",
    "_postman_id": "2a46f996-4f1f-4a0d-8b42-a4528e6ad3ca",
    "description": "Deletes a specified app.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Applications",
      "item": [
        {
          "id": "84a7eb3d-18e4-4189-9b05-4659afd6cacc",
          "name": "createApp",
          "request": {
            "url": "http://example.com/api/?Action=CreateApp?AppSource=AppSource&Attributes=Attributes&DataSources=DataSources&Description=Description&Domains=Domains&EnableSsl=EnableSsl&Environment=Environment&Name=Name&Shortname=Shortname&SslConfiguration=SslConfiguration&StackId=StackId&Type=Type",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an app for a specified stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "552132c4-2748-410d-9995-ad5ecbaabd15"
            }
          ]
        },
        {
          "id": "ab601257-1d7a-4c93-844a-4d8f7899c700",
          "name": "deleteApp",
          "request": {
            "url": "http://example.com/api/?Action=DeleteApp?AppId=AppId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a specified app."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "950db6bc-ecee-4621-99e5-46fd29cd754b"
            }
          ]
        }
      ]
    }
  ]
}