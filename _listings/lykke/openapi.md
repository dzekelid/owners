---
swagger: "2.0"
x-collection-name: Lykke
x-complete: 1
info:
  title: Wallet_Api
  version: 1.0.0
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
---