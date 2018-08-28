---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph Table Row Collection Item At
  description: 'TableRowCollection: ItemAt Gets a row based on its position in the
    collection.'
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
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/HeaderRowRange:
    post:
      summary: Table Column Header Row Range
      description: 'TableColumn: HeaderRowRange Gets the range object associated with
        the header row of the column.'
      operationId: TableColumn:HeaderRowRange
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegtheaderrowrange-post
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
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/TotalRowRange:
    post:
      summary: Table Column Total Row Range
      description: 'TableColumn: TotalRowRange Gets the range object associated with
        the totals row of the column.'
      operationId: TableColumn:TotalRowRange
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegttotalrowrange-post
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
      - Total
      - Row
      - Range
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/TotalRowRange:
    post:
      summary: Table Column Total Row Range
      description: 'TableColumn: TotalRowRange Gets the range object associated with
        the totals row of the column.'
      operationId: TableColumn:TotalRowRange
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegttotalrowrange-post
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
      - Total
      - Row
      - Range
  /workbook/tables(&lt;id|name&gt;)/rows(&lt;index&gt;)/delete:
    post:
      summary: Table Row Delete
      description: 'TableRow: delete Deletes the row from the table.'
      operationId: TableRow:Delete
      x-api-path-slug: workbooktablesltidnamegtrowsltindexgtdelete-post
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
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/rows(&lt;index&gt;)/delete:
    post:
      summary: Table Row Delete
      description: 'TableRow: delete Deletes the row from the table.'
      operationId: TableRow:Delete
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtrowsltindexgtdelete-post
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
  /workbook/tables(&lt;id|name&gt;)/rows(&lt;index&gt;):
    get:
      summary: Get Table Row
      description: Get TableRow Retrieve the properties and relationships of tablerow
        object.
      operationId: GetTableRow
      x-api-path-slug: workbooktablesltidnamegtrowsltindexgt-get
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
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/rows(&lt;index&gt;):
    get:
      summary: Get Table Row
      description: Get TableRow Retrieve the properties and relationships of tablerow
        object.
      operationId: GetTableRow
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtrowsltindexgt-get
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
  /workbook/tables(&lt;id|name&gt;)/rows(&lt;index&gt;)/Range:
    post:
      summary: Table Row Range
      description: 'TableRow: Range Returns the range object associated with the entire
        row.'
      operationId: TableRow:Range
      x-api-path-slug: workbooktablesltidnamegtrowsltindexgtrange-post
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
      - Range
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/rows(&lt;index&gt;)/Range:
    post:
      summary: Table Row Range
      description: 'TableRow: Range Returns the range object associated with the entire
        row.'
      operationId: TableRow:Range
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtrowsltindexgtrange-post
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
      - Range
  /workbook/tables(&lt;id|name&gt;)/rows/add:
    post:
      summary: Table Row Collection Add
      description: 'TableRowCollection: add Adds a new row to the table.'
      operationId: TableRowCollection:Add
      x-api-path-slug: workbooktablesltidnamegtrowsadd-post
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
      - Collection
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/rows/add:
    post:
      summary: Table Row Collection Add
      description: 'TableRowCollection: add Adds a new row to the table.'
      operationId: TableRowCollection:Add
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtrowsadd-post
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
      - Collection
  /workbook/tables(&lt;id|name&gt;)/rows/ItemAt:
    post:
      summary: Table Row Collection Item At
      description: 'TableRowCollection: ItemAt Gets a row based on its position in
        the collection.'
      operationId: TableRowCollection:ItemAt
      x-api-path-slug: workbooktablesltidnamegtrowsitemat-post
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
      - Collection
      - Item
      - At
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/rows/ItemAt:
    post:
      summary: Table Row Collection Item At
      description: 'TableRowCollection: ItemAt Gets a row based on its position in
        the collection.'
      operationId: TableRowCollection:ItemAt
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtrowsitemat-post
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
      - Collection
      - Item
      - At
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