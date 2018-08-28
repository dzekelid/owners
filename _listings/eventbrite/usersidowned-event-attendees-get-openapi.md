---
swagger: "2.0"
x-collection-name: Eventbrite
x-complete: 0
info:
  title: Eventbrite Get Users Owned Event Attendees
  description: |-
    Returns a paginated response of attendees,
    under the key attendees, of attendees visiting any of the events the user owns
    (events that would be returned from /users/:id/owned_events/)
  version: 1.0.0
host: www.eventbrite.com
basePath: /%7Bdata-type%7D/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/{id}/owned_events/:
    get:
      summary: Get Users Owned Events
      description: |-
        Returns a paginated response of events, under
        the key events, of all events the user owns (i.e. events they are organising)
      operationId: getUsersOwnedEvents
      x-api-path-slug: usersidowned-events-get
      parameters:
      - in: query
        name: order_by
        description: 'How to order the results (Valid choices are: start_asc, start_desc,
          created_asc, created_desc, name_asc, or name_desc)'
        type: query
      - in: query
        name: show_series_parent
        description: 'True: Will show parent of a serie instead of childrenFalse:
          Will show children of a serie (Default value)'
        type: query
      - in: query
        name: status
        description: Filter by events with a specific status set
        type: query
      responses:
        200:
          description: OK
      tags:
      - Users
      - Owned
      - Events
  /users/{id}/owned_event_attendees/:
    get:
      summary: Get Users Owned Event Attendees
      description: |-
        Returns a paginated response of attendees,
        under the key attendees, of attendees visiting any of the events the user owns
        (events that would be returned from /users/:id/owned_events/)
      operationId: getUsersOwnedEventAttendees
      x-api-path-slug: usersidowned-event-attendees-get
      parameters:
      - in: query
        name: changed_since
        description: Only return resource changed on or after the time given
        type: query
      - in: query
        name: status
        description: Limits results to either confirmed attendees or cancelled/refunded/etc
        type: query
      responses:
        200:
          description: OK
      tags:
      - Users
      - Owned
      - Event
      - Attendees
  /users/{id}/owned_event_orders/:
    get:
      summary: Get Users Owned Event Orders
      description: |-
        Returns a paginated response of orders,
        under the key orders, of orders placed against any of the events the user owns
        (events that would be returned from /users/:id/owned_events/)
      operationId: getUsersOwnedEventOrders
      x-api-path-slug: usersidowned-event-orders-get
      parameters:
      - in: query
        name: changed_since
        description: Only return resource changed on or after the time given
        type: query
      - in: query
        name: exclude_emails
        description: Don&#8217;t include orders placed by any of these emails
        type: query
      - in: query
        name: only_emails
        description: Only include orders placed by one of these emails
        type: query
      - in: query
        name: status
        description: 'Filter to active (attending), inactive (not attending), or all
          (both) orders (Valid choices are: active, inactive, or all)'
        type: query
      responses:
        200:
          description: OK
      tags:
      - Users
      - Owned
      - Event
      - Orders
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