---
swagger: "2.0"
x-collection-name: MapQuest
x-complete: 0
info:
  title: MapQuest Search for places with optional geographic and categorical contexts.
  description: Get a list of search results ordered by relevance or distance from
    a spatial reference point, optionally filtered by category, and optionally bounded
    within a geographic constraint.
  version: 1.0.0
host: www.mapquestapi.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /search/v4/place:
    get:
      summary: Search for places with optional geographic and categorical contexts.
      description: Get a list of search results ordered by relevance or distance from
        a spatial reference point, optionally filtered by category, and optionally
        bounded within a geographic constraint.
      operationId: get-a-list-of-search-results-ordered-by-relevance-or-distance-from-a-spatial-reference-point-optiona
      x-api-path-slug: searchv4place-get
      parameters:
      - in: query
        name: bbox
        description: A geographic rectangle used to bound the search
      - in: query
        name: category
        description: The categories of places to search over
      - in: query
        name: circle
        description: A geographic circle used to bound the search
      - in: query
        name: corridor
        description: A collection of points defining a route used for the search
      - in: query
        name: feedback
      - in: query
        name: key
        description: A valid and authorized MapQuest API key
      - in: query
        name: limit
        description: (Deprecated
      - in: query
        name: location
        description: A geographic context used for searching, ranking, and ordering
          results
      - in: query
        name: page
        description: The page within the result set to return, where pageSize determines
          the page size
      - in: query
        name: pageSize
        description: The number of results to return per page
      - in: query
        name: q
        description: A query phrase
      - in: query
        name: sort
        description: The scheme used to order results
      responses:
        200:
          description: OK
      tags:
      - Mapping
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