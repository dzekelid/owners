---
swagger: "2.0"
x-collection-name: Lykke
x-complete: 0
info:
  title: Lykke Add API Privatekeyownershipmsg
  version: 1.0.0
  description: Add api privatekeyownershipmsg.
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/PrivateKeyOwnershipMsg:
    get:
      summary: Get API Privatekeyownershipmsg
      description: Get api privatekeyownershipmsg.
      operationId: ApiPrivateKeyOwnershipMsgGet
      x-api-path-slug: apiprivatekeyownershipmsg-get
      parameters:
      - in: query
        name: email
      - in: query
        name: partnerId
      responses:
        200:
          description: OK
      tags:
      - Privatekeyownershipmsg
    post:
      summary: Add API Privatekeyownershipmsg
      description: Add api privatekeyownershipmsg.
      operationId: ApiPrivateKeyOwnershipMsgPost
      x-api-path-slug: apiprivatekeyownershipmsg-post
      parameters:
      - in: body
        name: request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Privatekeyownershipmsg
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