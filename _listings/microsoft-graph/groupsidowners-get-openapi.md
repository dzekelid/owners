---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph List Owners
  description: List owners Retrieve a list of the group's owners. The owners are a
    set of non-admin users who are allowed to modify the group object.
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