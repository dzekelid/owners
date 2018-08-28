swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 1
info:
  title: Microsoft Graph API
  description: microsoft-graph-exposes-multiple-apis-from-office-365-and-other-microsoft-cloud-services-through-a-single-endpoint-httpsgraph-microsoft-com--microsoft-graph-simplifies-queries-that-would-otherwise-be-more-complex-
  version: 1.0.0
host: graph.microsoft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /devices/{id}/registeredOwners:
    get:
      summary: List Registered Owners
      description: List registeredOwners Retrieve a list of users that are registered
        owners of the device.
      operationId: ListRegisteredOwners
      x-api-path-slug: devicesidregisteredowners-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Registered
      - Owners
    post:
      summary: Create Registered Owner
      description: Create registeredOwner Add a user as a registered owner of the
        device.
      operationId: CreateRegisteredOwner
      x-api-path-slug: devicesidregisteredowners-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Registered
      - Owner
  /groups/{id}/owners:
    get:
      summary: List Owners
      description: List owners Retrieve a list of the group's owners. The owners are
        a set of non-admin users who are allowed to modify the group object.
      operationId: ListOwners
      x-api-path-slug: groupsidowners-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Owners
  /users/{id | userPrincipalName}/ownedDevices:
    get:
      summary: List Owned Devices
      description: List ownedDevices Get the list of devices that are owned by the
        user.
      operationId: ListOwnedDevices
      x-api-path-slug: usersid--userprincipalnameowneddevices-get
      parameters:
      - in: header
        name: Accept
        description: application/json
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Owned
      - Devices
  /users/{id | userPrincipalName}/ownedObjects:
    get:
      summary: List Owned Objects
      description: List ownedObjects Get the list of directory objects that are owned
        by the user.
      operationId: ListOwnedObjects
      x-api-path-slug: usersid--userprincipalnameownedobjects-get
      parameters:
      - in: header
        name: Accept
        description: application/json
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Owned
      - Objects
  /groups/{id}/owners/{id}/$ref:
    delete:
      summary: Remove Owner
      description: Remove owner Use this API to remove an owner from an Office 365
        group, a security group or a mail-enabled security group through the owners
        navigation property.
      operationId: RemoveOwner
      x-api-path-slug: groupsidownersidref-delete
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Remove
      - Owner
  /groups/{id}/owners/$ref:
    post:
      summary: Add Group Owner
      description: Add group owner Add a user to the group's owners. The owners are
        a set of non-admin users who are allowed to modify the group object.
      operationId: AddGroupOwner
      x-api-path-slug: groupsidownersref-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Group
      - Owner