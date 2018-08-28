{
  "info": {
    "name": "Lota Data Get Places",
    "_postman_id": "b6956203-0bc8-4640-9a26-046b17d22594",
    "description": "Venues, landmarks, regions, these are all places to search..",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Events",
      "item": [
        {
          "id": "7a895492-1024-4961-8742-74beda65e025",
          "name": "events.get",
          "request": {
            "url": "http://api2.lotadata.com/v2/events?activity=%7B%7D&ambience=%7B%7D&bbox=%7B%7D&capacity_max=%7B%7D&capacity_min=%7B%7D&category=%7B%7D&center=%7B%7D&fieldset=%7B%7D&from_day=%7B%7D&genre=%7B%7D&limit=%7B%7D&name=%7B%7D&offset=%7B%7D&polygon=%7B%7D&q=%7B%7D&radius=%7B%7D&to_day=%7B%7D&within=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Find event occurrences in the area. returns results at specific place and time, event groups are expanded for every occurrence.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8d6c3cb8-7aff-49fe-aced-a0435876aa37"
            }
          ]
        },
        {
          "id": "05a8595f-2bd6-4e83-9394-cf7cd9ca3cda",
          "name": "events.id.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api2.lotadata.com",
              "path": [
                "v2",
                "events/:id"
              ],
              "query": [
                {
                  "key": "fieldset",
                  "value": "%7B%7D",
                  "disabled": false
                }
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
            "description": "Get specific event details.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5bde87a9-cd8b-405a-af28-654b13c26b03"
            }
          ]
        }
      ]
    },
    {
      "name": "Places",
      "item": [
        {
          "id": "ef21795f-234d-405f-946a-9ed91ffc182a",
          "name": "places.get",
          "request": {
            "url": "http://api2.lotadata.com/v2/places?ambience=%7B%7D&bbox=%7B%7D&capacity_max=%7B%7D&capacity_min=%7B%7D&category=%7B%7D&center=%7B%7D&country=%7B%7D&exact=%7B%7D&fieldset=%7B%7D&function=%7B%7D&limit=%7B%7D&locality=%7B%7D&name=%7B%7D&offset=%7B%7D&polygon=%7B%7D&postal_code=%7B%7D&radius=%7B%7D&region=%7B%7D&street=%7B%7D&tag=%7B%7D&type=%7B%7D&within=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Venues, landmarks, regions, these are all places to search.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e2a75ede-6d84-4254-9c11-b0ef1b4c5dfc"
            }
          ]
        }
      ]
    }
  ]
}