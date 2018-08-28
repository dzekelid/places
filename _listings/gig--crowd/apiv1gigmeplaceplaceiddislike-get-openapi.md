---
swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 0
info:
  title: GIGANDCROWD Get Gigme Place Placeid Dislike
  version: 1.0.0
  description: Get gigme place placeid dislike.
host: gigandcrowd.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/admin/place/{page}:
    get:
      summary: Get Admin Place Page
      description: Get admin place page.
      operationId: getApiV1AdminPlacePage
      x-api-path-slug: apiv1adminplacepage-get
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: page
      - in: query
        name: request.cityId
      - in: query
        name: request.isRecommended
      - in: query
        name: request.query
      - in: query
        name: request.status
      - in: query
        name: request.url
      responses:
        200:
          description: OK
      tags:
      - Admin
      - Place
      - Page
  /api/v1/admin/place/{placeId}:
    put:
      summary: Put Admin Place Placeid
      description: Put admin place placeid.
      operationId: putApiV1AdminPlacePlace
      x-api-path-slug: apiv1adminplaceplaceid-put
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: placeId
      - in: body
        name: request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Admin
      - Place
      - Placeid
    delete:
      summary: Delete Admin Place Placeid
      description: Delete admin place placeid.
      operationId: deleteApiV1AdminPlacePlace
      x-api-path-slug: apiv1adminplaceplaceid-delete
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: placeId
      responses:
        200:
          description: OK
      tags:
      - Admin
      - Place
      - Placeid
  /api/v1/admin/place:
    post:
      summary: Post Admin Place
      description: Post admin place.
      operationId: postApiV1AdminPlace
      x-api-path-slug: apiv1adminplace-post
      parameters:
      - in: header
        name: Authorization
      - in: body
        name: request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Admin
      - Place
  /api/v1/admin/place/{placeId}/thumbnail:
    post:
      summary: Post Admin Place Placeid Thumbnail
      description: Post admin place placeid thumbnail.
      operationId: postApiV1AdminPlacePlaceThumbnail
      x-api-path-slug: apiv1adminplaceplaceidthumbnail-post
      parameters:
      - in: header
        name: Authorization
      - in: query
        name: file
      responses:
        200:
          description: OK
      tags:
      - Admin
      - Place
      - Placeid
      - Thumbnail
  /api/v1/admin/place/{placeId}/photos:
    post:
      summary: Post Admin Place Placeid Photos
      description: Post admin place placeid photos.
      operationId: postApiV1AdminPlacePlacePhotos
      x-api-path-slug: apiv1adminplaceplaceidphotos-post
      parameters:
      - in: header
        name: Authorization
      - in: query
        name: file
      responses:
        200:
          description: OK
      tags:
      - Admin
      - Place
      - Placeid
      - Photos
  /api/v1/admin/place/{placeId}/photo/{photoId}:
    delete:
      summary: Delete Admin Place Placeid Photo Photoid
      description: Delete admin place placeid photo photoid.
      operationId: deleteApiV1AdminPlacePlacePhotoPhoto
      x-api-path-slug: apiv1adminplaceplaceidphotophotoid-delete
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: photoId
      - in: path
        name: placeId
      responses:
        200:
          description: OK
      tags:
      - Admin
      - Place
      - Placeid
      - Photo
      - Photoid
  /api/v1/admin/place/{placeId}/confirm:
    put:
      summary: Put Admin Place Placeid Confirm
      description: Put admin place placeid confirm.
      operationId: putApiV1AdminPlacePlaceConfirm
      x-api-path-slug: apiv1adminplaceplaceidconfirm-put
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: placeId
      responses:
        200:
          description: OK
      tags:
      - Admin
      - Place
      - Placeid
      - Confirm
  /api/v1/admin/place/tags/main:
    get:
      summary: Get Admin Place Tags Main
      description: Get admin place tags main.
      operationId: getApiV1AdminPlaceTagsMain
      x-api-path-slug: apiv1adminplacetagsmain-get
      parameters:
      - in: header
        name: Authorization
      responses:
        200:
          description: OK
      tags:
      - Admin
      - Place
      - Tags
      - Main
  /api/v1/admin/place/tags/additional:
    get:
      summary: Get Admin Place Tags Additional
      description: Get admin place tags additional.
      operationId: getApiV1AdminPlaceTagsAdditional
      x-api-path-slug: apiv1adminplacetagsadditional-get
      parameters:
      - in: header
        name: Authorization
      responses:
        200:
          description: OK
      tags:
      - Admin
      - Place
      - Tags
      - Itional
  /api/v1/admin/place/{primaryId}/merge/{secondaryId}:
    get:
      summary: Get Admin Place Primaryid Merge Secondaryid
      description: Get admin place primaryid merge secondaryid.
      operationId: getApiV1AdminPlacePrimaryMergeSecondary
      x-api-path-slug: apiv1adminplaceprimaryidmergesecondaryid-get
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: primaryId
      - in: path
        name: secondaryId
      responses:
        200:
          description: OK
      tags:
      - Admin
      - Place
      - Primaryid
      - Merge
      - Secondaryid
  /api/v1/admin/place/statistic:
    get:
      summary: Get Admin Place Statistic
      description: Get admin place statistic.
      operationId: getApiV1AdminPlaceStatistic
      x-api-path-slug: apiv1adminplacestatistic-get
      parameters:
      - in: header
        name: Authorization
      responses:
        200:
          description: OK
      tags:
      - Admin
      - Place
      - Statistic
  /api/v1/gigme/place/{placeId}/like:
    get:
      summary: Get Gigme Place Placeid Like
      description: Get gigme place placeid like.
      operationId: getApiV1GigmePlacePlaceLike
      x-api-path-slug: apiv1gigmeplaceplaceidlike-get
      parameters:
      - in: path
        name: placeId
      responses:
        200:
          description: OK
      tags:
      - Gigme
      - Place
      - Placeid
      - Like
  /api/v1/gigme/place/{placeId}/dislike:
    get:
      summary: Get Gigme Place Placeid Dislike
      description: Get gigme place placeid dislike.
      operationId: getApiV1GigmePlacePlaceDislike
      x-api-path-slug: apiv1gigmeplaceplaceiddislike-get
      parameters:
      - in: path
        name: placeId
      responses:
        200:
          description: OK
      tags:
      - Gigme
      - Place
      - Placeid
      - Dislike
  /api/v1/gigme/place/{placeUnique}:
    get:
      summary: Get Gigme Place Placeunique
      description: Get gigme place placeunique.
      operationId: getApiV1GigmePlacePlaceunique
      x-api-path-slug: apiv1gigmeplaceplaceunique-get
      parameters:
      - in: path
        name: placeUnique
      responses:
        200:
          description: OK
      tags:
      - Gigme
      - Place
      - Placeunique
  /api/v1/gigme/place/{placeId}/related:
    get:
      summary: Get Gigme Place Placeid Related
      description: Get gigme place placeid related.
      operationId: getApiV1GigmePlacePlaceRelated
      x-api-path-slug: apiv1gigmeplaceplaceidrelated-get
      parameters:
      - in: path
        name: placeId
      responses:
        200:
          description: OK
      tags:
      - Gigme
      - Place
      - Placeid
      - Related
  /api/v1/gigme/place/{placeId}/reviews/{page}/{pageSize}:
    get:
      summary: Get Gigme Place Placeid Reviews Page Pagesize
      description: Get gigme place placeid reviews page pagesize.
      operationId: getApiV1GigmePlacePlaceReviewsPagePagesize
      x-api-path-slug: apiv1gigmeplaceplaceidreviewspagepagesize-get
      parameters:
      - in: path
        name: page
      - in: path
        name: pageSize
      - in: path
        name: placeId
      responses:
        200:
          description: OK
      tags:
      - Gigme
      - Place
      - Placeid
      - Reviews
      - Page
      - Pagesize
  /api/v1/gigme/place/reviews/add:
    post:
      summary: Post Gigme Place Reviews Add
      description: Post gigme place reviews add.
      operationId: postApiV1GigmePlaceReviewsAdd
      x-api-path-slug: apiv1gigmeplacereviewsadd-post
      parameters:
      - in: body
        name: reviewRequest
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Gigme
      - Place
      - Reviews
  /api/v1/place/{placeId}:
    get:
      summary: Get Place Placeid
      description: Get place placeid.
      operationId: getApiV1PlacePlace
      x-api-path-slug: apiv1placeplaceid-get
      parameters:
      - in: path
        name: placeId
      responses:
        200:
          description: OK
      tags:
      - Place
      - Placeid
  /api/v1/place/{placeUnique}:
    get:
      summary: Get Place Placeunique
      description: Get place placeunique.
      operationId: getApiV1PlacePlaceunique
      x-api-path-slug: apiv1placeplaceunique-get
      parameters:
      - in: path
        name: placeUnique
      responses:
        200:
          description: OK
      tags:
      - Place
      - Placeunique
  /api/v1/place/{placeId}/related:
    get:
      summary: Get Place Placeid Related
      description: Get place placeid related.
      operationId: getApiV1PlacePlaceRelated
      x-api-path-slug: apiv1placeplaceidrelated-get
      parameters:
      - in: path
        name: placeId
      responses:
        200:
          description: OK
      tags:
      - Place
      - Placeid
      - Related
  /api/v1/place/search:
    get:
      summary: Get Place Search
      description: Get place search.
      operationId: getApiV1PlaceSearch
      x-api-path-slug: apiv1placesearch-get
      parameters:
      - in: query
        name: request.cities
      - in: query
        name: request.query
      responses:
        200:
          description: OK
      tags:
      - Place
      - Search
  /api/v1/place/{cityId}/search/{query}:
    get:
      summary: Get Place Cityid Search Query
      description: Get place cityid search query.
      operationId: getApiV1PlaceCitySearchQuery
      x-api-path-slug: apiv1placecityidsearchquery-get
      parameters:
      - in: path
        name: cityId
      - in: path
        name: query
      responses:
        200:
          description: OK
      tags:
      - Place
      - Cityid
      - Search
      - Query
  /api/v1/place:
    post:
      summary: Post Place
      description: Post place.
      operationId: postApiV1Place
      x-api-path-slug: apiv1place-post
      parameters:
      - in: header
        name: Authorization
      - in: body
        name: request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Place
  /api/v1/place/scheme/{placeId}:
    post:
      summary: Post Place Scheme Placeid
      description: Post place scheme placeid.
      operationId: postApiV1PlaceSchemePlace
      x-api-path-slug: apiv1placeschemeplaceid-post
      parameters:
      - in: header
        name: Authorization
      - in: query
        name: file
      responses:
        200:
          description: OK
      tags:
      - Place
      - Scheme
      - Placeid
  /api/v1/place/empty:
    post:
      summary: Post Place Empty
      description: Post place empty.
      operationId: postApiV1PlaceEmpty
      x-api-path-slug: apiv1placeempty-post
      responses:
        200:
          description: OK
      tags:
      - Place
      - Empty
  /api/v1/place/{placeId}/reviews/{page}/{pageSize}:
    get:
      summary: Get Place Placeid Reviews Page Pagesize
      description: Get place placeid reviews page pagesize.
      operationId: getApiV1PlacePlaceReviewsPagePagesize
      x-api-path-slug: apiv1placeplaceidreviewspagepagesize-get
      parameters:
      - in: path
        name: page
      - in: path
        name: pageSize
      - in: path
        name: placeId
      responses:
        200:
          description: OK
      tags:
      - Place
      - Placeid
      - Reviews
      - Page
      - Pagesize
  /api/v1/place/reviews/add:
    post:
      summary: Post Place Reviews Add
      description: Post place reviews add.
      operationId: postApiV1PlaceReviewsAdd
      x-api-path-slug: apiv1placereviewsadd-post
      parameters:
      - in: body
        name: reviewRequest
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Place
      - Reviews
  /api/v1/gigme/event/{placeId}/upcoming:
    get:
      summary: Get Gigme Event Placeid Upcoming
      description: Get gigme event placeid upcoming.
      operationId: getApiV1GigmeEventPlaceUpcoming
      x-api-path-slug: apiv1gigmeeventplaceidupcoming-get
      parameters:
      - in: path
        name: placeId
      responses:
        200:
          description: OK
      tags:
      - Gigme
      - Event
      - Placeid
      - Upcoming
  /api/v1/admin/placeReview/{page}:
    get:
      summary: Get Admin Placereview Page
      description: Get admin placereview page.
      operationId: getApiV1AdminPlacereviewPage
      x-api-path-slug: apiv1adminplacereviewpage-get
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: page
      - in: query
        name: request.placeName
      - in: query
        name: request.status
      responses:
        200:
          description: OK
      tags:
      - Admin
      - Placereview
      - Page
  /api/v1/admin/placeReview/{reviewId}/confirm:
    post:
      summary: Post Admin Placereview Reviewid Confirm
      description: Post admin placereview reviewid confirm.
      operationId: postApiV1AdminPlacereviewReviewConfirm
      x-api-path-slug: apiv1adminplacereviewreviewidconfirm-post
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: reviewId
      responses:
        200:
          description: OK
      tags:
      - Admin
      - Placereview
      - Reviewid
      - Confirm
  /api/v1/admin/placeReview/{reviewId}/reject:
    post:
      summary: Post Admin Placereview Reviewid Reject
      description: Post admin placereview reviewid reject.
      operationId: postApiV1AdminPlacereviewReviewReject
      x-api-path-slug: apiv1adminplacereviewreviewidreject-post
      parameters:
      - in: header
        name: Authorization
      - in: body
        name: reason
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: reviewId
      responses:
        200:
          description: OK
      tags:
      - Admin
      - Placereview
      - Reviewid
      - Reject
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