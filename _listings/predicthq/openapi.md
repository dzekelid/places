swagger: "2.0"
x-collection-name: PredictHQ
x-complete: 1
info:
  title: PredictHQ API
  description: todo-add-description
  version: 1.0.0
host: api.predicthq.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/places/:
    get:
      summary: Search Places
      description: |-
        Use the below parameters to search and filter all places. Places are sorted by relevance (location or text query proximity).

        A search requires at least one of the `q`, `id`, `country` or `location` parameters.
      operationId: V1PlacesGet
      x-api-path-slug: v1places-get
      responses:
        200:
          description: OK
      tags:
      - Places