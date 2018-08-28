swagger: "2.0"
x-collection-name: Dezrez
x-complete: 1
info:
  title: Dezrez.Rezi.Client.Api
  version: 1.0.0
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/agency/savemeetingplace:
    post:
      summary: Saves a new meeting place to that particular agency
      description: Saves a new meeting place to that particular agency.
      operationId: Agency_SaveMeetingPlaceBydataContract
      x-api-path-slug: apiagencysavemeetingplace-post
      parameters:
      - in: body
        name: dataContract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Saves
      - New
      - Meeting
      - Place
      - To
      - That
      - Particular
      - Agency
  /api/role/{id}/documentfromplaceholder:
    get:
      summary: Get a single DocumentPlaceholder which is the 'slot' the particular
        document of type+source exists within.
      description: Get a single documentplaceholder which is the 'slot' the particular
        document of type+source exists within..
      operationId: Role_DocumentFromPlaceholderByidByplaceholderTypeByplaceholderSourceTypeBygroupId
      x-api-path-slug: apiroleiddocumentfromplaceholder-get
      parameters:
      - in: query
        name: groupId
        description: Optional group id to filter placeholder for a specific group
          relating to this role
      - in: path
        name: id
        description: Role id
      - in: query
        name: placeholderSourceType
        description: Where did the document come from to fit into the placeholder
          slot
      - in: query
        name: placeholderType
        description: Which type of document placeholder slot is this
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Single
      - DocumentPlaceholder
      - Which
      - Is
      - Slot
      - Particular
      - Document
      - Of
      - Type+source
      - Exists
      - Within