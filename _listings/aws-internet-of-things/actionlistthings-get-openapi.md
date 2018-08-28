---
swagger: "2.0"
x-collection-name: AWS Internet of Things
x-complete: 0
info:
  title: AWS Internet of Things API List Things
  version: 1.0.0
  description: Lists your things.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateThing:
    get:
      summary: Create Thing
      description: Creates a thing record in the thing registry.
      operationId: createThing
      x-api-path-slug: actioncreatething-get
      parameters:
      - in: query
        name: attributePayload
        description: The attribute payload, which consists of up to three name/value
          pairs in a JSON document
        type: string
      - in: query
        name: thingName
        description: The name of the thing to create
        type: string
      - in: query
        name: thingTypeName
        description: The name of the thing type associated with the new thing
        type: string
      responses:
        200:
          description: OK
      tags:
      - Things
  /?Action=DeleteThing:
    get:
      summary: Delete Thing
      description: Deletes the specified thing.
      operationId: deleteThing
      x-api-path-slug: actiondeletething-get
      parameters:
      - in: query
        name: expectedVersion
        description: The expected version of the thing record in the registry
        type: string
      - in: query
        name: thingName
        description: The name of the thing to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Things
  /?Action=DescribeThing:
    get:
      summary: Describe Thing
      description: Gets information about the specified thing.
      operationId: describeThing
      x-api-path-slug: actiondescribething-get
      parameters:
      - in: query
        name: thingName
        description: The name of the thing
        type: string
      responses:
        200:
          description: OK
      tags:
      - Things
  /?Action=ListThings:
    get:
      summary: List Things
      description: Lists your things.
      operationId: listThings
      x-api-path-slug: actionlistthings-get
      parameters:
      - in: query
        name: attributeName
        description: The attribute name used to search for things
        type: string
      - in: query
        name: attributeValue
        description: The attribute value used to search for things
        type: string
      - in: query
        name: maxResults
        description: The maximum number of results to return in this operation
        type: string
      - in: query
        name: nextToken
        description: The token for the next set of results, or null if there are no
          additional results
        type: string
      - in: query
        name: thingTypeName
        description: The name of the thing type used to search for things
        type: string
      responses:
        200:
          description: OK
      tags:
      - Things
  /?Action=UpdateThing:
    get:
      summary: Update Thing
      description: Updates the data for a thing.
      operationId: updateThing
      x-api-path-slug: actionupdatething-get
      parameters:
      - in: query
        name: attributePayload
        description: A list of thing attributes, a JSON string containing name-value
          pairs
        type: string
      - in: query
        name: expectedVersion
        description: The expected version of the thing record in the registry
        type: string
      - in: query
        name: removeThingType
        description: Remove a thing type association
        type: string
      - in: query
        name: thingName
        description: The name of the thing to update
        type: string
      - in: query
        name: thingTypeName
        description: The name of the thing type
        type: string
      responses:
        200:
          description: OK
      tags:
      - Things
  /?Action=AttachThingPrincipal:
    get:
      summary: Attach Thing Principal
      description: Attaches the specified principal to the specified thing.
      operationId: attachThingPrincipal
      x-api-path-slug: actionattachthingprincipal-get
      parameters:
      - in: query
        name: principal
        description: The principal, such as a certificate or other credential
        type: string
      - in: query
        name: thingName
        description: The name of the thing
        type: string
      responses:
        200:
          description: OK
      tags:
      - Thing Principals
  /?Action=DetachThingPrincipal:
    get:
      summary: Detach Thing Principal
      description: Detaches the specified principal from the specified thing.
      operationId: detachThingPrincipal
      x-api-path-slug: actiondetachthingprincipal-get
      parameters:
      - in: query
        name: principal
        description: If the principal is a certificate, this value must be ARN of
          the certificate
        type: string
      - in: query
        name: thingName
        description: The name of the thing
        type: string
      responses:
        200:
          description: OK
      tags:
      - Thing Principals
  /?Action=ListThingPrincipals:
    get:
      summary: List Thing Principals
      description: Lists the principals associated with the specified thing.
      operationId: listThingPrincipals
      x-api-path-slug: actionlistthingprincipals-get
      parameters:
      - in: query
        name: thingName
        description: The name of the thing
        type: string
      responses:
        200:
          description: OK
      tags:
      - Thing Principals
  /?Action=CreateThingType:
    get:
      summary: Create Thing Type
      description: Creates a new thing type.
      operationId: createThingType
      x-api-path-slug: actioncreatethingtype-get
      parameters:
      - in: query
        name: thingTypeName
        description: The name of the thing type
        type: string
      - in: query
        name: thingTypeProperties
        description: The ThingTypeProperties for the thing type to create
        type: string
      responses:
        200:
          description: OK
      tags:
      - Thing Types
  /?Action=DeleteThingType:
    get:
      summary: Delete Thing Type
      description: Deletes the specified thing type.
      operationId: deleteThingType
      x-api-path-slug: actiondeletethingtype-get
      parameters:
      - in: query
        name: thingTypeName
        description: The name of the thing type
        type: string
      responses:
        200:
          description: OK
      tags:
      - Thing Types
  /?Action=DeprecateThingType:
    get:
      summary: Deprecate Thing Type
      description: Deprecates a thing type.
      operationId: deprecateThingType
      x-api-path-slug: actiondeprecatethingtype-get
      parameters:
      - in: query
        name: thingTypeName
        description: The name of the thing type to deprecate
        type: string
      - in: query
        name: undoDeprecate
        description: Whether to undeprecate a deprecated thing type
        type: string
      responses:
        200:
          description: OK
      tags:
      - Thing Types
  /?Action=DescribeThingType:
    get:
      summary: Describe Thing Type
      description: Gets information about the specified thing type.
      operationId: describeThingType
      x-api-path-slug: actiondescribethingtype-get
      parameters:
      - in: query
        name: thingTypeName
        description: The name of the thing type
        type: string
      responses:
        200:
          description: OK
      tags:
      - Thing Types
  /?Action=ListThingTypes:
    get:
      summary: List Thing Types
      description: Lists the existing thing types.
      operationId: listThingTypes
      x-api-path-slug: actionlistthingtypes-get
      parameters:
      - in: query
        name: maxResults
        description: The maximum number of results to return in this operation
        type: string
      - in: query
        name: nextToken
        description: The token for the next set of results, or null if there are no
          additional results
        type: string
      - in: query
        name: thingTypeName
        description: The name of the thing type
        type: string
      responses:
        200:
          description: OK
      tags:
      - Thing Types
  /?Action=ListPrincipalThings:
    get:
      summary: List Principal Things
      description: Lists the things associated with the specified principal.
      operationId: listPrincipalThings
      x-api-path-slug: actionlistprincipalthings-get
      parameters:
      - in: query
        name: maxResults
        description: The maximum number of results to return in this operation
        type: string
      - in: query
        name: nextToken
        description: The token for the next set of results, or null if there are no
          additional results
        type: string
      - in: query
        name: principal
        description: The principal
        type: string
      responses:
        200:
          description: OK
      tags:
      - Principal Things
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