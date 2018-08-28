---
swagger: "2.0"
x-collection-name: GitLab
x-complete: 0
info:
  title: GitLab Get Projects Owned
  version: 1.0.0
  description: Get an owned projects list for authenticated user
host: localhost:3000
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v3/groups/owned:
    get:
      summary: Get Groups Owned
      description: Get list of owned groups for authenticated user
      operationId: getV3GroupsOwned
      x-api-path-slug: v3groupsowned-get
      parameters:
      - in: query
        name: page
        description: Current page number
      - in: query
        name: per_page
        description: Number of items per page
      - in: query
        name: statistics
        description: Include project statistics
      responses:
        200:
          description: OK
      tags:
      - Groups
      - Owned
  /v3/projects/owned:
    get:
      summary: Get Projects Owned
      description: Get an owned projects list for authenticated user
      operationId: getV3ProjectsOwned
      x-api-path-slug: v3projectsowned-get
      parameters:
      - in: query
        name: archived
        description: Limit by archived status
      - in: query
        name: order_by
        description: Return projects ordered by field
      - in: query
        name: page
        description: Current page number
      - in: query
        name: per_page
        description: Number of items per page
      - in: query
        name: search
        description: Return list of authorized projects matching the search criteria
      - in: query
        name: simple
        description: Return only the ID, URL, name, and path of each project
      - in: query
        name: sort
        description: Return projects sorted in ascending and descending order
      - in: query
        name: statistics
        description: Include project statistics
      - in: query
        name: visibility
        description: Limit by visibility
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Owned
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