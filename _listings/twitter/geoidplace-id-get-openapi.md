---
swagger: "2.0"
x-collection-name: Twitter
x-complete: 0
info:
  title: Twitter Get Place
  description: Returns all the information about a know place
  version: "1.1"
host: api.twitter.com
basePath: /1.1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /geo/id/{place_id}:
    get:
      summary: Get Place
      description: Returns all the information about a know place
      operationId: returns-all-the-information-about-a-know-place
      x-api-path-slug: geoidplace-id-get
      parameters:
      - in: path
        name: place_id
        description: A place in the world
      responses:
        200:
          description: OK
      tags:
      - Places
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---