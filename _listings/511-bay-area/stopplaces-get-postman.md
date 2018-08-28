{
  "info": {
    "name": "Bay Area 511 Transit API Stop Places API",
    "_postman_id": "9cb21132-9482-4701-8d35-ac4c8b252d1b",
    "description": "San francisco 511 transit stop places api.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "511",
      "item": [
        {
          "id": "db81d35d-e346-4e51-9a96-031dd54e23d9",
          "name": "LinesGet",
          "request": {
            "url": "http://api.511.org/transit/lines?api_key=%7B%7D&operator_id=%7B%7D",
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
            "description": "San francisco 511 transit lines api."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0eaa8c1e-8c33-440a-ae17-e6debdcee0b5"
            }
          ]
        },
        {
          "id": "85adf45e-b3eb-468a-acd0-eefe3d00ea09",
          "name": "PatternsGet",
          "request": {
            "url": "http://api.511.org/transit/patterns?api_key=%7B%7D&operator_id=%7B%7D&pattern_id=%7B%7D",
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
            "description": "San francisco 511 transit transit patterns api."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5fe49815-953f-42b9-aeb2-5cfaac298a62"
            }
          ]
        },
        {
          "id": "c4d58ab0-3b41-4843-b765-848482c65a18",
          "name": "StopsGet",
          "request": {
            "url": "http://api.511.org/transit/stops?api_key=%7B%7D&operator_id=%7B%7D",
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
            "description": "San francisco 511 transit stops api."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7cf10b3e-9b14-43c2-ab90-9d623f5539d5"
            }
          ]
        },
        {
          "id": "a9ae2689-6cd6-4c50-ab68-1a71a417ba77",
          "name": "StopMonitoringGet",
          "request": {
            "url": "http://api.511.org/transit/StopMonitoring?agency=%7B%7D&api_key=%7B%7D&stopCode=%7B%7D",
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
            "description": "San francisco 511 transit stop monitoring api."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6ab2a774-42ca-4679-9d2a-482ab0b7ce09"
            }
          ]
        },
        {
          "id": "b3b9f702-8a38-4c2e-8852-609897f89396",
          "name": "StoptimetableGet",
          "request": {
            "url": "http://api.511.org/transit/stoptimetable?api_key=%7B%7D&MonitoringRef=%7B%7D&OperatorRef=%7B%7D",
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
            "description": "San francisco 511 transit stop timetable api."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dde331c2-2e57-4a25-aea6-d3a2233fd347"
            }
          ]
        },
        {
          "id": "99126443-7a1d-4fe7-b733-0dbcef7fa3f9",
          "name": "GeneralAnnouncementsGet",
          "request": {
            "url": "http://api.511.org/transit/GeneralAnnouncements?api_key=%7B%7D",
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
            "description": "San francisco 511 general announcements api."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0d3fc08b-e1d2-4134-b8a9-0808406744f7"
            }
          ]
        },
        {
          "id": "9d55ad4c-5304-41f3-bb1d-a43492a656f0",
          "name": "StopPlacesGet",
          "request": {
            "url": "http://api.511.org/transit/stopPlaces?api_key=%7B%7D&operator_id=%7B%7D",
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
            "description": "San francisco 511 transit stop places api."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e32cb879-43e0-4f42-8d3c-2c973d6ecee6"
            }
          ]
        }
      ]
    }
  ]
}