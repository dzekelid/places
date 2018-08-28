---
swagger: "2.0"
x-collection-name: Twitter
x-complete: 0
info:
  title: Twitter Get Places
  description: Create a new place object at the given latitude and logitude
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
  /geo/reverse_geoncode:
    get:
      summary: Get Lat / Log
      description: Given a latitude and a longitude, searches for up to 20 places
        that can be used as a place_id when updatting a status
      operationId: given-a-latitude-and-a-longitude-searches-for-up-to-20-places-that-can-be-used-as-a-place-id-when-up
      x-api-path-slug: georeverse-geoncode-get
      parameters:
      - in: query
        name: accuracy
        description: A hint on region in which to search
      - in: query
        name: callback
        description: If supplied, the responses will use the JSON format with a callback
          of the given name
      - in: query
        name: granularity
        description: This is the minimal granularity of place types to return
      - in: query
        name: lat
        description: The latitude to search around
      - in: query
        name: long
        description: The longtitude to search around
      - in: query
        name: max_results
        description: A hint as to the number of results to return
      responses:
        200:
          description: OK
      tags:
      - Places
      - Search
  /geo/search:
    get:
      summary: Geo Search
      description: Search for places that can be attached to a statuses/updates
      operationId: search-for-places-that-can-be-attached-to-a-statusesupdates
      x-api-path-slug: geosearch-get
      parameters:
      - in: query
        name: accuracy
        description: A hint on region in which to search
      - in: query
        name: attribute:street_address
        description: This parameter searches for places which have this givven street
          address
      - in: query
        name: callback
        description: If supplied, the responses will use the JSON format with a callback
          of the given name
      - in: query
        name: contained_within
        description: This is the place_id which you would like to restrict the search
          results to
      - in: query
        name: granularity
        description: This is the minimal granularity of place types to return
      - in: query
        name: ip
        description: An Ip address
      - in: query
        name: lat
        description: The latitude to search around
      - in: query
        name: long
        description: The longtitude to search around
      - in: query
        name: query
        description: Free-form text to match against while executing a geo-based query
      responses:
        200:
          description: OK
      tags:
      - Places
      - Similar
  /geo/similar_places:
    get:
      summary: Get Similar Places
      description: Locates places near the given coordinates which are similar in
        name
      operationId: locates-places-near-the-given-coordinates-which-are-similar-in-name
      x-api-path-slug: geosimilar-places-get
      parameters:
      - in: query
        name: attribute:street_address
        description: This parameter searches for places which have this givven street
          address
      - in: query
        name: callback
        description: If supplied, the responses will use the JSON format with a callback
          of the given name
      - in: query
        name: contained_within
        description: This is the place_id which you would like to restrict the search
          results to
      - in: query
        name: lat
        description: The latitude to search around
      - in: query
        name: long
        description: The longtitude to search around
      - in: query
        name: name
        description: The name a place is known as
      responses:
        200:
          description: OK
      tags:
      - Places
      - Similar
  /geo/places:
    get:
      summary: Get Places
      description: Create a new place object at the given latitude and logitude
      operationId: create-a-new-place-object-at-the-given-latitude-and-logitude
      x-api-path-slug: geoplaces-get
      parameters:
      - in: query
        name: attribute:street_address
        description: This parameter searches for places which have this givven street
          address
      - in: query
        name: callback
        description: If supplied, the responses will use the JSON format with a callback
          of the given name
      - in: query
        name: contained_within
        description: This is the place_id which you would like to restrict the search
          results to
      - in: query
        name: lat
        description: The latitude to search around
      - in: query
        name: long
        description: The longtitude to search around
      - in: query
        name: name
        description: The name a place is known as
      - in: query
        name: token
        description: The token found in the response from geo/similar_places
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