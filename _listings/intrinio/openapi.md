swagger: "2.0"
x-collection-name: Intrinio
x-complete: 1
info:
  title: Intrinio
  version: 1.0.0
host: api.intrinio.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /owners/insider_transactions:
    get:
      summary: Insider Transactions By Owner
      description: Returns a list of all insider transactions by an owner in as many
        companies as the owner may be considered an insider.  Criteria for being an
        insider include being a director, officer, or 10%+ owner in the company.  Transactions
        are detailed for both non-derivative and derivative transactions by the insider.
      operationId: insider-transactions-by-owner
      x-api-path-slug: ownersinsider-transactions-get
      parameters:
      - in: query
        name: identifier
        description: the Central Index Key issued by the SEC, which is the unique
          identifier all owner filings are issued under:CENTRAL INDEX KEY
        type: string
      - in: query
        name: page_number
        description: an integer greater than or equal to 1 for specifying the page
          number for the return values
        type: string
      - in: query
        name: page_size
        description: an integer greater than 1 for specifying the number of results
          on each page
        type: string
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Owners
      - Insider Transactions
  /owners:
    get:
      summary: Owners
      description: Returns owners list and information for all institutional owners
        of securities covered by Intrinio.  Includes detailed info for a single owner
        and the ability to query by name.
      operationId: owners
      x-api-path-slug: owners-get
      parameters:
      - in: query
        name: identifier
        description: the Central Index Key issued by the SEC, which is the unique
          identifier all owner filings are issued under:CENTRAL INDEX KEY
        type: string
      - in: query
        name: institutional
        description: (true)
        type: string
      - in: query
        name: page_number
        description: an integer greater than or equal to 1 for specifying the page
          number for the return values
        type: string
      - in: query
        name: page_size
        description: an integer greater than 1 for specifying the number of results
          on each page
        type: string
      - in: query
        name: query
        description: a string query search of owner name or cik id with the returned
          results being the relevant owners in compacted list format
        type: string
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Owners