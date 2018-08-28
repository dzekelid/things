---
swagger: "2.0"
x-collection-name: IBM Watson
x-complete: 0
info:
  title: |-
    IBM Watson IoT Platform Get the active property mappings for a specific logical interface for
    a thing type.
  description: |-
    Retrieves the active property mappings for a specific logical interface
    for the thing type.
  version: 1.0.0
basePath: /api/v0002
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /thing/types/{thingTypeId}/things:
    get:
      summary: List things
      description: "Within the Watson IoT Platform, a Thing allows you to aggregate
        one or\nmore instances of a Device or Thing together to represent a more coarse\ngrained
        object.  For example, you might aggregrate together a\ntemperature sensor,
        flow sensor and power sensor together into a Boiler. \n\nThe **/thing/types/{thingTypeId}/things**
        endpoint returns the list of\nall of the Thing instances of the specified
        type that have been created\nfor the organization in the Watson IoT Platform.
        Various query\nparameters can be used to filter, sort and page through the
        list of\nThing instances that are returned."
      operationId: within-the-watson-iot-platform-a-thing-allows-you-to-aggregate-one-ormore-instances-of-a-device-or-t
      x-api-path-slug: thingtypesthingtypeidthings-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Thing
      - Types
      - ThingTypeId
      - Things
    post:
      summary: Create a thing
      description: "Creates a thing instance of the specified type for the organization
        in\nthe Watson IoT Platform. The thing type must have a valid set of   \nInformation
        Management metadata associated with it and activated before\nany instances
        can be created."
      operationId: creates-a-thing-instance-of-the-specified-type-for-the-organization-inthe-watson-iot-platform-the-th
      x-api-path-slug: thingtypesthingtypeidthings-post
      parameters:
      - in: query
        name: No Name
      - in: body
        name: thing
        description: Thing to be created
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Thing
      - Types
      - ThingTypeId
      - Things
  /thing/types/{thingTypeId}/things/{thingId}:
    get:
      summary: Get a thing
      description: Retrieve the thing with the specified id.
      operationId: retrieve-the-thing-with-the-specified-id
      x-api-path-slug: thingtypesthingtypeidthingsthingid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Thing
      - Types
      - ThingTypeId
      - Things
      - ThingId
    put:
      summary: Update a thing
      description: "Updates the thing with the specified id. The following properties\ncan
        be updated:\n\n  - name\n  - description\n  - metadata\n  - aggregatedObjects\n\nNote
        that if the description field is omitted from the body of the\nupdate, then
        any existing description will be removed from the thing\ntype.\n  \nAny changes
        made to the values of the following properties will be\nignored:\n\n  - created\n
        \ - createdBy\n  - updated\n  - updatedBy\n  \nThe values of these properties
        are set on the server as a result of a\nsuccessful update."
      operationId: updates-the-thing-with-the-specified-id-the-following-propertiescan-be-updated---name---description-
      x-api-path-slug: thingtypesthingtypeidthingsthingid-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: Thing
        description: The JSON representation of the thing
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Thing
      - Types
      - ThingTypeId
      - Things
      - ThingId
    delete:
      summary: Delete a thing
      description: "Deletes the thing with the specified id from the organization
        in the \nWatson IoT Platform.\n\nPlease note the the delete will fail if the
        thing being deleted is \ncurrently being aggregated by other thing instances."
      operationId: deletes-the-thing-with-the-specified-id-from-the-organization-in-the-watson-iot-platformplease-note-
      x-api-path-slug: thingtypesthingtypeidthingsthingid-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Thing
      - Types
      - ThingTypeId
      - Things
      - ThingId
  /thing/types/{thingTypeId}/things/{thingId}/state/{logicalInterfaceId}:
    get:
      summary: Get the state for the thing with the specified id
      description: Retrieve the current state of the thing with the specified id.
      operationId: retrieve-the-current-state-of-the-thing-with-the-specified-id
      x-api-path-slug: thingtypesthingtypeidthingsthingidstatelogicalinterfaceid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Thing
      - Types
      - ThingTypeId
      - Things
      - ThingId
      - State
      - LogicalInterfaceId
    patch:
      summary: Perform an operation against the thing state for a logical interface
      description: |-
        Performs the specified operation against the thing state for a logical
        interface. The following values can be specified for the operation
        property:

          - reset-state

        The **reset-state** operation will reset the state of the specified
        thing instance to the default values as defined by the schema for the
        logical interface.
      operationId: performs-the-specified-operation-against-the-thing-state-for-a-logicalinterface-the-following-values
      x-api-path-slug: thingtypesthingtypeidthingsthingidstatelogicalinterfaceid-patch
      parameters:
      - in: query
        name: No Name
      - in: body
        name: Operation
        description: The JSON representation of an operation
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Thing
      - Types
      - ThingTypeId
      - Things
      - ThingId
      - State
      - LogicalInterfaceId
  /thing/types:
    get:
      summary: Query active thing types
      description: "Within the Watson IoT Platform, a Thing allows you to aggregate
        one or\nmore instances of a Device or Thing together to represent a more coarse\ngrained
        object.  For example, you might aggregrate together a temperature\nsensor,
        flow sensor and power sensor together into a Boiler. \n\nThing Types are used
        to model Things.  The Schema associated with a\nThing Type defines the type
        of objects that are aggregated togther to\nmake up an instance of a Thing.
        A Thing Type must be created in an \norganization before in instance of a
        Thing can be created.\n\nThe **/thing/types** endpoint returns the list of
        all of the active\nThing types that have been defined for the organization
        in the Watson IoT\nPlatform. Various query parameters can be used to filter,
        sort and page\nthrough the list of Thing types that are returned."
      operationId: within-the-watson-iot-platform-a-thing-allows-you-to-aggregate-one-ormore-instances-of-a-device-or-t
      x-api-path-slug: thingtypes-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Thing
      - Types
  /thing/types/{thingTypeId}:
    get:
      summary: Get an active thing type
      description: Retrieve the active thing type with the specified id.
      operationId: retrieve-the-active-thing-type-with-the-specified-id
      x-api-path-slug: thingtypesthingtypeid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Thing
      - Types
      - ThingTypeId
    patch:
      summary: Perform an operation against an active thing type
      description: |-
        Performs the specified operation against the active thing type. The
        following values can be specified for the operation property:

          - deactivate-configuration

        The **deactivate-configuration** operation will remove any active
        configuration that is currently associated with the thing type. The
        **deactivate-configuration** operation will fail if there are
        any instances of the thing type.
      operationId: performs-the-specified-operation-against-the-active-thing-type-thefollowing-values-can-be-specified-
      x-api-path-slug: thingtypesthingtypeid-patch
      parameters:
      - in: query
        name: No Name
      - in: body
        name: Thing Type Operation
        description: The JSON representation of a thing type operation
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Thing
      - Types
      - ThingTypeId
  /draft/thing/types:
    get:
      summary: Query draft thing types
      description: "Within the Watson IoT Platform, a Thing allows you to aggregate
        one or\nmore instances of a Device or Thing together to represent a more coarse\ngrained
        object.  For example, you might aggregrate together a temperature\nsensor,
        flow sensor and power sensor together into a Boiler. \n\nThing Types are used
        to model Things.  The Schema associated with a\nThing Type defines the type
        of objects that are aggregated togther to\nmake up an instance of a Thing.
        A Thing Type must be created in an \norganization before in instance of a
        Thing can be created.\n\nThe **/draft/thing/types** endpoint returns the list
        of all of the draft\nThing types that have been defined for the organization
        in the Watson IoT\nPlatform. Various query parameters can be used to filter,
        sort and page\nthrough the list of draft Thing types that are returned."
      operationId: within-the-watson-iot-platform-a-thing-allows-you-to-aggregate-one-ormore-instances-of-a-device-or-t
      x-api-path-slug: draftthingtypes-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Draft
      - Thing
      - Types
    post:
      summary: Create a draft thing type
      description: |-
        Creates a new draft thing type for the organization in the Watson IoT
        Platform.  The thing type must reference the schema definition that
        defines the structure of instances of the thing type.
      operationId: creates-a-new-draft-thing-type-for-the-organization-in-the-watson-iotplatform--the-thing-type-must-r
      x-api-path-slug: draftthingtypes-post
      parameters:
      - in: body
        name: Thing Type
        description: The JSON representation of the thing type
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Draft
      - Thing
      - Types
  /draft/thing/types/{thingTypeId}:
    get:
      summary: Get a draft thing type
      description: Retrieve the draft thing type with the specified id.
      operationId: retrieve-the-draft-thing-type-with-the-specified-id
      x-api-path-slug: draftthingtypesthingtypeid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Draft
      - Thing
      - Types
      - ThingTypeId
    put:
      summary: Update a draft thing type
      description: "Updates the draft thing type with the specified id. The following\nproperties
        can be updated:\n\n  - name\n  - description\n  - schemaId\n  - metadata\n\nNote
        that if the description field is omitted from the body of the\nupdate, then
        any existing description will be removed from the draft\nthing type.\n  \nAny
        changes made to the values of the following properties will be\nignored:\n\n
        \ - version\n  - created\n  - createdBy\n  - updated\n  - updatedBy\n  - refs\n
        \ \nThe values of these properties are set on the server as a result of a\nsuccessful
        update."
      operationId: updates-the-draft-thing-type-with-the-specified-id-the-followingproperties-can-be-updated---name---d
      x-api-path-slug: draftthingtypesthingtypeid-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: Thing Type
        description: The JSON representation of the thing type
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Draft
      - Thing
      - Types
      - ThingTypeId
    patch:
      summary: Perform an operation against a draft thing type
      description: "Performs the specified operation against the draft thing type.
        The\nfollowing values can be specified for the operation property:\n\n  -
        validate-configuration\n  - activate-configuration\n  - list-differences\n\nThe
        **validate-configuration** operation will analyze all of the \nconfiguration
        associated with the draft thing type to determine if it is\nvalid.  If the
        configuration is invalid, a list of the issues will be\nreturned in the body
        of the response.  \n \nThe **activate-configuration** operation will make
        the configuration\nassociated with the draft thing type active. The \n**activate-configuration**
        operation must have been performed against a\ndraft thing type before any
        instances of that type can be created.\n\nThe **list-differences** operation
        will return a list of the differences\nthat exist between the active configuration
        for the thing type, if any,\nand the draft configuration."
      operationId: performs-the-specified-operation-against-the-draft-thing-type-thefollowing-values-can-be-specified-f
      x-api-path-slug: draftthingtypesthingtypeid-patch
      parameters:
      - in: query
        name: No Name
      - in: body
        name: Thing Type Operation
        description: The JSON representation of a thing type operation
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Draft
      - Thing
      - Types
      - ThingTypeId
    delete:
      summary: Delete a draft thing type
      description: |-
        Deletes the draft thing type with the specified id from the organization
        in the Watson IoT Platform.

        Please note the the delete will fail if there is an active version of the
        thing type or if the thing type is currently being referenced by another
        object.
      operationId: deletes-the-draft-thing-type-with-the-specified-id-from-the-organizationin-the-watson-iot-platformpl
      x-api-path-slug: draftthingtypesthingtypeid-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Draft
      - Thing
      - Types
      - ThingTypeId
  /thing/types/{thingTypeId}/logicalinterfaces:
    get:
      summary: |-
        Get the list of active logical interfaces associated with the thing
        type
      description: |-
        Retrieve the list of active logical  interfaces that have been associated
        with the thing type.  At least one logical interface must be associated
        with the thing type before any mappings can be defined that will generate
        state for the thing.
      operationId: retrieve-the-list-of-active-logical--interfaces-that-have-been-associatedwith-the-thing-type--at-lea
      x-api-path-slug: thingtypesthingtypeidlogicalinterfaces-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Thing
      - Types
      - ThingTypeId
      - Logical interfaces
  /thing/types/{thingTypeId}/mappings:
    get:
      summary: Get the list of active property mappings for the thing type
      description: |-
        Retrieve the list of active property mappings for the specified thing
        type.  A property mapping defines how properties from state update events
        on aggregated devices or things are mapped to properties defined on a
        logical interface associated with the thing type.
      operationId: retrieve-the-list-of-active-property-mappings-for-the-specified-thingtype--a-property-mapping-define
      x-api-path-slug: thingtypesthingtypeidmappings-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Thing
      - Types
      - ThingTypeId
      - Mappings
  /thing/types/{thingTypeId}/mappings/{logicalInterfaceId}:
    get:
      summary: |-
        Get the active property mappings for a specific logical interface for
        a thing type.
      description: |-
        Retrieves the active property mappings for a specific logical interface
        for the thing type.
      operationId: retrieves-the-active-property-mappings-for-a-specific-logical-interfacefor-the-thing-type
      x-api-path-slug: thingtypesthingtypeidmappingslogicalinterfaceid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Thing
      - Types
      - ThingTypeId
      - Mappings
      - LogicalInterfaceId
  /draft/thing/types/{thingTypeId}/logicalinterfaces:
    get:
      summary: |-
        Get the list of draft logical interfaces associated with the thing
        type
      description: |-
        Retrieve the list of draft logical interfaces that have been associated
        with the draft thing type.  At least one logical interface must be
        associated with the thing type before any mappings can be defined that
        will generate state for the thing.
      operationId: retrieve-the-list-of-draft-logical-interfaces-that-have-been-associatedwith-the-draft-thing-type--at
      x-api-path-slug: draftthingtypesthingtypeidlogicalinterfaces-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Draft
      - Thing
      - Types
      - ThingTypeId
      - Logical interfaces
    post:
      summary: Associate a draft logical interface with the draft thing type
      description: |-
        Associates a draft logical interface with the specified draft thing type.
        The logical interface must already exist within the organization in the
        Watson IoT Platform.
      operationId: associates-a-draft-logical-interface-with-the-specified-draft-thing-typethe-logical-interface-must-a
      x-api-path-slug: draftthingtypesthingtypeidlogicalinterfaces-post
      parameters:
      - in: body
        name: Logical Interface
        description: The JSON representation of the draft logical interface
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Draft
      - Thing
      - Types
      - ThingTypeId
      - Logical interfaces
  /draft/thing/types/{thingTypeId}/logicalinterfaces/{logicalInterfaceId}:
    delete:
      summary: Disassociate a logical interface from the draft thing type
      description: |-
        Disassociates the draft logical interface with the specified id from the
        draft thing type.

        Please note the the delete will fail if the logical interface being
        removed from the draft thing type is referenced in the property mappings
        for the draft thing type.
      operationId: disassociates-the-draft-logical-interface-with-the-specified-id-from-thedraft-thing-typeplease-note-
      x-api-path-slug: draftthingtypesthingtypeidlogicalinterfaceslogicalinterfaceid-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Draft
      - Thing
      - Types
      - ThingTypeId
      - Logical interfaces
      - LogicalInterfaceId
  /draft/thing/types/{thingTypeId}/mappings:
    get:
      summary: Get the list of draft property mappings for the thing type
      description: |-
        Retrieve the list of draft property mappings for the specified draft
        thing type.  A property mapping defines how properties from state update
        events on aggregated devices or things are mapped to properties defined
        on a logical interface associated with the thing type.
      operationId: retrieve-the-list-of-draft-property-mappings-for-the-specified-draftthing-type--a-property-mapping-d
      x-api-path-slug: draftthingtypesthingtypeidmappings-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Draft
      - Thing
      - Types
      - ThingTypeId
      - Mappings
    post:
      summary: |-
        Create the draft property mappings for a logical interface for the thing
        type
      description: |-
        Creates the draft property mappings for a logical interface for the
        thing type.  The mapping object must specify:
        - The id for for the logical interface that the mappings are for
        - The mappings that define how to map from properties on the state
          update events to the properties on the logical interface.  The
          mappings are keyed off of the name of the internal properties of the
          thing type.
      operationId: creates-the-draft-property-mappings-for-a-logical-interface-for-thething-type--the-mapping-object-mu
      x-api-path-slug: draftthingtypesthingtypeidmappings-post
      parameters:
      - in: query
        name: No Name
      - in: body
        name: Thing Type Property Mappings
        description: The JSON representation of the thing type property mappings
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Draft
      - Thing
      - Types
      - ThingTypeId
      - Mappings
  /draft/thing/types/{thingTypeId}/mappings/{logicalInterfaceId}:
    get:
      summary: |-
        Get the draft property mappings for a specific logical interface for
        a thing type.
      description: |-
        Retrieves the draft property mappings for a specific logical interface
        for the thing type.
      operationId: retrieves-the-draft-property-mappings-for-a-specific-logical-interfacefor-the-thing-type
      x-api-path-slug: draftthingtypesthingtypeidmappingslogicalinterfaceid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Draft
      - Thing
      - Types
      - ThingTypeId
      - Mappings
      - LogicalInterfaceId
    put:
      summary: |-
        Update the property mappings for a specific logical interface for
        the thing type.
      description: |-
        Updates the property mappings for a specific logical interface
        for the draft thing type.
      operationId: updates-the-property-mappings-for-a-specific-logical-interfacefor-the-draft-thing-type
      x-api-path-slug: draftthingtypesthingtypeidmappingslogicalinterfaceid-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: Thing Type Property Mappings
        description: The JSON representation of the thing type property mappings
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Draft
      - Thing
      - Types
      - ThingTypeId
      - Mappings
      - LogicalInterfaceId
    delete:
      summary: |-
        Delete the property mappings for a specific logical interface for
        the draft thing type.
      description: |-
        Deletes the property mappings for a specific logical interface
        for the draft thing type.
      operationId: deletes-the-property-mappings-for-a-specific-logical-interfacefor-the-draft-thing-type
      x-api-path-slug: draftthingtypesthingtypeidmappingslogicalinterfaceid-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Draft
      - Thing
      - Types
      - ThingTypeId
      - Mappings
      - LogicalInterfaceId
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