---
swagger: "2.0"
x-collection-name: Xibo
x-complete: 0
info:
  title: Xibo API Add Row
  description: Add a row of Data to a DataSet
  termsOfService: http://xibo.org.uk/legal
  version: 1.0.0
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /dataset/data/{dataSetId}:
    post:
      summary: Add Row
      description: Add a row of Data to a DataSet
      operationId: dataSetDataAdd
      x-api-path-slug: datasetdatadatasetid-post
      parameters:
      - in: formData
        name: dataSetColumnId_ID
        description: Parameter for each dataSetColumnId in the DataSet
      - in: path
        name: dataSetId
        description: The DataSet ID
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