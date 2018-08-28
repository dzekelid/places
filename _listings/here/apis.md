---
name: HERE
x-slug: here
description: HERE Technologies enables people, enterprises and cities around the world
  to harness the power of location and create innovative solutions that make our lives
  safer and more efficient. We transform information from devices, vehicles, infrastructure
  and...
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
x-kinRank: "7"
x-alexaRank: "3011"
tags: Places
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/here/apis.md
specificationVersion: "0.14"
apis:
- name: Places API - Explore Popular Places
  x-api-slug: discoverexplore-get
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://places.demo.api.here.com//places/v1
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/here/discoverexplore-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/here/discoverexplore-get-openapi.md
- name: Places API - Explore Nearby Places
  x-api-slug: discoverhere-get
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://places.demo.api.here.com//places/v1
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/here/discoverhere-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/here/discoverhere-get-openapi.md
- name: Places API - Place Categories
  x-api-slug: categoriesplaces-get
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://places.demo.api.here.com//places/v1
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/here/categoriesplaces-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/here/categoriesplaces-get-openapi.md
- name: Places API - Place Categories
  x-api-slug: categoriesplaces-get
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://places.demo.api.here.com//places/v1
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/here/categoriesplaces-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/here/categoriesplaces-get-openapi.md
- name: Places API - Place Categories
  x-api-slug: categoriesplaces-get
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://places.demo.api.here.com//places/v1
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/here/categoriesplaces-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/here/categoriesplaces-get-openapi.md
- name: Places API - Place Categories
  x-api-slug: categoriesplaces-get
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://places.demo.api.here.com//places/v1
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/here/categoriesplaces-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/here/categoriesplaces-get-openapi.md
- name: Places API - Place Categories
  x-api-slug: categoriesplaces-get
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://places.demo.api.here.com//places/v1
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/here/categoriesplaces-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/here/categoriesplaces-get-openapi.md
- name: Places API - Place Categories
  x-api-slug: categoriesplaces-get
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://places.demo.api.here.com//places/v1
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/here/categoriesplaces-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/here/categoriesplaces-get-openapi.md
- name: Venue Maps - Places within a Venue
  x-api-slug: 1modelspoidm-7205-js-get
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://signature.venue.maps.cit.api.here.com//venues/signature
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/here/1modelspoidm-7205-js-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/here/1modelspoidm-7205-js-get-openapi.md
- name: Venue Maps - Places within a Venue
  x-api-slug: 1modelspoidm-7205-js-get
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://signature.venue.maps.cit.api.here.com//venues/signature
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/here/1modelspoidm-7205-js-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/here/1modelspoidm-7205-js-get-openapi.md
x-common:
- type: x-blog-rss
  url: https://developer.here.com/blog/feed
- type: x-github
  url: https://github.com/heremaps
- type: x-postman-collection
  url: https://github.com/heremaps/postman-collections
- type: x-api-gallery
  url: http://healthcare.gov.api.gallery.streamdata.io
- type: x-api-stack
  url: http://here.stack.network
- type: x-blog
  url: https://developer.here.com/blog
- type: x-crunchbase
  url: https://crunchbase.com/organization/here-inc
- type: x-developer
  url: https://developer.here.com
- type: x-email
  url: dirk.popp@here.com
- type: x-email
  url: sebastian.kurme@here.com
- type: x-email
  url: jordan.stark@here.com
- type: x-email
  url: amy.stupavsky@here.com
- type: x-email
  url: minna.laub@here.com
- type: x-email
  url: stefanie.sirc@here.com
- type: x-email
  url: rachel.kuta@here.com
- type: x-email
  url: laurel.davis-lyons@here.com
- type: x-email
  url: linda.bradley@here.com
- type: x-email
  url: press@here.com
- type: x-twitter
  url: https://twitter.com/here
- type: x-website
  url: https://here.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---