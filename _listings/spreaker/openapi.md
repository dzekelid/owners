swagger: "2.0"
x-collection-name: Spreaker
x-complete: 1
info:
  title: Spreaker API
  version: v1
host: api.spreaker.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /library/{user_id}/effects/owned:
    get:
      summary: Get Owned Media
      description: Get a paginated list of media owned by <user_id> filtered by type:.
      operationId: getLibraryUserEffectsOwned
      x-api-path-slug: libraryuser-ideffectsowned-get
      parameters:
      - in: query
        name: sort_col
        description: The column upon which the results are sorted
      - in: query
        name: sort_dir
        description: The direction of sorting
      - in: path
        name: user_id
        description: The user id
      responses:
        200:
          description: OK
      tags:
      - Podcasts
      - Owned
      - Media
  /library/{user_id}/jingles/owned:
    get:
      summary: Get Owned Media
      description: Get a paginated list of media owned by <user_id> filtered by type:.
      operationId: getLibraryUserJinglesOwned
      x-api-path-slug: libraryuser-idjinglesowned-get
      parameters:
      - in: query
        name: sort_col
        description: The column upon which the results are sorted
      - in: query
        name: sort_dir
        description: The direction of sorting
      - in: path
        name: user_id
        description: The user id
      responses:
        200:
          description: OK
      tags:
      - Podcasts
      - Owned
      - Media
  /library/{user_id}/loops/owned:
    get:
      summary: Get Owned Media
      description: Get a paginated list of media owned by <user_id> filtered by type:.
      operationId: getLibraryUserLoopsOwned
      x-api-path-slug: libraryuser-idloopsowned-get
      parameters:
      - in: query
        name: sort_col
        description: The column upon which the results are sorted
      - in: query
        name: sort_dir
        description: The direction of sorting
      - in: path
        name: user_id
        description: The user id
      responses:
        200:
          description: OK
      tags:
      - Podcasts
      - Owned
      - Media
  /library/{user_id}/songs/owned:
    get:
      summary: Get Owned Media
      description: Get a paginated list of media owned by <user_id> filtered by type:.
      operationId: getLibraryUserSongsOwned
      x-api-path-slug: libraryuser-idsongsowned-get
      parameters:
      - in: query
        name: sort_col
        description: The column upon which the results are sorted
      - in: query
        name: sort_dir
        description: The direction of sorting
      - in: query
        name: user_id
        description: Users id
      responses:
        200:
          description: OK
      tags:
      - Podcasts
      - Owned
      - Media
  /library/{user_id}/soundtracks/owned:
    get:
      summary: Get Owned Media
      description: Get a paginated list of media owned by <user_id> filtered by type:.
      operationId: getLibraryUserSoundtracksOwned
      x-api-path-slug: libraryuser-idsoundtracksowned-get
      parameters:
      - in: query
        name: sort_col
        description: The column upon which the results are sorted
      - in: query
        name: sort_dir
        description: The direction of sorting
      - in: path
        name: user_id
        description: The user id
      responses:
        200:
          description: OK
      tags:
      - Podcasts
      - Owned
      - Media