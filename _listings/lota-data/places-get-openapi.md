---
swagger: "2.0"
x-collection-name: Lota Data
x-complete: 0
info:
  title: Lota Data Get Places
  description: Venues, landmarks, regions, these are all places to search..
  version: 2.0.0
host: api2.lotadata.com
basePath: /v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /places:
    get:
      summary: Get Places
      description: Venues, landmarks, regions, these are all places to search..
      operationId: places.get
      x-api-path-slug: places-get
      parameters:
      - in: query
        name: ambience
        description: List of required ambience ids
      - in: query
        name: bbox
        description: Corner of a bounding box (lat,lng)
      - in: query
        name: capacity_max
        description: Min capacity at location
      - in: query
        name: capacity_min
        description: Min capacity at location
      - in: query
        name: category
        description: List of required PlaceCategory ids (Tier 1)
      - in: query
        name: center
        description: latitude,longitude of the origin point
      - in: query
        name: country
        description: country component of the address
      - in: query
        name: exact
        description: Require an exact name match
      - in: query
        name: fieldset
        description: Return results starting at specified offset (summary, context,
          detail)
      - in: query
        name: function
        description: List of required PlaceFunction ids (Tier 2)
      - in: query
        name: limit
        description: Max results to return
      - in: query
        name: locality
        description: city, town, or neighborhood of the place
      - in: query
        name: name
        description: Match on place names
      - in: query
        name: offset
        description: Return results starting at specified offset
      - in: query
        name: polygon
        description: Closed custom polygon
      - in: query
        name: postal_code
        description: Postal or zip code
      - in: query
        name: radius
        description: Distance from origin in meters
      - in: query
        name: region
        description: region or state
      - in: query
        name: street
        description: Address of the place or street component of the address
      - in: query
        name: tag
        description: List of required tags
      - in: query
        name: type
        description: Specific PlaceType to return
      - in: query
        name: within
        description: Search within specified geopolitical place id
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