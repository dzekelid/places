swagger: "2.0"
x-collection-name: Lota Data
x-complete: 1
info:
  title: Lota Data
  description: access-the-most-exhaustive-accurate-and-uptodate-collection-of-global-and-hyperlocal-geocoded-events-and-activities-across-a-wide-range-of-categories-and-genres
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
  /places/{id}:
    get:
      summary: Get Places
      description: Get specific place details.
      operationId: places.id.get
      x-api-path-slug: placesid-get
      parameters:
      - in: query
        name: fieldset
      - in: path
        name: id
        description: place @id
      responses:
        200:
          description: OK
      tags:
      - Places