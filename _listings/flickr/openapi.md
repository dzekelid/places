swagger: "2.0"
x-collection-name: Flickr
x-complete: 1
info:
  title: Flickr
  description: explore-upload-and-organize-photos-on-flickr
  version: 1.0.0
host: api.flickr.com
basePath: /services/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/?method=flickr.places.find:
    get:
      summary: Places Find
      description: Return a list of place IDs for a query string.
      operationId: getRestMethodFlickr.places.find
      x-api-path-slug: restmethodflickr-places-find-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: format
        description: Response format
      - in: query
        name: query
        description: The query string to use for place ID lookups
      responses:
        200:
          description: OK
      tags:
      - Places
      - Find
  /rest/?method=flickr.places.findByLatLon:
    get:
      summary: Places Find By Lat Lon
      description: Return a place ID for a latitude, longitude and accuracy triple.
      operationId: getRestMethodFlickr.places.findbylatlon
      x-api-path-slug: restmethodflickr-places-findbylatlon-get
      parameters:
      - in: query
        name: accuracy
        description: Recorded accuracy level of the location information
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: format
        description: Response format
      - in: query
        name: lat
        description: The latitude whose valid range is -90 to 90
      - in: query
        name: lon
        description: The longitude whose valid range is -180 to 180
      responses:
        200:
          description: OK
      tags:
      - Places
      - FindByLatLon
  /rest/?method=flickr.places.getChildrenWithPhotosPublic:
    get:
      summary: Places Get Children With Photos Public
      description: Return a list of locations with public photos that are parented
        by a Where on Earth (WOE) or Places ID.
      operationId: getRestMethodFlickr.places.getchildrenwithphotospublic
      x-api-path-slug: restmethodflickr-places-getchildrenwithphotospublic-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: format
        description: Response format
      - in: query
        name: place_id
        description: A Flickr Places ID
      - in: query
        name: woe_id
        description: A Where On Earth (WOE) ID
      responses:
        200:
          description: OK
      tags:
      - Places
      - GetChildrenWithPhotosPublic
  /rest/?method=flickr.places.getInfo:
    get:
      summary: Places Get Info
      description: Get information about a place.
      operationId: getRestMethodFlickr.places.getinfo
      x-api-path-slug: restmethodflickr-places-getinfo-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: format
        description: Response format
      - in: query
        name: place_id
        description: A Flickr Places ID
      - in: query
        name: woe_id
        description: A Where On Earth (WOE) ID
      responses:
        200:
          description: OK
      tags:
      - Places
      - GetInfo
  /rest/?method=flickr.places.getInfoByUrl:
    get:
      summary: Places Get Info By Url
      description: Lookup information about a place, by its flickr.com/places URL.
      operationId: getRestMethodFlickr.places.getinfobyurl
      x-api-path-slug: restmethodflickr-places-getinfobyurl-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: format
        description: Response format
      - in: query
        name: url
        description: A flickr
      responses:
        200:
          description: OK
      tags:
      - Places
      - GetInfoByUrl
  /rest/?method=flickr.places.getPlaceTypes:
    get:
      summary: Places Get Place Types
      description: Fetches a list of available place types for Flickr.
      operationId: getRestMethodFlickr.places.getplacetypes
      x-api-path-slug: restmethodflickr-places-getplacetypes-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: format
        description: Response format
      responses:
        200:
          description: OK
      tags:
      - Places
      - GetPlaceTypes
  /rest/?method=flickr.places.getShapeHistory:
    get:
      summary: Places Get Shape History
      description: Return an historical list of all the shape data generated for a
        Places or Where on Earth (WOE) ID.
      operationId: getRestMethodFlickr.places.getshapehistory
      x-api-path-slug: restmethodflickr-places-getshapehistory-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: format
        description: Response format
      - in: query
        name: place_id
        description: A Flickr Places ID
      - in: query
        name: woe_id
        description: A Where On Earth (WOE) ID
      responses:
        200:
          description: OK
      tags:
      - Places
      - GetShapeHistory
  /rest/?method=flickr.places.getTopPlacesList:
    get:
      summary: Places Get Top Places List
      description: Return the top 100 most geotagged places for a day.
      operationId: getRestMethodFlickr.places.gettopplaceslist
      x-api-path-slug: restmethodflickr-places-gettopplaceslist-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: date
        description: A valid date in YYYY-MM-DD format
      - in: query
        name: format
        description: Response format
      - in: query
        name: place_id
        description: Limit your query to only those top places belonging to a specific
          Flickr Places identifier
      - in: query
        name: place_type_id
        description: The numeric ID for a specific place type to cluster photos by
      - in: query
        name: woe_id
        description: Limit your query to only those top places belonging to a specific
          Where on Earth (WOE) identifier
      responses:
        200:
          description: OK
      tags:
      - Places
      - GetTopPlacesList
  /rest/?method=flickr.places.placesForBoundingBox:
    get:
      summary: Places Places For Bounding Box
      description: Return all the locations of a matching place type for a bounding
        box.
      operationId: getRestMethodFlickr.places.placesforboundingbox
      x-api-path-slug: restmethodflickr-places-placesforboundingbox-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: bbox
        description: A comma-delimited list of 4 values defining the Bounding Box
          of the area that will be searched
      - in: query
        name: format
        description: Response format
      - in: query
        name: place_type
        description: Deprecated in favor of place_type_id
      - in: query
        name: place_type_id
        description: The numeric ID for a specific place type to cluster photos by
      responses:
        200:
          description: OK
      tags:
      - Places
      - PlacesForBoundingBox
  /rest/?method=flickr.places.placesForContacts:
    get:
      summary: Places Places For Contacts
      description: Return a list of the top 100 unique places clustered by a given
        placetype for a user's contacts.
      operationId: getRestMethodFlickr.places.placesforcontacts
      x-api-path-slug: restmethodflickr-places-placesforcontacts-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: contacts
        description: Search your contacts
      - in: query
        name: format
        description: Response format
      - in: query
        name: max_taken_date
        description: Maximum taken date
      - in: query
        name: max_upload_date
        description: Maximum upload date
      - in: query
        name: min_taken_date
        description: Minimum taken date
      - in: query
        name: min_upload_date
        description: Minimum upload date
      - in: query
        name: place_id
        description: A Flickr Places identifier to use to filter photo clusters
      - in: query
        name: place_type
        description: Deprecated in favor of place_type_id
      - in: query
        name: place_type_id
        description: The numeric ID for a specific place type to cluster photos by
      - in: query
        name: threshold
        description: The minimum number of photos that a place type must have to be
          included
      - in: query
        name: woe_id
        description: A Where on Earth (WOE) identifier to use to filter photo clusters
      responses:
        200:
          description: OK
      tags:
      - Places
      - PlacesForContacts
  /rest/?method=flickr.places.placesForTags:
    get:
      summary: Places Places For Tags
      description: Return a list of the top 100 unique places clustered by a given
        placetype for set of tags or machine tags.
      operationId: getRestMethodFlickr.places.placesfortags
      x-api-path-slug: restmethodflickr-places-placesfortags-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: format
        description: Response format
      - in: query
        name: machine_tags
        description: Machine tags
      - in: query
        name: machine_tag_mode
        description: Either any for an OR combination of tags, or all for an AND combination
      - in: query
        name: max_taken_date
        description: Maximum taken date
      - in: query
        name: max_upload_date
        description: Maximum upload date
      - in: query
        name: min_taken_date
        description: Minimum taken date
      - in: query
        name: min_upload_date
        description: Minimum upload date
      - in: query
        name: place_id
        description: A Flickr Places identifier to use to filter photo clusters
      - in: query
        name: place_type_id
        description: The numeric ID for a specific place type to cluster photos by
      - in: query
        name: tags
        description: A comma-delimited list of tags
      - in: query
        name: tag_mode
        description: Either any for an OR combination of tags, or all for an AND combination
      - in: query
        name: threshold
        description: The minimum number of photos that a place type must have to be
          included
      - in: query
        name: woe_id
        description: A Where on Earth (WOE) identifier to use to filter photo clusters
      responses:
        200:
          description: OK
      tags:
      - Places
      - PlacesForTags
  /rest/?method=flickr.places.placesForUser:
    get:
      summary: Places Places For User
      description: Return a list of the top 100 unique places clustered by a given
        placetype for a user.
      operationId: getRestMethodFlickr.places.placesforuser
      x-api-path-slug: restmethodflickr-places-placesforuser-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: format
        description: Response format
      - in: query
        name: max_taken_date
        description: Maximum taken date
      - in: query
        name: max_upload_date
        description: Maximum upload date
      - in: query
        name: min_taken_date
        description: Minimum taken date
      - in: query
        name: min_upload_date
        description: Minimum upload date
      - in: query
        name: place_id
        description: A Flickr Places identifier to use to filter photo clusters
      - in: query
        name: place_type
        description: Deprecated in favor of place_type_id
      - in: query
        name: place_type_id
        description: The numeric ID for a specific place type to cluster photos by
      - in: query
        name: threshold
        description: The minimum number of photos that a place type must have to be
          included
      - in: query
        name: woe_id
        description: A Where on Earth (WOE) identifier to use to filter photo clusters
      responses:
        200:
          description: OK
      tags:
      - Places
      - PlacesForUser
  /rest/?method=flickr.places.resolvePlaceId:
    get:
      summary: Places Resolve Place Id
      description: Find Flickr Places information by Place ID. This method has been
        deprecated. It won't be removed but you should use flickr.places.getInfo instead.
      operationId: getRestMethodFlickr.places.resolveplace
      x-api-path-slug: restmethodflickr-places-resolveplaceid-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: format
        description: Response format
      - in: query
        name: place_id
        description: A Flickr Places ID
      responses:
        200:
          description: OK
      tags:
      - Places
      - ResolvePlaceId
  /rest/?method=flickr.places.resolvePlaceURL:
    get:
      summary: Places Resolve Place U R L
      description: Find Flickr Places information by Place URL. This method has been
        deprecated. It won't be removed but you should use flickr.places.getInfo instead.
      operationId: getRestMethodFlickr.places.resolveplaceurl
      x-api-path-slug: restmethodflickr-places-resolveplaceurl-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: format
        description: Response format
      - in: query
        name: url
        description: A Flickr Places URL
      responses:
        200:
          description: OK
      tags:
      - Places
      - ResolvePlaceURL
  /rest/?method=flickr.places.tagsForPlace:
    get:
      summary: Places Tags For Place
      description: Return a list of the top 100 unique tags for a Flickr Places or
        Where on Earth (WOE) ID.
      operationId: getRestMethodFlickr.places.tagsforplace
      x-api-path-slug: restmethodflickr-places-tagsforplace-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: format
        description: Response format
      - in: query
        name: max_taken_date
        description: Maximum taken date
      - in: query
        name: max_upload_date
        description: Maximum upload date
      - in: query
        name: min_taken_date
        description: Minimum taken date
      - in: query
        name: min_upload_date
        description: Minimum upload date
      - in: query
        name: place_id
        description: A Flickr Places identifier to use to filter photo clusters
      - in: query
        name: woe_id
        description: A Where on Earth (WOE) identifier to use to filter photo clusters
      responses:
        200:
          description: OK
      tags:
      - Places
      - TagsForPlace