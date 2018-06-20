{
  "info": {
    "name": "Lykke Get API Application Settings",
    "_postman_id": "4c3ec248-02b9-4cad-965c-4bd6cb2e6fe9",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "dff6951f-aabd-4092-9c0d-95c88dc0b7d6",
      "name": "ApiAccountExistGet",
      "request": {
        "url": "http://example.com/api/AccountExist?email=%7B%7D&partnerId=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Get API Account Exist"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "6626bc83-8473-487a-be79-71cf8b6317a3"
        }
      ]
    },
    {
      "id": "9900e580-bc84-4df0-b23e-4c7501f9ef74",
      "name": "ApiAllAssetDescriptionByIdGet",
      "request": {
        "url": {
          "protocol": "http",
          "host": "example.com",
          "path": [
            "api/AllAssetDescription/:id"
          ],
          "variable": [
            {
              "id": "id",
              "value": "{}",
              "type": "string"
            }
          ]
        },
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Get API All Asset Description"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "aea32f95-482d-4f06-ac3d-6dab1aa5c10b"
        }
      ]
    },
    {
      "id": "e0144ae1-56e7-4fd8-b1c3-d42ef7ec1702",
      "name": "ApiAllAssetPairRatesGet",
      "request": {
        "url": "http://example.com/api/AllAssetPairRates",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Get API All Asset Pair Rates"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "f2748ff3-56a9-460d-b27a-b4c749101f1b"
        }
      ]
    },
    {
      "id": "86fcffea-b5a8-4531-9901-f9038ff5d2f1",
      "name": "ApiAllAssetPairRatesByIdGet",
      "request": {
        "url": {
          "protocol": "http",
          "host": "example.com",
          "path": [
            "api/AllAssetPairRates/:id"
          ],
          "variable": [
            {
              "id": "id",
              "value": "{}",
              "type": "string"
            }
          ]
        },
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Get API All Asset Pair Rates"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "ab683582-289c-4a1a-9532-e0f449f8e320"
        }
      ]
    },
    {
      "id": "e454a1d8-06d6-4561-b9aa-cb19241cf77d",
      "name": "ApiAllAssetPairsGet",
      "request": {
        "url": "http://example.com/api/AllAssetPairs",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Get API All Asset Pairs"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "3c09bfe6-2ec3-4cf6-926c-b48ebd5110a1"
        }
      ]
    },
    {
      "id": "3d330bcd-b1a5-498a-a839-58591fcbd087",
      "name": "ApiAllAssetPairsByIdGet",
      "request": {
        "url": {
          "protocol": "http",
          "host": "example.com",
          "path": [
            "api/AllAssetPairs/:id"
          ],
          "variable": [
            {
              "id": "id",
              "value": "{}",
              "type": "string"
            }
          ]
        },
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Get API All Asset Pairs"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "38743009-95aa-41e4-ab8b-dcff91fa4fd6"
        }
      ]
    },
    {
      "id": "ed10b130-ade1-4a3e-ac50-6dbd33d3a4b5",
      "name": "ApiApplicationInfoGet",
      "request": {
        "url": "http://example.com/api/ApplicationInfo",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Get API Application Information"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "6979cf04-6bf9-4231-95ae-a826b105a594"
        }
      ]
    },
    {
      "id": "ec0fa0db-2df7-4c59-980b-fcc615b3d727",
      "name": "ApiAppSettingsGet",
      "request": {
        "url": "http://example.com/api/AppSettings",
        "method": "GET",
        "header": [
          {
            "key": "Authorization",
            "value": "{}",
            "description": "access token",
            "disabled": false
          }
        ],
        "body": {
          "mode": "raw"
        },
        "description": "Get API Application Settings"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "67d8d8d2-83fe-4ca5-8438-fd99bd341e8c"
        }
      ]
    }
  ]
}