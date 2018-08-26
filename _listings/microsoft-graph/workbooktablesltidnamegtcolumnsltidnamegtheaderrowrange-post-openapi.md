---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph Table Column Header Row Range
  description: 'TableColumn: HeaderRowRange Gets the range object associated with
    the header row of the column.'
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
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/EntireRow:
    post:
      summary: Range Entire Row
      description: 'Range: EntireRow Gets an object that represents the entire row
        of the range.'
      operationId: Range:EntireRow
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeentirerow-post
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
  /workbook/names(&lt;name&gt;)/range/Row:
    post:
      summary: Range Row
      description: 'Range: Row Gets a row contained in the range.'
      operationId: Range:Row
      x-api-path-slug: workbooknamesltnamegtrangerow-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Row
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/Row:
    post:
      summary: Range Row
      description: 'Range: Row Gets a row contained in the range.'
      operationId: Range:Row
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtrow-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Row
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/Row:
    post:
      summary: Range Row
      description: 'Range: Row Gets a row contained in the range.'
      operationId: Range:Row
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangerow-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Row
  /workbook/tables(&lt;id|name&gt;)/HeaderRowRange:
    post:
      summary: Table Header Row Range
      description: 'Table: HeaderRowRange Gets the range object associated with header
        row of the table.'
      operationId: Table:HeaderRowRange
      x-api-path-slug: workbooktablesltidnamegtheaderrowrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Header
      - Row
      - Range
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/HeaderRowRange:
    post:
      summary: Table Header Row Range
      description: 'Table: HeaderRowRange Gets the range object associated with header
        row of the table.'
      operationId: Table:HeaderRowRange
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtheaderrowrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Header
      - Row
      - Range
  /workbook/tables(&lt;id|name&gt;)/rows:
    post:
      summary: Create Table Row
      description: Create TableRow Use this API to create a new TableRow.
      operationId: CreateTableRow
      x-api-path-slug: workbooktablesltidnamegtrows-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Row
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/rows:
    post:
      summary: Create Table Row
      description: Create TableRow Use this API to create a new TableRow.
      operationId: CreateTableRow
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtrows-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Row
  /workbook/tables(&lt;id|name&gt;)/TotalRowRange:
    post:
      summary: Table Total Row Range
      description: 'Table: TotalRowRange Gets the range object associated with totals
        row of the table.'
      operationId: Table:TotalRowRange
      x-api-path-slug: workbooktablesltidnamegttotalrowrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Total
      - Row
      - Range
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/TotalRowRange:
    post:
      summary: Table Total Row Range
      description: 'Table: TotalRowRange Gets the range object associated with totals
        row of the table.'
      operationId: Table:TotalRowRange
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegttotalrowrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Total
      - Row
      - Range
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/HeaderRowRange:
    post:
      summary: Table Column Header Row Range
      description: 'TableColumn: HeaderRowRange Gets the range object associated with
        the header row of the column.'
      operationId: TableColumn:HeaderRowRange
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtheaderrowrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
      - Header
      - Row
      - Range
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