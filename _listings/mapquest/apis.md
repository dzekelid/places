---
name: MapQuest
x-slug: mapquest
description: Official MapQuest website, find driving directions, maps, live traffic
  updates and road conditions.  Find nearby businesses, restaurants and hotels. Explore!
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/365-mapquest.jpg
x-kinRank: "10"
x-alexaRank: "2843"
tags: Places
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/mapquest/apis.md
specificationVersion: "0.14"
apis:
- name: 'MapQuest Search API: Place Search - Search for places with optional geographic
    and categorical contexts.'
  x-api-slug: searchv4place-get
  description: Get a list of search results ordered by relevance or distance from
    a spatial reference point, optionally filtered by category, and optionally bounded
    within a geographic constraint.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/365-mapquest.jpg
  humanURL: http://mapquest.com
  baseURL: https://www.mapquestapi.com//
  tags: Display, Directions, Openstreetmap, Display, Openstreetmap, Directions, Openstreetmap,
    Elevation, Openstreetmap, GPS, Mobile, Navigation, Openstreetmap, Directions,
    Display, HTTP POST, Places, Display, Traffic, Geo, Mapping, Stack Network, internet,
    Technology, API Provider, Viewers, Viewers, Geo, Geo, Geo, Profiles, Routes, General
    Data, Relative Data, Locations, Locations, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/mapquest/searchv4place-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/places/master/_listings/mapquest/searchv4place-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://mailjet.api.gallery.streamdata.io
- type: x-api-stack
  url: http://mapquest.stack.network
- type: x-base
  url: http://open.mapquestapi.com/s
- type: x-blog
  url: http://blog.mapquest.com
- type: x-blog-rss
  url: http://blog.mapquest.com/feed/
- type: x-crunchbase
  url: https://crunchbase.com/organization/mapquest
- type: x-crunchbase
  url: http://www.crunchbase.com/company/mapquest
- type: x-developer
  url: https://developer.mapquest.com/
- type: x-developer
  url: http://www.mapquestapi.com/
- type: x-documentation
  url: https://developer.mapquest.com/documentation/
- type: x-github
  url: https://github.com/MapQuest
- type: x-openapi
  url: https://developer.mapquest.com/documentation/search-api/v4/swagger/search-v4-swagger.yaml
- type: x-pricing
  url: https://developer.mapquest.com/plans
- type: x-twitter
  url: https://twitter.com/MapQuest
- type: x-website
  url: http://mapquest.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---