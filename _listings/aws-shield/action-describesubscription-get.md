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
  /?Action=DescribeSubscription:
    get:
      summary: ' Describe Subscription '
      description: Provides details about the AWS Shield Advanced subscription for
        an account
      operationId: describeSubscription
      parameters:
      - in: query
        name: Subscription
        description: The AWS Shield Advanced subscription details for an account
        type: string
      responses:
        200:
          description: OK
      tags:
      - subscriptions
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