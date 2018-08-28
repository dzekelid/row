---
swagger: "2.0"
x-collection-name: Google Cloud Spanner
x-complete: 0
info:
  title: Google Cloud Spanner API Read Rows
  description: |-
    Reads rows from the database using key lookups and scans, as a
    simple key/value style alternative to
    ExecuteSql.  This method cannot be used to
    return a result set larger than 10 MiB; if the read matches more
    data than that, the read fails with a `FAILED_PRECONDITION`
    error.

    Reads inside read-write transactions might return `ABORTED`. If
    this occurs, the application should restart the transaction from
    the beginning. See Transaction for more details.

    Larger result sets can be yielded in streaming fashion by calling
    StreamingRead instead.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: spanner.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/{session}:read:
    post:
      summary: Read Rows
      description: |-
        Reads rows from the database using key lookups and scans, as a
        simple key/value style alternative to
        ExecuteSql.  This method cannot be used to
        return a result set larger than 10 MiB; if the read matches more
        data than that, the read fails with a `FAILED_PRECONDITION`
        error.

        Reads inside read-write transactions might return `ABORTED`. If
        this occurs, the application should restart the transaction from
        the beginning. See Transaction for more details.

        Larger result sets can be yielded in streaming fashion by calling
        StreamingRead instead.
      operationId: spanner.projects.instances.databases.sessions.read
      x-api-path-slug: v1sessionread-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: session
        description: Required
      responses:
        200:
          description: OK
      tags:
      - Row
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