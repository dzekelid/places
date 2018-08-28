---
name: Transport for London Unified
x-slug: transport-for-london-unified
description: We are the integrated transport authority responsible for delivering
  Mayor of London Sadiq Khans strategy and commitments on transport. We run the day-to-day
  operation of the Capitals public transport network and manage Londons main roads.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
x-kinRank: "7"
x-alexaRank: "0"
tags: Places
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/apis.md
specificationVersion: "0.14"
apis:
- name: Transport for London Unified - Place
  x-api-slug: place-get
  description: "Gets the places that lie within the bounding box defined by the lat/lon
    of its north-west and south-east corners. optionally filters\r\n            on
    type and can strip properties for a smaller payload.."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/place-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/place-get-openapi.md
- name: Transport for London Unified - Place  Address  Streets  Postcode
  x-api-slug: placeaddressstreetspostcode-get
  description: Gets the set of streets associated with a post code..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placeaddressstreetspostcode-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placeaddressstreetspostcode-get-openapi.md
- name: Transport for London Unified - Place  Meta  Categories
  x-api-slug: placemetacategories-get
  description: Gets a list of all of the available place property categories and keys..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placemetacategories-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placemetacategories-get-openapi.md
- name: Transport for London Unified - Place  Meta  Place Types
  x-api-slug: placemetaplacetypes-get
  description: Gets a list of the available types of place..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placemetaplacetypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placemetaplacetypes-get-openapi.md
- name: Transport for London Unified - Place  Search
  x-api-slug: placesearch-get
  description: Gets all places that matches the given query.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placesearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placesearch-get-openapi.md
- name: Transport for London Unified - Place  Type types
  x-api-slug: placetypetypes-get
  description: Gets all places of a given type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placetypetypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placetypetypes-get-openapi.md
- name: Transport for London Unified - Place
  x-api-slug: placeid-get
  description: Gets the place with the given id..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placeid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placeid-get-openapi.md
- name: Transport for London Unified - Place type  At  Lat  Lon
  x-api-slug: placetypeatlatlon-get
  description: "Gets any places of the given type whose geography intersects the given
    latitude and longitude. in practice this means the place\r\n            must be
    polygonal e.g. a boroughboundary.."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placetypeatlatlon-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placetypeatlatlon-get-openapi.md
- name: Transport for London Unified - Place type overlay z  Lat  Lon wth height
  x-api-slug: placetypeoverlayzlatlonwidthheight-get
  description: Gets the place overlay for a given set of co-ordinates and a given
    width/height..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placetypeoverlayzlatlonwidthheight-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placetypeoverlayzlatlonwidthheight-get-openapi.md
- name: Transport for London Unified - Stop Point place Types
  x-api-slug: stoppointidplacetypes-get
  description: Get a list of places corresponding to a given id and place types..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/stoppointidplacetypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/stoppointidplacetypes-get-openapi.md
- name: Transport for London Unified - Place
  x-api-slug: place-get
  description: "Gets the places that lie within the bounding box defined by the lat/lon
    of its north-west and south-east corners. optionally filters\r\n            on
    type and can strip properties for a smaller payload.."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/place-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/place-get-openapi.md
- name: Transport for London Unified - Place  Address  Streets  Postcode
  x-api-slug: placeaddressstreetspostcode-get
  description: Gets the set of streets associated with a post code..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placeaddressstreetspostcode-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placeaddressstreetspostcode-get-openapi.md
- name: Transport for London Unified - Place  Meta  Categories
  x-api-slug: placemetacategories-get
  description: Gets a list of all of the available place property categories and keys..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placemetacategories-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placemetacategories-get-openapi.md
- name: Transport for London Unified - Place  Meta  Place Types
  x-api-slug: placemetaplacetypes-get
  description: Gets a list of the available types of place..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placemetaplacetypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placemetaplacetypes-get-openapi.md
- name: Transport for London Unified - Place  Search
  x-api-slug: placesearch-get
  description: Gets all places that matches the given query.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placesearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placesearch-get-openapi.md
- name: Transport for London Unified - Place  Type types
  x-api-slug: placetypetypes-get
  description: Gets all places of a given type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placetypetypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placetypetypes-get-openapi.md
- name: Transport for London Unified - Place
  x-api-slug: placeid-get
  description: Gets the place with the given id..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placeid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placeid-get-openapi.md
- name: Transport for London Unified - Place type  At  Lat  Lon
  x-api-slug: placetypeatlatlon-get
  description: "Gets any places of the given type whose geography intersects the given
    latitude and longitude. in practice this means the place\r\n            must be
    polygonal e.g. a boroughboundary.."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placetypeatlatlon-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placetypeatlatlon-get-openapi.md
- name: Transport for London Unified - Place type overlay z  Lat  Lon wth height
  x-api-slug: placetypeoverlayzlatlonwidthheight-get
  description: Gets the place overlay for a given set of co-ordinates and a given
    width/height..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placetypeoverlayzlatlonwidthheight-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placetypeoverlayzlatlonwidthheight-get-openapi.md
- name: Transport for London Unified - Stop Point place Types
  x-api-slug: stoppointidplacetypes-get
  description: Get a list of places corresponding to a given id and place types..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/stoppointidplacetypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/stoppointidplacetypes-get-openapi.md
- name: Transport for London Unified - Stop Point place Types
  x-api-slug: stoppointidplacetypes-get
  description: Get a list of places corresponding to a given id and place types..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/stoppointidplacetypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/stoppointidplacetypes-get-openapi.md
- name: Transport for London Unified - Place type overlay z  Lat  Lon wth height
  x-api-slug: placetypeoverlayzlatlonwidthheight-get
  description: Gets the place overlay for a given set of co-ordinates and a given
    width/height..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placetypeoverlayzlatlonwidthheight-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placetypeoverlayzlatlonwidthheight-get-openapi.md
- name: Transport for London Unified - Place type  At  Lat  Lon
  x-api-slug: placetypeatlatlon-get
  description: "Gets any places of the given type whose geography intersects the given
    latitude and longitude. in practice this means the place\r\n            must be
    polygonal e.g. a boroughboundary.."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placetypeatlatlon-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placetypeatlatlon-get-openapi.md
- name: Transport for London Unified - Place
  x-api-slug: placeid-get
  description: Gets the place with the given id..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placeid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placeid-get-openapi.md
- name: Transport for London Unified - Place  Type types
  x-api-slug: placetypetypes-get
  description: Gets all places of a given type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placetypetypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placetypetypes-get-openapi.md
- name: Transport for London Unified - Place  Search
  x-api-slug: placesearch-get
  description: Gets all places that matches the given query.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placesearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placesearch-get-openapi.md
- name: Transport for London Unified - Place  Meta  Place Types
  x-api-slug: placemetaplacetypes-get
  description: Gets a list of the available types of place..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placemetaplacetypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placemetaplacetypes-get-openapi.md
- name: Transport for London Unified - Place  Meta  Categories
  x-api-slug: placemetacategories-get
  description: Gets a list of all of the available place property categories and keys..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placemetacategories-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placemetacategories-get-openapi.md
- name: Transport for London Unified - Place  Address  Streets  Postcode
  x-api-slug: placeaddressstreetspostcode-get
  description: Gets the set of streets associated with a post code..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placeaddressstreetspostcode-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/placeaddressstreetspostcode-get-openapi.md
- name: Transport for London Unified - Place
  x-api-slug: place-get
  description: "Gets the places that lie within the bounding box defined by the lat/lon
    of its north-west and south-east corners. optionally filters\r\n            on
    type and can strip properties for a smaller payload.."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/place-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/transport-for-london-unified/place-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://transitfeeds.api.gallery.streamdata.io
- type: x-api-stack
  url: http://transport.for.london.unified.stack.network
- type: x-developer
  url: http://api.tfl.gov.uk
- type: x-website
  url: https://tfl.gov.uk/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---