---
swagger: "2.0"
x-collection-name: Transport for London Unified
x-complete: 0
info:
  title: Transport for London Unified Place  Meta  Categories
  description: Gets a list of all of the available place property categories and keys..
  version: v1
host: api.tfl.gov.uk
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Place:
    get:
      summary: Place
      description: "Gets the places that lie within the bounding box defined by the
        lat/lon of its north-west and south-east corners. optionally filters\r\n            on
        type and can strip properties for a smaller payload.."
      operationId: Place_GetByGeoBox
      x-api-path-slug: place-get
      parameters:
      - in: query
        name: activeOnly
        description: An optional parameter to limit the results to active records
          only (Currently only the VariableMessageSign place type is supported)
      - in: query
        name: bbBoxpoints.neLat
      - in: query
        name: bbBoxpoints.neLon
      - in: query
        name: bbBoxpoints.swLat
      - in: query
        name: bbBoxpoints.swLon
      - in: query
        name: categories
        description: an optional list of comma separated property categories to return
          in the Places property bag
      - in: query
        name: includeChildren
        description: Defaults to false
      - in: query
        name: type
        description: place types to filter on, or null to return all types
      responses:
        200:
          description: OK
      tags:
      - Place
  /Place/Address/Streets/{Postcode}:
    get:
      summary: Place  Address  Streets  Postcode
      description: Gets the set of streets associated with a post code..
      operationId: Place_GetStreetsByPostCode
      x-api-path-slug: placeaddressstreetspostcode-get
      parameters:
      - in: query
        name: postcode
      - in: path
        name: Postcode
      - in: query
        name: postcodeInput.postcode
      responses:
        200:
          description: OK
      tags:
      - Place
      - ""
      - Ress
      - ""
      - Streets
      - ""
      - Code
  /Place/Meta/Categories:
    get:
      summary: Place  Meta  Categories
      description: Gets a list of all of the available place property categories and
        keys..
      operationId: Place_MetaCategories
      x-api-path-slug: placemetacategories-get
      responses:
        200:
          description: OK
      tags:
      - Place
      - ""
      - Meta
      - ""
      - Categories
  /Place/Meta/PlaceTypes:
    get:
      summary: Place  Meta  Place Types
      description: Gets a list of the available types of place..
      operationId: Place_MetaPlaceTypes
      x-api-path-slug: placemetaplacetypes-get
      responses:
        200:
          description: OK
      tags:
      - Place
      - ""
      - Meta
      - ""
      - Place
      - Types
  /Place/Search:
    get:
      summary: Place  Search
      description: Gets all places that matches the given query.
      operationId: Place_Search
      x-api-path-slug: placesearch-get
      parameters:
      - in: query
        name: name
        description: The name of the place, you can use the /Place/Types/{types} endpoint
          to get a list of places for a given type including their names
      - in: query
        name: types
        description: A comma-separated list of the types to return
      responses:
        200:
          description: OK
      tags:
      - Place
      - ""
      - Search
  /Place/Type/{types}:
    get:
      summary: Place  Type types
      description: Gets all places of a given type.
      operationId: Place_GetByType
      x-api-path-slug: placetypetypes-get
      parameters:
      - in: query
        name: activeOnly
        description: An optional parameter to limit the results to active records
          only (Currently only the VariableMessageSign place type is supported)
      - in: path
        name: types
        description: A comma-separated list of the types to return
      responses:
        200:
          description: OK
      tags:
      - Place
      - ""
      - Type
      - Types
  /Place/{id}:
    get:
      summary: Place
      description: Gets the place with the given id..
      operationId: Place_Get
      x-api-path-slug: placeid-get
      parameters:
      - in: path
        name: id
        description: The id of the place, you can use the /Place/Types/{types} endpoint
          to get a list of places for a given type including their ids
      - in: query
        name: includeChildren
        description: Defaults to false
      responses:
        200:
          description: OK
      tags:
      - Place
  /Place/{type}/At/{Lat}/{Lon}:
    get:
      summary: Place type  At  Lat  Lon
      description: "Gets any places of the given type whose geography intersects the
        given latitude and longitude. in practice this means the place\r\n            must
        be polygonal e.g. a boroughboundary.."
      operationId: Place_GetAt
      x-api-path-slug: placetypeatlatlon-get
      parameters:
      - in: query
        name: lat
      - in: path
        name: Lat
      - in: query
        name: location.lat
      - in: query
        name: location.lon
      - in: query
        name: lon
      - in: path
        name: Lon
      - in: path
        name: type
        description: The place type (a valid list of place types can be obtained from
          the /Place/Meta/placeTypes endpoint)
      responses:
        200:
          description: OK
      tags:
      - Place
      - Type
      - ""
      - At
      - ""
      - Lat
      - ""
      - Lon
  /Place/{type}/overlay/{z}/{Lat}/{Lon}/{width}/{height}:
    get:
      summary: Place type overlay z  Lat  Lon wth height
      description: Gets the place overlay for a given set of co-ordinates and a given
        width/height..
      operationId: Place_GetOverlay
      x-api-path-slug: placetypeoverlayzlatlonwidthheight-get
      parameters:
      - in: path
        name: height
        description: The height of the requested overlay
      - in: query
        name: lat
      - in: path
        name: Lat
      - in: query
        name: location.lat
      - in: query
        name: location.lon
      - in: query
        name: lon
      - in: path
        name: Lon
      - in: path
        name: type
        description: The place type (a valid list of place types can be obtained from
          the /Place/Meta/placeTypes endpoint)
      - in: path
        name: width
        description: The width of the requested overlay
      - in: path
        name: z
        description: The zoom level
      responses:
        200:
          description: OK
      tags:
      - Place
      - Type
      - Overlay
      - Z
      - ""
      - Lat
      - ""
      - Lon
      - Wth
      - Height
  /StopPoint/{id}/placeTypes:
    get:
      summary: Stop Point place Types
      description: Get a list of places corresponding to a given id and place types..
      operationId: StopPoint.id.placeTypes.get
      x-api-path-slug: stoppointidplacetypes-get
      parameters:
      - in: path
        name: id
        description: A naptan id for a stop point (station naptan code e
      - in: query
        name: placeTypes
        description: A comcomma-separated value representing the place types
      responses:
        200:
          description: OK
      tags:
      - Stop
      - Point
      - Place
      - Types
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