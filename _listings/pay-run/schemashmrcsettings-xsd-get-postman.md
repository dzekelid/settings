{
  "info": {
    "name": "Pay Run.IO Get the HmrcSettings schema",
    "_postman_id": "84544c97-52c1-4ffc-8ce5-b387aaaf854f",
    "description": "Returns the HmrcSettings schema object",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "HmrcSettings",
      "item": [
        {
          "id": "bb45d985-6e50-4d8e-b8ec-253bc3d2f7f1",
          "name": "GetHmrcSettingsSchema",
          "request": {
            "url": "http://api.test.payrun.io/Schemas/HmrcSettings.xsd",
            "method": "GET",
            "header": [
              {
                "key": "Api-Version",
                "value": "{}",
                "description": "The version of the api to target",
                "disabled": false
              },
              {
                "key": "Authorization",
                "value": "{}",
                "description": "The OAuth 1 authorization header",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns the HmrcSettings schema object"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "183a8fd0-b19c-4784-b778-bf46177a9e27"
            }
          ]
        }
      ]
    }
  ]
}