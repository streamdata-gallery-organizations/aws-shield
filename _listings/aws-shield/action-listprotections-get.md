---
swagger: "2.0"
info:
  title: AWS Shield API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=ListProtections&k=1:
    get:
      summary: ' List Protections '
      description: Lists all protections
      operationId: listProtections
      parameters:
      - in: query
        name: MaxResults
        description: The maximum number of Protection objects to be returned
        type: string
      - in: query
        name: NextToken
        description: The ListProtectionsRequest
        type: string
      responses:
        200:
          description: OK
      tags:
      - protection
definitions: []
x-collection-name: AWS Shield
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