---
swagger: "2.0"
x-collection-name: SAP
x-complete: 0
info:
  title: SAP Manufacturing Network Customer APIs Retrieves your own organization
  description: Retrieves the information of the login user's own organization.
  version: 1.0.0
host: hostname
basePath: /dim/api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /organizations/self:
    get:
      summary: Retrieves your own organization
      description: Retrieves the information of the login user's own organization.
      operationId: retrieves-the-information-of-the-login-users-own-organization
      x-api-path-slug: organizationsself-get
      responses:
        200:
          description: Successful response
      tags:
      - Retrieves
      - Your
      - Own
      - Organization
  /users/self:
    get:
      summary: Retrieves your own user info
      description: Retrieves the information of the current login user.
      operationId: retrieves-the-information-of-the-current-login-user
      x-api-path-slug: usersself-get
      responses:
        200:
          description: Successful response
      tags:
      - Retrieves
      - Your
      - Own
      - User
      - Info
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