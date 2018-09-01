---
swagger: "2.0"
x-collection-name: Zencoder
x-complete: 0
info:
  title: Zencoder API Get Job Details
  version: v2
  description: Get Job Details
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
  /inputs/{input_id}/progress:
    get:
      summary: Input Progress
      description: 'The return will contain one or more of the following keys: state,
        current_event, current_event_progress and progress.'
      operationId: getInupdatesInupdateProgress
      x-api-path-slug: inputsinput-idprogress-get
      responses:
        200:
          description: OK
      tags:
      - Inputs
      - Input
      - Id
      - Progress
  /jobs:
    get:
      summary: List Jobs
      description: A list of jobs can be obtained by sending an HTTP GET request.
      operationId: getJobs
      x-api-path-slug: jobs-get
      parameters:
      - in: query
        name: api_key
        description: The API Key
      responses:
        200:
          description: OK
      tags:
      - Jobs
    post:
      summary: Create a Job
      description: Encoding jobs are created by sending an HTTP POST request.
      operationId: postJobs
      x-api-path-slug: jobs-post
      parameters:
      - in: query
        name: api_key
        description: The API key
      - in: query
        name: Encoding Settings
        description: '(see: https://app'
      - in: query
        name: input
        description: A valid URL to a media file (HTTP/HTTPS, FTP/FTPS, SFTP, GCS,
          CF or S3), with or without authentication
      responses:
        200:
          description: OK
      tags:
      - Jobs
  /jobs/{job_id}:
    get:
      summary: Get Job Details
      description: Get Job Details
      operationId: getJobsJob
      x-api-path-slug: jobsjob-id-get
      parameters:
      - in: query
        name: api_key
        description: The API Key
      - in: query
        name: Get Job Details
        description: The Job id
      responses:
        200:
          description: OK
      tags:
      - Jobs
      - Job
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