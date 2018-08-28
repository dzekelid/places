swagger: "2.0"
x-collection-name: AWS EC2
x-complete: 1
info:
  title: AWS EC2 API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreatePlacementGroup:
    get:
      summary: Create Placement Group
      description: Creates a placement group that you launch cluster instances into.
      operationId: createplacementgroup
      x-api-path-slug: actioncreateplacementgroup-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: GroupName
        description: The name of the placement group
        type: string
      responses:
        200:
          description: OK
      tags:
      - Placement Group
  /?Action=DeletePlacementGroup:
    get:
      summary: Delete Placement Group
      description: Deletes the specified placement group.
      operationId: deleteplacementgroup
      x-api-path-slug: actiondeleteplacementgroup-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: GroupName.N
        description: One or more placement group names
        type: string
      responses:
        200:
          description: OK
      tags:
      - Placement Group
  /?Action=DescribePlacementGroups:
    get:
      summary: Describe Placement Groups
      description: Describes one or more of your placement groups.
      operationId: describeplacementgroups
      x-api-path-slug: actiondescribeplacementgroups-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: ZoneName.N
        description: The names of one or more Availability Zones
        type: string
      responses:
        200:
          description: OK
      tags:
      - Placement Groups
  /?Action=ModifyInstancePlacement:
    get:
      summary: Modify Instance Placement
      description: |-
        Set the instance affinity value for a specific stopped instance and modify the
                    instance tenancy setting.
      operationId: modifyinstanceplacement
      x-api-path-slug: actionmodifyinstanceplacement-get
      parameters:
      - in: query
        name: ClientToken
        description: Unique, case-sensitive identifier you provide to ensure idempotency
          of the request
        type: string
      - in: query
        name: CurrencyCode
        description: The currency in which the totalUpfrontPrice, LimitPrice,            and
          totalHourlyPrice amounts are specified
        type: string
      - in: query
        name: HostIdSet.N
        description: The ID/s of the Dedicated Host/s that the reservation will be
          associated            with
        type: string
      - in: query
        name: LimitPrice
        description: The specified limit is checked against the total upfront cost
          of the reservation            (calculated as the offerings upfront cost
          multiplied by the host count)
        type: string
      - in: query
        name: OfferingId
        description: The ID of the offering
        type: string
      responses:
        200:
          description: OK
      tags:
      - Server Instance