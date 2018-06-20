---
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
---