{
  "info": {
    "name": "GIGANDCROWD Get Place Placeunique",
    "_postman_id": "a5e8e7ac-66b2-4f34-b17d-6c0cd6fdc0d1",
    "description": "Get place placeunique.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Art",
      "item": [
        {
          "id": "a62cb4ea-4219-43f9-93b3-82e9d5bfe7a7",
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
              "id": "3a409aed-1965-460e-bcbc-eb54aaa597d2"
            }
          ]
        }
      ]
    },
    {
      "name": "Event",
      "item": [
        {
          "id": "f4c54424-2a1c-433d-baae-20b035a0a3b7",
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
              "id": "359d75b1-cc3e-437a-bdea-51e84144cc55"
            }
          ]
        }
      ]
    },
    {
      "name": "Gigme",
      "item": [
        {
          "id": "948fdcd8-24ea-4194-99ca-b474af300134",
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
              "id": "8edf0e9a-3d93-4d9d-8116-e5b893ba29a5"
            }
          ]
        },
        {
          "id": "c4914b94-9d0d-403a-bbd2-64ac6ee422c0",
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
              "id": "bf3aeb9d-740c-400b-9ac1-262d395bbf0c"
            }
          ]
        },
        {
          "id": "69089613-4e16-4817-8c56-8dd324979a97",
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
              "id": "2199038f-7997-4844-b907-51b5868f15e9"
            }
          ]
        }
      ]
    },
    {
      "name": "Place",
      "item": [
        {
          "id": "5fae819a-beeb-48fa-88c1-5acb4216f152",
          "name": "getApiV1PlacePlaceunique",
          "request": {
            "url": {
              "protocol": "http",
              "host": "gigandcrowd.com",
              "path": [
                "api/v1/place/:placeUnique"
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
            "description": "Get place placeunique."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "33f79b91-5328-452e-919e-2a9e522b70b5"
            }
          ]
        }
      ]
    }
  ]
}