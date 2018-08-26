---
swagger: "2.0"
x-collection-name: Xibo
x-complete: 1
info:
  title: Xibo API
  description: xibo-cms-api
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
  /dataset/data/{dataSetId}/{rowId}:
    put:
      summary: Edit Row
      description: Edit a row of Data to a DataSet
      operationId: dataSetDataEdit
      x-api-path-slug: datasetdatadatasetidrowid-put
      parameters:
      - in: formData
        name: dataSetColumnId_ID
        description: Parameter for each dataSetColumnId in the DataSet
      - in: path
        name: dataSetId
        description: The DataSet ID
      - in: path
        name: rowId
        description: The Row ID of the Data to Edit
      responses:
        200:
          description: OK
      tags:
      - Edit
      - Row
    delete:
      summary: Delete Row
      description: Delete a row of Data to a DataSet
      operationId: dataSetDataDelete
      x-api-path-slug: datasetdatadatasetidrowid-delete
      parameters:
      - in: path
        name: dataSetId
        description: The DataSet ID
      - in: path
        name: rowId
        description: The Row ID of the Data to Delete
      responses:
        200:
          description: OK
      tags:
      - Row
---