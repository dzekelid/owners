swagger: "2.0"
x-collection-name: Bitly
x-complete: 1
info:
  title: Bitly User Metrics API
  description: the-bitly-user-metrics-api
  termsOfService: http://dev.bitly.com/best_practices.html
  version: v3
host: api-ssl.bitly.com
basePath: /v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v3/user/popular_owned_by_clicks:
    get:
      summary: User Popular Owned By Clicks
      description: Returns the top links to your tracking domain (or domains) created
        by you or your subaccounts ordered by clicks.
      operationId: userPopularOwnedByClicks
      x-api-path-slug: v3userpopular-owned-by-clicks-get
      parameters:
      - in: query
        name: domain
        description: a tracking domain as returned from /v3/user/tracking_domain_list
          (may be specified multiple times)
      - in: query
        name: limit
        description: "1"
      - in: query
        name: subaccount
        description: restrict to links created by this subaccount (may be specified
          multiple times)
      - in: query
        name: timezone
        description: an integer hour offset from UTC (-14
      - in: query
        name: unit
        description: hour | day | week | month default:day
      - in: query
        name: units
        description: an integer representing the time units to query data for
      - in: query
        name: unit_reference_ts
        description: an epoch timestamp, indicating the most recent time for which
          to pull metrics
      responses:
        200:
          description: OK
      tags:
      - User
      - Popular
      - Owned
      - Clicks
  /v3/user/popular_owned_by_shortens:
    get:
      summary: User Popular Owned by Shortens
      description: Returns the top links to your tracking domain (or domains) created
        by you or your subaccounts ordered by number of shortens.
      operationId: userPopularOwnedByShortens
      x-api-path-slug: v3userpopular-owned-by-shortens-get
      parameters:
      - in: query
        name: domain
        description: a tracking domain as returned from /v3/user/tracking_domain_list
          (may be specified multiple times)
      - in: query
        name: limit
        description: "1"
      - in: query
        name: subaccount
        description: restrict to links created by this subaccount (may be specified
          multiple times)
      - in: query
        name: timezone
        description: an integer hour offset from UTC (-14
      - in: query
        name: unit
        description: hour | day | week | month default:day
      - in: query
        name: units
        description: an integer representing the time units to query data for
      - in: query
        name: unit_reference_ts
        description: an epoch timestamp, indicating the most recent time for which
          to pull metrics
      responses:
        200:
          description: OK
      tags:
      - User
      - Popular
      - Owned
      - By
      - Shortens