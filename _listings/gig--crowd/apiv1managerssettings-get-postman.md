{
  "info": {
    "name": "GIGANDCROWD Get Managers Settings",
    "_postman_id": "e21cdeb4-7de9-4779-b7fd-d8868d01457a",
    "description": "Get managers settings.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Managers",
      "item": [
        {
          "id": "97d239c4-0669-494a-82bd-2051f3043bf1",
          "name": "getApiV1ManagersSettings",
          "request": {
            "url": "http://gigandcrowd.com/api/v1/managers/settings",
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "{}",
                "description": "",
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
            "description": "Get managers settings."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "34596cb6-a36c-4c07-b90b-6f23ffe7f064"
            }
          ]
        }
      ]
    }
  ]
}