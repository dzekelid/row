---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph Range Entire Row
  description: 'Range: EntireRow Gets an object that represents the entire row of
    the range.'
  version: 1.0.0
host: graph.microsoft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /workbook/names(&lt;name&gt;)/range/EntireRow:
    post:
      summary: Range Entire Row
      description: 'Range: EntireRow Gets an object that represents the entire row
        of the range.'
      operationId: Range:EntireRow
      x-api-path-slug: workbooknamesltnamegtrangeentirerow-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Entire
      - Row
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/EntireRow:
    post:
      summary: Range Entire Row
      description: 'Range: EntireRow Gets an object that represents the entire row
        of the range.'
      operationId: Range:EntireRow
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtentirerow-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Entire
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