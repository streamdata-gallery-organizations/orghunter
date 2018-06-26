---
swagger: "2.0"
x-collection-name: OrgHunter
x-complete: 0
info:
  title: Org Hunter Get categories!
  description: This operation provides a list of categories.
  version: 1.0.0
host: data.orghunter.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/categories:
    post:
      summary: Get categories!
      description: This operation provides a list of categories.
      operationId: postV1Categories
      x-api-path-slug: v1categories-post
      responses:
        200:
          description: OK
      tags:
      - Charity
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