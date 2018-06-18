---
swagger: "2.0"
x-collection-name: 7digital
x-complete: 0
info:
  title: 7digital Purchasing API basket
  description: Basket.
  version: "1.2"
host: api.7digital.com
basePath: 1.2/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  basket:
    '<h4 ':
      summary: basket
      description: Basket.
      operationId: basket
      x-api-path-slug: basket-h4
      parameters:
      - ~
      - in: query
        name: amountDue
      - in: query
        name: artistName
      - in: query
        name: basket id
      - in: query
        name: basketId
        description: nttttttttThe unique identifier of the basket as acquired by basket/create
          methodnttttttt
      - in: query
        name: basketItem id
      - in: query
        name: basketItems
      - in: query
        name: country
        description: The code of the country the end user resides in
      - in: query
        name: discount
      - in: query
        name: itemCount
      - in: query
        name: itemName
      - in: query
        name: package
      - in: query
        name: price
      - in: query
        name: releaseId
      - in: query
        name: trackId
      - in: query
        name: type
      responses:
        200:
          description: OK
      tags:
      - Basket
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