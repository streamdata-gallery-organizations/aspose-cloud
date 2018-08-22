---
swagger: "2.0"
x-collection-name: Aspose.Cloud
x-complete: 0
info:
  title: Aspose.Cloud https://api.aspose.cloud/oauth2/token
  description: Get Access/Refresh Token
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