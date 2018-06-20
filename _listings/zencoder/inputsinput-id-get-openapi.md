---
swagger: "2.0"
x-collection-name: Zencoder
x-complete: 0
info:
  title: Zencoder API Get Input Details
  version: v2
  description: Get Input Details
host: app.zencoder.com
basePath: /api/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /account:
    get:
      summary: Get Account Details
      description: Get Account Details
      operationId: getAccount
      x-api-path-slug: account-get
      parameters:
      - in: query
        name: api_key
        description: The API key
      responses:
        200:
          description: OK
      tags:
      - Account
    post:
      summary: Create an Account
      description: Create an Account
      operationId: postAccount
      x-api-path-slug: account-post
      parameters:
      - in: query
        name: email
      - in: query
        name: password
      - in: query
        name: password_confirmation
      - in: query
        name: terms_of_service
      responses:
        200:
          description: OK
      tags:
      - Account
  /account/integration:
    put:
      summary: Integration Mode
      description: Integration Mode
      operationId: putAccountIntegration
      x-api-path-slug: accountintegration-put
      parameters:
      - in: query
        name: api_key
        description: The API key
      responses:
        200:
          description: OK
      tags:
      - Account
      - Integration
  /account/live:
    put:
      summary: Integration Mode - Live
      description: Integration Mode - Live
      operationId: putAccountLive
      x-api-path-slug: accountlive-put
      responses:
        200:
          description: OK
      tags:
      - Account
      - Live
  /inputs/{input_id}:
    get:
      summary: Get Input Details
      description: Get Input Details
      operationId: getInupdatesInupdate
      x-api-path-slug: inputsinput-id-get
      parameters:
      - in: query
        name: api_key
        description: The API key
      - in: query
        name: callback
        description: JSONP Callback
      - in: query
        name: input_id
        description: The input id
      responses:
        200:
          description: OK
      tags:
      - Inputs
      - Input
      - Id
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