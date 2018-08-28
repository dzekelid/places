swagger: "2.0"
x-collection-name: HERE
x-complete: 1
info:
  title: Weather API
  description: the-here-weather-api-provides-weather-forecasts-and-reports-on-current-weather-conditions-provides-information-on-severe-weather-alerts-provides-information-about-when-the-sun-and-moon-rise-and-set-and-the-phase-of-the-moonthis-example-set-works-with-version-1-2-4-or-higheradditional-information-can-be-found-on-developer-here-comhttpsdeveloper-here-comrestapisdocumentationweather
  version: 1.0.0
host: weather.cit.api.here.com
basePath: /weather/1.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /discover/explore:
    get:
      summary: Explore Popular Places
      description: |-
        *Request a list of popular places around a location*

        The `explore` location context can either be an explicitly given location using the `at` parameter, or implicitly defined by a user's current position or the currently visible map.



        * **at**  `latlng`
         \- Location of the central point for the places search.    e.g. `52.515,13.377`

        * **app_id**  `text`
         \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

        * **app_code**  `text`
         \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.

        * **Accept**  `header`

          Format to request from the server
      operationId: DiscoverExploreGet5
      x-api-path-slug: discoverexplore-get
      parameters:
      - in: header
        name: Accept
      - in: query
        name: app_code
      - in: query
        name: app_id
      - in: query
        name: at
      responses:
        200:
          description: OK
      tags:
      - Explore
      - Popular
      - Places
  /discover/here:
    get:
      summary: Explore Nearby Places
      description: |-
        *Request a list of places close to a location *

        The `discover/here` endpoint allow users to request a list of places near to a given point, based on a location precision parameter (in this case the `at` parameter) which must be provided. If the precision is high, the places around that point are returned in order of proximity. Otherwise a set of recommended places in the area is returned.



        * **at**  `latlng`
         \- Location of the central point for the places search.    e.g. `52.515,13.377`

        * **app_id**  `text`
         \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

        * **app_code**  `text`
         \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.

        * **Accept**  `header`

          Format to request from the server
      operationId: DiscoverHereGet
      x-api-path-slug: discoverhere-get
      parameters:
      - in: header
        name: Accept
      - in: query
        name: app_code
      - in: query
        name: app_id
      - in: query
        name: at
      responses:
        200:
          description: OK
      tags:
      - Explore
      - Nearby
      - Places
  /categories/places:
    get:
      summary: Place Categories
      description: |-
        *Request a list of place categories available for a given location*

        A place category request can be made using the `categories/places` endpoint in the request URL and specifying the  focal point using the `at` parameter.



        * **at**  `latlng`
         \- Location of the central point for the places search.    e.g. `52.515,13.377`

        * **app_id**  `text`
         \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

        * **app_code**  `text`
         \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.

        * **Accept**  `header`

          Format to request from the server
      operationId: CategoriesPlacesGet
      x-api-path-slug: categoriesplaces-get
      parameters:
      - in: header
        name: Accept
      - in: query
        name: app_code
      - in: query
        name: app_id
      - in: query
        name: at
      responses:
        200:
          description: OK
      tags:
      - Place
      - Categories
  /1/models-poi/DM_7205.js:
    get:
      summary: Places within a Venue
      description: |-
        *Request a list of the places within a venue*

        Details of the individual places to be found within a venue can be obtained by passing `models-poi` in the path of the request URL and appending the `id` of the venue in question along with associated authentication credentials.



        * **app_id**  `text`
         \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

        * **app_code**  `text`
         \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.

        * **Signature**  `text`
         \- Signature

        * **Policy**  `text`
         \- Policy

        * **Key-Pair-Id**  `text`
         \- Key-Pair-Id
      operationId: 1ModelsPoiDM7205JsGet
      x-api-path-slug: 1modelspoidm-7205-js-get
      parameters:
      - in: query
        name: app_code
      - in: query
        name: app_id
      - in: query
        name: Key-Pair-Id
      - in: query
        name: Policy
      - in: query
        name: Signature
      responses:
        200:
          description: OK
      tags:
      - Places
      - Within
      - Venue