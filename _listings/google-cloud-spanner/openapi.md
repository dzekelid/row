---
swagger: "2.0"
x-collection-name: Google Cloud Spanner
x-complete: 1
info:
  title: Cloud Spanner
  description: cloud-spanner-is-a-managed-missioncritical-globally-consistent-and-scalable-relational-database-service-
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
---