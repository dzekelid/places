{
  "info": {
    "name": "GIGANDCROWD Get Gigme Place Placeunique",
    "_postman_id": "f9a57403-735f-4e2c-917e-2f92eeba9f5d",
    "description": "Get gigme place placeunique.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Art",
      "item": [
        {
          "id": "b207c53c-ed99-4192-ace5-64d93ced6fe2",
          "name": "getApiV1ArtUniqueDetails",
          "request": {
            "url": {
              "protocol": "http",
              "host": "gigandcrowd.com",
              "path": [
                "api/v1/art/:unique/details"
              ],
              "variable": [
                {
                  "id": "unique",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get art unique details."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1ba5b525-b439-4375-a3b1-747f80c3410b"
            }
          ]
        }
      ]
    },
    {
      "name": "Event",
      "item": [
        {
          "id": "35073bfb-a7bb-472d-8663-98932f0e0cbb",
          "name": "getApiV1EventUniqueDetails",
          "request": {
            "url": {
              "protocol": "http",
              "host": "gigandcrowd.com",
              "path": [
                "api/v1/event/:unique/details"
              ],
              "variable": [
                {
                  "id": "unique",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get event unique details."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6a78d7ba-17ba-45ff-a526-f36bf4b195d7"
            }
          ]
        }
      ]
    },
    {
      "name": "Gigme",
      "item": [
        {
          "id": "b6ebedd6-1197-48e1-8cf1-18d4210f544b",
          "name": "getApiV1GigmeArtistUniqueDetails",
          "request": {
            "url": {
              "protocol": "http",
              "host": "gigandcrowd.com",
              "path": [
                "api/v1/gigme/artist/:unique/details"
              ],
              "variable": [
                {
                  "id": "unique",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get gigme artist unique details."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "26ed0b02-e9e9-478d-b3d6-b639e811114c"
            }
          ]
        },
        {
          "id": "79427ed1-88f6-4cd8-b78d-0ab6d86bd017",
          "name": "getApiV1GigmeEventUniqueDetails",
          "request": {
            "url": {
              "protocol": "http",
              "host": "gigandcrowd.com",
              "path": [
                "api/v1/gigme/event/:unique/details"
              ],
              "variable": [
                {
                  "id": "unique",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get gigme event unique details."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "052057c7-08fc-46c7-8f00-7113f6ccbbcc"
            }
          ]
        },
        {
          "id": "1a0ab187-3dd5-4580-a8c3-954b92d3cb5d",
          "name": "getApiV1GigmePlacePlaceunique",
          "request": {
            "url": {
              "protocol": "http",
              "host": "gigandcrowd.com",
              "path": [
                "api/v1/gigme/place/:placeUnique"
              ],
              "variable": [
                {
                  "id": "placeUnique",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get gigme place placeunique."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f24e9e13-44d3-45b5-914f-6dc2b0b75cde"
            }
          ]
        }
      ]
    }
  ]
}