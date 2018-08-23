---
swagger: "2.0"
x-collection-name: Aspose.Cloud
x-complete: 0
info:
  title: Aspose.Cloud Gettings Cells Data based on Named Range
  description: Gettings Cells Data based on Named Range
  version: "1.0"
host: api.aspose.cloud
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /oauth2/token:
    post:
      summary: https://api.aspose.cloud/oauth2/token
      description: Get Access/Refresh Token
      operationId: Oauth2TokenPost
      x-api-path-slug: oauth2token-post
      parameters:
      - in: header
        name: Accept
      - in: formData
        name: client_id
      - in: formData
        name: client_secret
      - in: header
        name: Content-Type
      - in: formData
        name: grant_type
      responses:
        200:
          description: OK
      tags:
      - Tokens
  /v1.1/cells/MyExcel.xlsx/worksheets/Sheet1/ranges/value:
    get:
      summary: Gettings Cells Data based on Named Range
      description: Gettings Cells Data based on Named Range
      operationId: V11CellsMyExcelXlsxWorksheetsSheet1RangesValueGet
      x-api-path-slug: v1-1cellsmyexcel-xlsxworksheetssheet1rangesvalue-get
      parameters:
      - in: header
        name: Accept
      - in: query
        name: columnCount
      - in: header
        name: Content-Type
      - in: query
        name: firstColumn
      - in: query
        name: firstRow
      - in: query
        name: rowCount
      responses:
        200:
          description: OK
      tags:
      - Spreadsheets
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