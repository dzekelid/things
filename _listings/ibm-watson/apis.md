---
name: IBM Watson
x-slug: ibm-watson
description: Meet IBM Watson, a cognitive system that enables a new partnership between
  people and computers that enhances and scales human expertise. Watson has been learning
  the language of professions and is trained by experts to work across many different
  industries.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Things
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/apis.md
specificationVersion: "0.14"
apis:
- name: IBM Watson IoT Platform HTTP REST API - List things
  x-api-slug: thingtypesthingtypeidthings-get
  description: "Within the Watson IoT Platform, a Thing allows you to aggregate one
    or\nmore instances of a Device or Thing together to represent a more coarse\ngrained
    object.  For example, you might aggregrate together a\ntemperature sensor, flow
    sensor and power sensor together into a Boiler. \n\nThe **/thing/types/{thingTypeId}/things**
    endpoint returns the list of\nall of the Thing instances of the specified type
    that have been created\nfor the organization in the Watson IoT Platform. Various
    query\nparameters can be used to filter, sort and page through the list of\nThing
    instances that are returned."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthings-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Create a thing
  x-api-slug: thingtypesthingtypeidthings-post
  description: "Creates a thing instance of the specified type for the organization
    in\nthe Watson IoT Platform. The thing type must have a valid set of   \nInformation
    Management metadata associated with it and activated before\nany instances can
    be created."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthings-post-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get a thing
  x-api-slug: thingtypesthingtypeidthingsthingid-get
  description: Retrieve the thing with the specified id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthingsthingid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Update a thing
  x-api-slug: thingtypesthingtypeidthingsthingid-put
  description: "Updates the thing with the specified id. The following properties\ncan
    be updated:\n\n  - name\n  - description\n  - metadata\n  - aggregatedObjects\n\nNote
    that if the description field is omitted from the body of the\nupdate, then any
    existing description will be removed from the thing\ntype.\n  \nAny changes made
    to the values of the following properties will be\nignored:\n\n  - created\n  -
    createdBy\n  - updated\n  - updatedBy\n  \nThe values of these properties are
    set on the server as a result of a\nsuccessful update."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthingsthingid-put-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Delete a thing
  x-api-slug: thingtypesthingtypeidthingsthingid-delete
  description: "Deletes the thing with the specified id from the organization in the
    \nWatson IoT Platform.\n\nPlease note the the delete will fail if the thing being
    deleted is \ncurrently being aggregated by other thing instances."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthingsthingid-delete-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get the state for the thing with the
    specified id
  x-api-slug: thingtypesthingtypeidthingsthingidstatelogicalinterfaceid-get
  description: Retrieve the current state of the thing with the specified id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthingsthingidstatelogicalinterfaceid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Perform an operation against the thing
    state for a logical interface
  x-api-slug: thingtypesthingtypeidthingsthingidstatelogicalinterfaceid-patch
  description: |-
    Performs the specified operation against the thing state for a logical
    interface. The following values can be specified for the operation
    property:

      - reset-state

    The **reset-state** operation will reset the state of the specified
    thing instance to the default values as defined by the schema for the
    logical interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthingsthingidstatelogicalinterfaceid-patch-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Query active thing types
  x-api-slug: thingtypes-get
  description: "Within the Watson IoT Platform, a Thing allows you to aggregate one
    or\nmore instances of a Device or Thing together to represent a more coarse\ngrained
    object.  For example, you might aggregrate together a temperature\nsensor, flow
    sensor and power sensor together into a Boiler. \n\nThing Types are used to model
    Things.  The Schema associated with a\nThing Type defines the type of objects
    that are aggregated togther to\nmake up an instance of a Thing. A Thing Type must
    be created in an \norganization before in instance of a Thing can be created.\n\nThe
    **/thing/types** endpoint returns the list of all of the active\nThing types that
    have been defined for the organization in the Watson IoT\nPlatform. Various query
    parameters can be used to filter, sort and page\nthrough the list of Thing types
    that are returned."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypes-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get an active thing type
  x-api-slug: thingtypesthingtypeid-get
  description: Retrieve the active thing type with the specified id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Perform an operation against an active
    thing type
  x-api-slug: thingtypesthingtypeid-patch
  description: |-
    Performs the specified operation against the active thing type. The
    following values can be specified for the operation property:

      - deactivate-configuration

    The **deactivate-configuration** operation will remove any active
    configuration that is currently associated with the thing type. The
    **deactivate-configuration** operation will fail if there are
    any instances of the thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeid-patch-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Query draft thing types
  x-api-slug: draftthingtypes-get
  description: "Within the Watson IoT Platform, a Thing allows you to aggregate one
    or\nmore instances of a Device or Thing together to represent a more coarse\ngrained
    object.  For example, you might aggregrate together a temperature\nsensor, flow
    sensor and power sensor together into a Boiler. \n\nThing Types are used to model
    Things.  The Schema associated with a\nThing Type defines the type of objects
    that are aggregated togther to\nmake up an instance of a Thing. A Thing Type must
    be created in an \norganization before in instance of a Thing can be created.\n\nThe
    **/draft/thing/types** endpoint returns the list of all of the draft\nThing types
    that have been defined for the organization in the Watson IoT\nPlatform. Various
    query parameters can be used to filter, sort and page\nthrough the list of draft
    Thing types that are returned."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/draftthingtypes-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Create a draft thing type
  x-api-slug: draftthingtypes-post
  description: |-
    Creates a new draft thing type for the organization in the Watson IoT
    Platform.  The thing type must reference the schema definition that
    defines the structure of instances of the thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/draftthingtypes-post-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get a draft thing type
  x-api-slug: draftthingtypesthingtypeid-get
  description: Retrieve the draft thing type with the specified id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/draftthingtypesthingtypeid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Update a draft thing type
  x-api-slug: draftthingtypesthingtypeid-put
  description: "Updates the draft thing type with the specified id. The following\nproperties
    can be updated:\n\n  - name\n  - description\n  - schemaId\n  - metadata\n\nNote
    that if the description field is omitted from the body of the\nupdate, then any
    existing description will be removed from the draft\nthing type.\n  \nAny changes
    made to the values of the following properties will be\nignored:\n\n  - version\n
    \ - created\n  - createdBy\n  - updated\n  - updatedBy\n  - refs\n  \nThe values
    of these properties are set on the server as a result of a\nsuccessful update."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/draftthingtypesthingtypeid-put-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Perform an operation against a draft
    thing type
  x-api-slug: draftthingtypesthingtypeid-patch
  description: "Performs the specified operation against the draft thing type. The\nfollowing
    values can be specified for the operation property:\n\n  - validate-configuration\n
    \ - activate-configuration\n  - list-differences\n\nThe **validate-configuration**
    operation will analyze all of the \nconfiguration associated with the draft thing
    type to determine if it is\nvalid.  If the configuration is invalid, a list of
    the issues will be\nreturned in the body of the response.  \n \nThe **activate-configuration**
    operation will make the configuration\nassociated with the draft thing type active.
    The \n**activate-configuration** operation must have been performed against a\ndraft
    thing type before any instances of that type can be created.\n\nThe **list-differences**
    operation will return a list of the differences\nthat exist between the active
    configuration for the thing type, if any,\nand the draft configuration."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/draftthingtypesthingtypeid-patch-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Delete a draft thing type
  x-api-slug: draftthingtypesthingtypeid-delete
  description: |-
    Deletes the draft thing type with the specified id from the organization
    in the Watson IoT Platform.

    Please note the the delete will fail if there is an active version of the
    thing type or if the thing type is currently being referenced by another
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/draftthingtypesthingtypeid-delete-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Get the list of active logical interfaces associated with the thing
    type
  x-api-slug: thingtypesthingtypeidlogicalinterfaces-get
  description: |-
    Retrieve the list of active logical  interfaces that have been associated
    with the thing type.  At least one logical interface must be associated
    with the thing type before any mappings can be defined that will generate
    state for the thing.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidlogicalinterfaces-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get the list of active property mappings
    for the thing type
  x-api-slug: thingtypesthingtypeidmappings-get
  description: |-
    Retrieve the list of active property mappings for the specified thing
    type.  A property mapping defines how properties from state update events
    on aggregated devices or things are mapped to properties defined on a
    logical interface associated with the thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidmappings-get-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Get the active property mappings for a specific logical interface for
    a thing type.
  x-api-slug: thingtypesthingtypeidmappingslogicalinterfaceid-get
  description: |-
    Retrieves the active property mappings for a specific logical interface
    for the thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidmappingslogicalinterfaceid-get-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Get the list of draft logical interfaces associated with the thing
    type
  x-api-slug: draftthingtypesthingtypeidlogicalinterfaces-get
  description: |-
    Retrieve the list of draft logical interfaces that have been associated
    with the draft thing type.  At least one logical interface must be
    associated with the thing type before any mappings can be defined that
    will generate state for the thing.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/draftthingtypesthingtypeidlogicalinterfaces-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Associate a draft logical interface
    with the draft thing type
  x-api-slug: draftthingtypesthingtypeidlogicalinterfaces-post
  description: |-
    Associates a draft logical interface with the specified draft thing type.
    The logical interface must already exist within the organization in the
    Watson IoT Platform.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/draftthingtypesthingtypeidlogicalinterfaces-post-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Disassociate a logical interface from
    the draft thing type
  x-api-slug: draftthingtypesthingtypeidlogicalinterfaceslogicalinterfaceid-delete
  description: |-
    Disassociates the draft logical interface with the specified id from the
    draft thing type.

    Please note the the delete will fail if the logical interface being
    removed from the draft thing type is referenced in the property mappings
    for the draft thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/draftthingtypesthingtypeidlogicalinterfaceslogicalinterfaceid-delete-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get the list of draft property mappings
    for the thing type
  x-api-slug: draftthingtypesthingtypeidmappings-get
  description: |-
    Retrieve the list of draft property mappings for the specified draft
    thing type.  A property mapping defines how properties from state update
    events on aggregated devices or things are mapped to properties defined
    on a logical interface associated with the thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/draftthingtypesthingtypeidmappings-get-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Create the draft property mappings for a logical interface for the thing
    type
  x-api-slug: draftthingtypesthingtypeidmappings-post
  description: |-
    Creates the draft property mappings for a logical interface for the
    thing type.  The mapping object must specify:
    - The id for for the logical interface that the mappings are for
    - The mappings that define how to map from properties on the state
      update events to the properties on the logical interface.  The
      mappings are keyed off of the name of the internal properties of the
      thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/draftthingtypesthingtypeidmappings-post-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Get the draft property mappings for a specific logical interface for
    a thing type.
  x-api-slug: draftthingtypesthingtypeidmappingslogicalinterfaceid-get
  description: |-
    Retrieves the draft property mappings for a specific logical interface
    for the thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/draftthingtypesthingtypeidmappingslogicalinterfaceid-get-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Update the property mappings for a specific logical interface for
    the thing type.
  x-api-slug: draftthingtypesthingtypeidmappingslogicalinterfaceid-put
  description: |-
    Updates the property mappings for a specific logical interface
    for the draft thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/draftthingtypesthingtypeidmappingslogicalinterfaceid-put-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Delete the property mappings for a specific logical interface for
    the draft thing type.
  x-api-slug: draftthingtypesthingtypeidmappingslogicalinterfaceid-delete
  description: |-
    Deletes the property mappings for a specific logical interface
    for the draft thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/draftthingtypesthingtypeidmappingslogicalinterfaceid-delete-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - List things
  x-api-slug: thingtypesthingtypeidthings-get
  description: "Within the Watson IoT Platform, a Thing allows you to aggregate one
    or\nmore instances of a Device or Thing together to represent a more coarse\ngrained
    object.  For example, you might aggregrate together a\ntemperature sensor, flow
    sensor and power sensor together into a Boiler. \n\nThe **/thing/types/{thingTypeId}/things**
    endpoint returns the list of\nall of the Thing instances of the specified type
    that have been created\nfor the organization in the Watson IoT Platform. Various
    query\nparameters can be used to filter, sort and page through the list of\nThing
    instances that are returned."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthings-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Create a thing
  x-api-slug: thingtypesthingtypeidthings-post
  description: "Creates a thing instance of the specified type for the organization
    in\nthe Watson IoT Platform. The thing type must have a valid set of   \nInformation
    Management metadata associated with it and activated before\nany instances can
    be created."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthings-post-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get a thing
  x-api-slug: thingtypesthingtypeidthingsthingid-get
  description: Retrieve the thing with the specified id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthingsthingid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Update a thing
  x-api-slug: thingtypesthingtypeidthingsthingid-put
  description: "Updates the thing with the specified id. The following properties\ncan
    be updated:\n\n  - name\n  - description\n  - metadata\n  - aggregatedObjects\n\nNote
    that if the description field is omitted from the body of the\nupdate, then any
    existing description will be removed from the thing\ntype.\n  \nAny changes made
    to the values of the following properties will be\nignored:\n\n  - created\n  -
    createdBy\n  - updated\n  - updatedBy\n  \nThe values of these properties are
    set on the server as a result of a\nsuccessful update."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthingsthingid-put-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Delete a thing
  x-api-slug: thingtypesthingtypeidthingsthingid-delete
  description: "Deletes the thing with the specified id from the organization in the
    \nWatson IoT Platform.\n\nPlease note the the delete will fail if the thing being
    deleted is \ncurrently being aggregated by other thing instances."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthingsthingid-delete-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get the state for the thing with the
    specified id
  x-api-slug: thingtypesthingtypeidthingsthingidstatelogicalinterfaceid-get
  description: Retrieve the current state of the thing with the specified id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthingsthingidstatelogicalinterfaceid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Perform an operation against the thing
    state for a logical interface
  x-api-slug: thingtypesthingtypeidthingsthingidstatelogicalinterfaceid-patch
  description: |-
    Performs the specified operation against the thing state for a logical
    interface. The following values can be specified for the operation
    property:

      - reset-state

    The **reset-state** operation will reset the state of the specified
    thing instance to the default values as defined by the schema for the
    logical interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthingsthingidstatelogicalinterfaceid-patch-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get a thing
  x-api-slug: thingtypesthingtypeidthingsthingid-get
  description: Retrieve the thing with the specified id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthingsthingid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Update a thing
  x-api-slug: thingtypesthingtypeidthingsthingid-put
  description: "Updates the thing with the specified id. The following properties\ncan
    be updated:\n\n  - name\n  - description\n  - metadata\n  - aggregatedObjects\n\nNote
    that if the description field is omitted from the body of the\nupdate, then any
    existing description will be removed from the thing\ntype.\n  \nAny changes made
    to the values of the following properties will be\nignored:\n\n  - created\n  -
    createdBy\n  - updated\n  - updatedBy\n  \nThe values of these properties are
    set on the server as a result of a\nsuccessful update."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthingsthingid-put-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Delete a thing
  x-api-slug: thingtypesthingtypeidthingsthingid-delete
  description: "Deletes the thing with the specified id from the organization in the
    \nWatson IoT Platform.\n\nPlease note the the delete will fail if the thing being
    deleted is \ncurrently being aggregated by other thing instances."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthingsthingid-delete-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get the state for the thing with the
    specified id
  x-api-slug: thingtypesthingtypeidthingsthingidstatelogicalinterfaceid-get
  description: Retrieve the current state of the thing with the specified id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthingsthingidstatelogicalinterfaceid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Perform an operation against the thing
    state for a logical interface
  x-api-slug: thingtypesthingtypeidthingsthingidstatelogicalinterfaceid-patch
  description: |-
    Performs the specified operation against the thing state for a logical
    interface. The following values can be specified for the operation
    property:

      - reset-state

    The **reset-state** operation will reset the state of the specified
    thing instance to the default values as defined by the schema for the
    logical interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthingsthingidstatelogicalinterfaceid-patch-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Query active thing types
  x-api-slug: thingtypes-get
  description: "Within the Watson IoT Platform, a Thing allows you to aggregate one
    or\nmore instances of a Device or Thing together to represent a more coarse\ngrained
    object.  For example, you might aggregrate together a temperature\nsensor, flow
    sensor and power sensor together into a Boiler. \n\nThing Types are used to model
    Things.  The Schema associated with a\nThing Type defines the type of objects
    that are aggregated togther to\nmake up an instance of a Thing. A Thing Type must
    be created in an \norganization before in instance of a Thing can be created.\n\nThe
    **/thing/types** endpoint returns the list of all of the active\nThing types that
    have been defined for the organization in the Watson IoT\nPlatform. Various query
    parameters can be used to filter, sort and page\nthrough the list of Thing types
    that are returned."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypes-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get an active thing type
  x-api-slug: thingtypesthingtypeid-get
  description: Retrieve the active thing type with the specified id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Perform an operation against an active
    thing type
  x-api-slug: thingtypesthingtypeid-patch
  description: |-
    Performs the specified operation against the active thing type. The
    following values can be specified for the operation property:

      - deactivate-configuration

    The **deactivate-configuration** operation will remove any active
    configuration that is currently associated with the thing type. The
    **deactivate-configuration** operation will fail if there are
    any instances of the thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeid-patch-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Query draft thing types
  x-api-slug: draftthingtypes-get
  description: "Within the Watson IoT Platform, a Thing allows you to aggregate one
    or\nmore instances of a Device or Thing together to represent a more coarse\ngrained
    object.  For example, you might aggregrate together a temperature\nsensor, flow
    sensor and power sensor together into a Boiler. \n\nThing Types are used to model
    Things.  The Schema associated with a\nThing Type defines the type of objects
    that are aggregated togther to\nmake up an instance of a Thing. A Thing Type must
    be created in an \norganization before in instance of a Thing can be created.\n\nThe
    **/draft/thing/types** endpoint returns the list of all of the draft\nThing types
    that have been defined for the organization in the Watson IoT\nPlatform. Various
    query parameters can be used to filter, sort and page\nthrough the list of draft
    Thing types that are returned."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/draftthingtypes-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Create a draft thing type
  x-api-slug: draftthingtypes-post
  description: |-
    Creates a new draft thing type for the organization in the Watson IoT
    Platform.  The thing type must reference the schema definition that
    defines the structure of instances of the thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/draftthingtypes-post-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get a draft thing type
  x-api-slug: draftthingtypesthingtypeid-get
  description: Retrieve the draft thing type with the specified id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/draftthingtypesthingtypeid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Update a draft thing type
  x-api-slug: draftthingtypesthingtypeid-put
  description: "Updates the draft thing type with the specified id. The following\nproperties
    can be updated:\n\n  - name\n  - description\n  - schemaId\n  - metadata\n\nNote
    that if the description field is omitted from the body of the\nupdate, then any
    existing description will be removed from the draft\nthing type.\n  \nAny changes
    made to the values of the following properties will be\nignored:\n\n  - version\n
    \ - created\n  - createdBy\n  - updated\n  - updatedBy\n  - refs\n  \nThe values
    of these properties are set on the server as a result of a\nsuccessful update."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/draftthingtypesthingtypeid-put-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Perform an operation against a draft
    thing type
  x-api-slug: draftthingtypesthingtypeid-patch
  description: "Performs the specified operation against the draft thing type. The\nfollowing
    values can be specified for the operation property:\n\n  - validate-configuration\n
    \ - activate-configuration\n  - list-differences\n\nThe **validate-configuration**
    operation will analyze all of the \nconfiguration associated with the draft thing
    type to determine if it is\nvalid.  If the configuration is invalid, a list of
    the issues will be\nreturned in the body of the response.  \n \nThe **activate-configuration**
    operation will make the configuration\nassociated with the draft thing type active.
    The \n**activate-configuration** operation must have been performed against a\ndraft
    thing type before any instances of that type can be created.\n\nThe **list-differences**
    operation will return a list of the differences\nthat exist between the active
    configuration for the thing type, if any,\nand the draft configuration."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/draftthingtypesthingtypeid-patch-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Delete a draft thing type
  x-api-slug: draftthingtypesthingtypeid-delete
  description: |-
    Deletes the draft thing type with the specified id from the organization
    in the Watson IoT Platform.

    Please note the the delete will fail if there is an active version of the
    thing type or if the thing type is currently being referenced by another
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/draftthingtypesthingtypeid-delete-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Get the list of active logical interfaces associated with the thing
    type
  x-api-slug: thingtypesthingtypeidlogicalinterfaces-get
  description: |-
    Retrieve the list of active logical  interfaces that have been associated
    with the thing type.  At least one logical interface must be associated
    with the thing type before any mappings can be defined that will generate
    state for the thing.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidlogicalinterfaces-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get the list of active property mappings
    for the thing type
  x-api-slug: thingtypesthingtypeidmappings-get
  description: |-
    Retrieve the list of active property mappings for the specified thing
    type.  A property mapping defines how properties from state update events
    on aggregated devices or things are mapped to properties defined on a
    logical interface associated with the thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidmappings-get-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Get the active property mappings for a specific logical interface for
    a thing type.
  x-api-slug: thingtypesthingtypeidmappingslogicalinterfaceid-get
  description: |-
    Retrieves the active property mappings for a specific logical interface
    for the thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidmappingslogicalinterfaceid-get-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Get the list of draft logical interfaces associated with the thing
    type
  x-api-slug: draftthingtypesthingtypeidlogicalinterfaces-get
  description: |-
    Retrieve the list of draft logical interfaces that have been associated
    with the draft thing type.  At least one logical interface must be
    associated with the thing type before any mappings can be defined that
    will generate state for the thing.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/draftthingtypesthingtypeidlogicalinterfaces-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Associate a draft logical interface
    with the draft thing type
  x-api-slug: draftthingtypesthingtypeidlogicalinterfaces-post
  description: |-
    Associates a draft logical interface with the specified draft thing type.
    The logical interface must already exist within the organization in the
    Watson IoT Platform.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/draftthingtypesthingtypeidlogicalinterfaces-post-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Disassociate a logical interface from
    the draft thing type
  x-api-slug: draftthingtypesthingtypeidlogicalinterfaceslogicalinterfaceid-delete
  description: |-
    Disassociates the draft logical interface with the specified id from the
    draft thing type.

    Please note the the delete will fail if the logical interface being
    removed from the draft thing type is referenced in the property mappings
    for the draft thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/draftthingtypesthingtypeidlogicalinterfaceslogicalinterfaceid-delete-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get the list of draft property mappings
    for the thing type
  x-api-slug: draftthingtypesthingtypeidmappings-get
  description: |-
    Retrieve the list of draft property mappings for the specified draft
    thing type.  A property mapping defines how properties from state update
    events on aggregated devices or things are mapped to properties defined
    on a logical interface associated with the thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/draftthingtypesthingtypeidmappings-get-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Create the draft property mappings for a logical interface for the thing
    type
  x-api-slug: draftthingtypesthingtypeidmappings-post
  description: |-
    Creates the draft property mappings for a logical interface for the
    thing type.  The mapping object must specify:
    - The id for for the logical interface that the mappings are for
    - The mappings that define how to map from properties on the state
      update events to the properties on the logical interface.  The
      mappings are keyed off of the name of the internal properties of the
      thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/draftthingtypesthingtypeidmappings-post-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Get the draft property mappings for a specific logical interface for
    a thing type.
  x-api-slug: draftthingtypesthingtypeidmappingslogicalinterfaceid-get
  description: |-
    Retrieves the draft property mappings for a specific logical interface
    for the thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/draftthingtypesthingtypeidmappingslogicalinterfaceid-get-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Update the property mappings for a specific logical interface for
    the thing type.
  x-api-slug: draftthingtypesthingtypeidmappingslogicalinterfaceid-put
  description: |-
    Updates the property mappings for a specific logical interface
    for the draft thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/draftthingtypesthingtypeidmappingslogicalinterfaceid-put-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Delete the property mappings for a specific logical interface for
    the draft thing type.
  x-api-slug: draftthingtypesthingtypeidmappingslogicalinterfaceid-delete
  description: |-
    Deletes the property mappings for a specific logical interface
    for the draft thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/draftthingtypesthingtypeidmappingslogicalinterfaceid-delete-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - List things
  x-api-slug: thingtypesthingtypeidthings-get
  description: "Within the Watson IoT Platform, a Thing allows you to aggregate one
    or\nmore instances of a Device or Thing together to represent a more coarse\ngrained
    object.  For example, you might aggregrate together a\ntemperature sensor, flow
    sensor and power sensor together into a Boiler. \n\nThe **/thing/types/{thingTypeId}/things**
    endpoint returns the list of\nall of the Thing instances of the specified type
    that have been created\nfor the organization in the Watson IoT Platform. Various
    query\nparameters can be used to filter, sort and page through the list of\nThing
    instances that are returned."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthings-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Create a thing
  x-api-slug: thingtypesthingtypeidthings-post
  description: "Creates a thing instance of the specified type for the organization
    in\nthe Watson IoT Platform. The thing type must have a valid set of   \nInformation
    Management metadata associated with it and activated before\nany instances can
    be created."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthings-post-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get a thing
  x-api-slug: thingtypesthingtypeidthingsthingid-get
  description: Retrieve the thing with the specified id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthingsthingid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Update a thing
  x-api-slug: thingtypesthingtypeidthingsthingid-put
  description: "Updates the thing with the specified id. The following properties\ncan
    be updated:\n\n  - name\n  - description\n  - metadata\n  - aggregatedObjects\n\nNote
    that if the description field is omitted from the body of the\nupdate, then any
    existing description will be removed from the thing\ntype.\n  \nAny changes made
    to the values of the following properties will be\nignored:\n\n  - created\n  -
    createdBy\n  - updated\n  - updatedBy\n  \nThe values of these properties are
    set on the server as a result of a\nsuccessful update."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthingsthingid-put-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Delete a thing
  x-api-slug: thingtypesthingtypeidthingsthingid-delete
  description: "Deletes the thing with the specified id from the organization in the
    \nWatson IoT Platform.\n\nPlease note the the delete will fail if the thing being
    deleted is \ncurrently being aggregated by other thing instances."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthingsthingid-delete-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get the state for the thing with the
    specified id
  x-api-slug: thingtypesthingtypeidthingsthingidstatelogicalinterfaceid-get
  description: Retrieve the current state of the thing with the specified id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthingsthingidstatelogicalinterfaceid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Perform an operation against the thing
    state for a logical interface
  x-api-slug: thingtypesthingtypeidthingsthingidstatelogicalinterfaceid-patch
  description: |-
    Performs the specified operation against the thing state for a logical
    interface. The following values can be specified for the operation
    property:

      - reset-state

    The **reset-state** operation will reset the state of the specified
    thing instance to the default values as defined by the schema for the
    logical interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthingsthingidstatelogicalinterfaceid-patch-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get a thing
  x-api-slug: thingtypesthingtypeidthingsthingid-get
  description: Retrieve the thing with the specified id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthingsthingid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Update a thing
  x-api-slug: thingtypesthingtypeidthingsthingid-put
  description: "Updates the thing with the specified id. The following properties\ncan
    be updated:\n\n  - name\n  - description\n  - metadata\n  - aggregatedObjects\n\nNote
    that if the description field is omitted from the body of the\nupdate, then any
    existing description will be removed from the thing\ntype.\n  \nAny changes made
    to the values of the following properties will be\nignored:\n\n  - created\n  -
    createdBy\n  - updated\n  - updatedBy\n  \nThe values of these properties are
    set on the server as a result of a\nsuccessful update."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthingsthingid-put-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Delete a thing
  x-api-slug: thingtypesthingtypeidthingsthingid-delete
  description: "Deletes the thing with the specified id from the organization in the
    \nWatson IoT Platform.\n\nPlease note the the delete will fail if the thing being
    deleted is \ncurrently being aggregated by other thing instances."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthingsthingid-delete-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get the state for the thing with the
    specified id
  x-api-slug: thingtypesthingtypeidthingsthingidstatelogicalinterfaceid-get
  description: Retrieve the current state of the thing with the specified id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthingsthingidstatelogicalinterfaceid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Perform an operation against the thing
    state for a logical interface
  x-api-slug: thingtypesthingtypeidthingsthingidstatelogicalinterfaceid-patch
  description: |-
    Performs the specified operation against the thing state for a logical
    interface. The following values can be specified for the operation
    property:

      - reset-state

    The **reset-state** operation will reset the state of the specified
    thing instance to the default values as defined by the schema for the
    logical interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthingsthingidstatelogicalinterfaceid-patch-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Perform an operation against the thing
    state for a logical interface
  x-api-slug: thingtypesthingtypeidthingsthingidstatelogicalinterfaceid-patch
  description: |-
    Performs the specified operation against the thing state for a logical
    interface. The following values can be specified for the operation
    property:

      - reset-state

    The **reset-state** operation will reset the state of the specified
    thing instance to the default values as defined by the schema for the
    logical interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthingsthingidstatelogicalinterfaceid-patch-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get the state for the thing with the
    specified id
  x-api-slug: thingtypesthingtypeidthingsthingidstatelogicalinterfaceid-get
  description: Retrieve the current state of the thing with the specified id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthingsthingidstatelogicalinterfaceid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Delete a thing
  x-api-slug: thingtypesthingtypeidthingsthingid-delete
  description: "Deletes the thing with the specified id from the organization in the
    \nWatson IoT Platform.\n\nPlease note the the delete will fail if the thing being
    deleted is \ncurrently being aggregated by other thing instances."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthingsthingid-delete-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Update a thing
  x-api-slug: thingtypesthingtypeidthingsthingid-put
  description: "Updates the thing with the specified id. The following properties\ncan
    be updated:\n\n  - name\n  - description\n  - metadata\n  - aggregatedObjects\n\nNote
    that if the description field is omitted from the body of the\nupdate, then any
    existing description will be removed from the thing\ntype.\n  \nAny changes made
    to the values of the following properties will be\nignored:\n\n  - created\n  -
    createdBy\n  - updated\n  - updatedBy\n  \nThe values of these properties are
    set on the server as a result of a\nsuccessful update."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthingsthingid-put-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get a thing
  x-api-slug: thingtypesthingtypeidthingsthingid-get
  description: Retrieve the thing with the specified id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthingsthingid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Create a thing
  x-api-slug: thingtypesthingtypeidthings-post
  description: "Creates a thing instance of the specified type for the organization
    in\nthe Watson IoT Platform. The thing type must have a valid set of   \nInformation
    Management metadata associated with it and activated before\nany instances can
    be created."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthings-post-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - List things
  x-api-slug: thingtypesthingtypeidthings-get
  description: "Within the Watson IoT Platform, a Thing allows you to aggregate one
    or\nmore instances of a Device or Thing together to represent a more coarse\ngrained
    object.  For example, you might aggregrate together a\ntemperature sensor, flow
    sensor and power sensor together into a Boiler. \n\nThe **/thing/types/{thingTypeId}/things**
    endpoint returns the list of\nall of the Thing instances of the specified type
    that have been created\nfor the organization in the Watson IoT Platform. Various
    query\nparameters can be used to filter, sort and page through the list of\nThing
    instances that are returned."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthings-get-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Delete the property mappings for a specific logical interface for
    the draft thing type.
  x-api-slug: draftthingtypesthingtypeidmappingslogicalinterfaceid-delete
  description: |-
    Deletes the property mappings for a specific logical interface
    for the draft thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/draftthingtypesthingtypeidmappingslogicalinterfaceid-delete-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Update the property mappings for a specific logical interface for
    the thing type.
  x-api-slug: draftthingtypesthingtypeidmappingslogicalinterfaceid-put
  description: |-
    Updates the property mappings for a specific logical interface
    for the draft thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/draftthingtypesthingtypeidmappingslogicalinterfaceid-put-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Get the draft property mappings for a specific logical interface for
    a thing type.
  x-api-slug: draftthingtypesthingtypeidmappingslogicalinterfaceid-get
  description: |-
    Retrieves the draft property mappings for a specific logical interface
    for the thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/draftthingtypesthingtypeidmappingslogicalinterfaceid-get-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Create the draft property mappings for a logical interface for the thing
    type
  x-api-slug: draftthingtypesthingtypeidmappings-post
  description: |-
    Creates the draft property mappings for a logical interface for the
    thing type.  The mapping object must specify:
    - The id for for the logical interface that the mappings are for
    - The mappings that define how to map from properties on the state
      update events to the properties on the logical interface.  The
      mappings are keyed off of the name of the internal properties of the
      thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/draftthingtypesthingtypeidmappings-post-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get the list of draft property mappings
    for the thing type
  x-api-slug: draftthingtypesthingtypeidmappings-get
  description: |-
    Retrieve the list of draft property mappings for the specified draft
    thing type.  A property mapping defines how properties from state update
    events on aggregated devices or things are mapped to properties defined
    on a logical interface associated with the thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/draftthingtypesthingtypeidmappings-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Disassociate a logical interface from
    the draft thing type
  x-api-slug: draftthingtypesthingtypeidlogicalinterfaceslogicalinterfaceid-delete
  description: |-
    Disassociates the draft logical interface with the specified id from the
    draft thing type.

    Please note the the delete will fail if the logical interface being
    removed from the draft thing type is referenced in the property mappings
    for the draft thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/draftthingtypesthingtypeidlogicalinterfaceslogicalinterfaceid-delete-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Associate a draft logical interface
    with the draft thing type
  x-api-slug: draftthingtypesthingtypeidlogicalinterfaces-post
  description: |-
    Associates a draft logical interface with the specified draft thing type.
    The logical interface must already exist within the organization in the
    Watson IoT Platform.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/draftthingtypesthingtypeidlogicalinterfaces-post-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Get the list of draft logical interfaces associated with the thing
    type
  x-api-slug: draftthingtypesthingtypeidlogicalinterfaces-get
  description: |-
    Retrieve the list of draft logical interfaces that have been associated
    with the draft thing type.  At least one logical interface must be
    associated with the thing type before any mappings can be defined that
    will generate state for the thing.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/draftthingtypesthingtypeidlogicalinterfaces-get-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Get the active property mappings for a specific logical interface for
    a thing type.
  x-api-slug: thingtypesthingtypeidmappingslogicalinterfaceid-get
  description: |-
    Retrieves the active property mappings for a specific logical interface
    for the thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidmappingslogicalinterfaceid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get the list of active property mappings
    for the thing type
  x-api-slug: thingtypesthingtypeidmappings-get
  description: |-
    Retrieve the list of active property mappings for the specified thing
    type.  A property mapping defines how properties from state update events
    on aggregated devices or things are mapped to properties defined on a
    logical interface associated with the thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidmappings-get-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Get the list of active logical interfaces associated with the thing
    type
  x-api-slug: thingtypesthingtypeidlogicalinterfaces-get
  description: |-
    Retrieve the list of active logical  interfaces that have been associated
    with the thing type.  At least one logical interface must be associated
    with the thing type before any mappings can be defined that will generate
    state for the thing.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidlogicalinterfaces-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Delete a draft thing type
  x-api-slug: draftthingtypesthingtypeid-delete
  description: |-
    Deletes the draft thing type with the specified id from the organization
    in the Watson IoT Platform.

    Please note the the delete will fail if there is an active version of the
    thing type or if the thing type is currently being referenced by another
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/draftthingtypesthingtypeid-delete-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Perform an operation against a draft
    thing type
  x-api-slug: draftthingtypesthingtypeid-patch
  description: "Performs the specified operation against the draft thing type. The\nfollowing
    values can be specified for the operation property:\n\n  - validate-configuration\n
    \ - activate-configuration\n  - list-differences\n\nThe **validate-configuration**
    operation will analyze all of the \nconfiguration associated with the draft thing
    type to determine if it is\nvalid.  If the configuration is invalid, a list of
    the issues will be\nreturned in the body of the response.  \n \nThe **activate-configuration**
    operation will make the configuration\nassociated with the draft thing type active.
    The \n**activate-configuration** operation must have been performed against a\ndraft
    thing type before any instances of that type can be created.\n\nThe **list-differences**
    operation will return a list of the differences\nthat exist between the active
    configuration for the thing type, if any,\nand the draft configuration."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/draftthingtypesthingtypeid-patch-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Update a draft thing type
  x-api-slug: draftthingtypesthingtypeid-put
  description: "Updates the draft thing type with the specified id. The following\nproperties
    can be updated:\n\n  - name\n  - description\n  - schemaId\n  - metadata\n\nNote
    that if the description field is omitted from the body of the\nupdate, then any
    existing description will be removed from the draft\nthing type.\n  \nAny changes
    made to the values of the following properties will be\nignored:\n\n  - version\n
    \ - created\n  - createdBy\n  - updated\n  - updatedBy\n  - refs\n  \nThe values
    of these properties are set on the server as a result of a\nsuccessful update."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/draftthingtypesthingtypeid-put-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get a draft thing type
  x-api-slug: draftthingtypesthingtypeid-get
  description: Retrieve the draft thing type with the specified id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/draftthingtypesthingtypeid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Create a draft thing type
  x-api-slug: draftthingtypes-post
  description: |-
    Creates a new draft thing type for the organization in the Watson IoT
    Platform.  The thing type must reference the schema definition that
    defines the structure of instances of the thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/draftthingtypes-post-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Query draft thing types
  x-api-slug: draftthingtypes-get
  description: "Within the Watson IoT Platform, a Thing allows you to aggregate one
    or\nmore instances of a Device or Thing together to represent a more coarse\ngrained
    object.  For example, you might aggregrate together a temperature\nsensor, flow
    sensor and power sensor together into a Boiler. \n\nThing Types are used to model
    Things.  The Schema associated with a\nThing Type defines the type of objects
    that are aggregated togther to\nmake up an instance of a Thing. A Thing Type must
    be created in an \norganization before in instance of a Thing can be created.\n\nThe
    **/draft/thing/types** endpoint returns the list of all of the draft\nThing types
    that have been defined for the organization in the Watson IoT\nPlatform. Various
    query parameters can be used to filter, sort and page\nthrough the list of draft
    Thing types that are returned."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/draftthingtypes-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Perform an operation against an active
    thing type
  x-api-slug: thingtypesthingtypeid-patch
  description: |-
    Performs the specified operation against the active thing type. The
    following values can be specified for the operation property:

      - deactivate-configuration

    The **deactivate-configuration** operation will remove any active
    configuration that is currently associated with the thing type. The
    **deactivate-configuration** operation will fail if there are
    any instances of the thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeid-patch-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get an active thing type
  x-api-slug: thingtypesthingtypeid-get
  description: Retrieve the active thing type with the specified id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Query active thing types
  x-api-slug: thingtypes-get
  description: "Within the Watson IoT Platform, a Thing allows you to aggregate one
    or\nmore instances of a Device or Thing together to represent a more coarse\ngrained
    object.  For example, you might aggregrate together a temperature\nsensor, flow
    sensor and power sensor together into a Boiler. \n\nThing Types are used to model
    Things.  The Schema associated with a\nThing Type defines the type of objects
    that are aggregated togther to\nmake up an instance of a Thing. A Thing Type must
    be created in an \norganization before in instance of a Thing can be created.\n\nThe
    **/thing/types** endpoint returns the list of all of the active\nThing types that
    have been defined for the organization in the Watson IoT\nPlatform. Various query
    parameters can be used to filter, sort and page\nthrough the list of Thing types
    that are returned."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypes-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Perform an operation against the thing
    state for a logical interface
  x-api-slug: thingtypesthingtypeidthingsthingidstatelogicalinterfaceid-patch
  description: |-
    Performs the specified operation against the thing state for a logical
    interface. The following values can be specified for the operation
    property:

      - reset-state

    The **reset-state** operation will reset the state of the specified
    thing instance to the default values as defined by the schema for the
    logical interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthingsthingidstatelogicalinterfaceid-patch-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get the state for the thing with the
    specified id
  x-api-slug: thingtypesthingtypeidthingsthingidstatelogicalinterfaceid-get
  description: Retrieve the current state of the thing with the specified id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthingsthingidstatelogicalinterfaceid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Delete a thing
  x-api-slug: thingtypesthingtypeidthingsthingid-delete
  description: "Deletes the thing with the specified id from the organization in the
    \nWatson IoT Platform.\n\nPlease note the the delete will fail if the thing being
    deleted is \ncurrently being aggregated by other thing instances."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthingsthingid-delete-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Update a thing
  x-api-slug: thingtypesthingtypeidthingsthingid-put
  description: "Updates the thing with the specified id. The following properties\ncan
    be updated:\n\n  - name\n  - description\n  - metadata\n  - aggregatedObjects\n\nNote
    that if the description field is omitted from the body of the\nupdate, then any
    existing description will be removed from the thing\ntype.\n  \nAny changes made
    to the values of the following properties will be\nignored:\n\n  - created\n  -
    createdBy\n  - updated\n  - updatedBy\n  \nThe values of these properties are
    set on the server as a result of a\nsuccessful update."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthingsthingid-put-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get a thing
  x-api-slug: thingtypesthingtypeidthingsthingid-get
  description: Retrieve the thing with the specified id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/things/master/_listings/ibm-watson/thingtypesthingtypeidthingsthingid-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://ibm.financial.crimes.insight.for.insurance.api.gallery.streamdata.io
- type: x-api-stack
  url: http://ibm.watson.stack.network
- type: x-application-gallery
  url: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/gallery.html
- type: x-blog
  url: https://developer.ibm.com/watson/blog/
- type: x-blog-rss
  url: https://developer.ibm.com/watson/feed/
- type: x-developer
  url: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/doc/
- type: x-developer
  url: https://developer.ibm.com/watson/
- type: x-documentation
  url: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/apis/
- type: x-forum
  url: https://developer.ibm.com/answers/smartspace/watson/
- type: x-getting-started
  url: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/getstarted.html
- type: x-github
  url: https://github.com/IBM-Watson
- type: x-partners
  url: http://www.ibm.com/smarterplanet/us/en/ibmwatson/ecosystem.html
- type: x-privacy
  url: http://www.ibm.com/privacy/us/en/?lnk=flg-priv-usen
- type: x-terms-of-service
  url: http://www.ibm.com/legal/us/en/?lnk=flg-tous-usen
- type: x-twitter
  url: https://twitter.com/IBMWatson
- type: x-videos
  url: http://www.ibm.com/smarterplanet/us/en/ibmwatson/
- type: x-website
  url: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
- type: x-white-papers
  url: https://developer.ibm.com/watson/docs/whitepapers/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---