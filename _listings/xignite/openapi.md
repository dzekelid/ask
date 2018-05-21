---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 1
info:
  title: Xignite Currencies
  description: provide-realtime-currency-foreign-exchange-information-and-calculations
  version: 1.0.0
host: www.xignite.com/xCurrencies.json
basePath: /XigniteCurrencies
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /GetHistoricalCrossRateTablesBidAsk:
    post:
      summary: Get Historical Cross Rate Tables Bid Ask
      description: Returns historical currency cross-rate tables for a range of dates.
      operationId: postGethistoricalcrossratetablesbask
      x-api-path-slug: gethistoricalcrossratetablesbidask-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Historical
      - Cross
      - Rate
      - Tables
      - Bid
      - Ask
  /GetHistoricalCrossRateTableBidAsk:
    post:
      summary: Get Historical Cross Rate Table Bid Ask
      description: Returns a historical currency cross-rate table.
      operationId: postGethistoricalcrossratetablebask
      x-api-path-slug: gethistoricalcrossratetablebidask-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Historical
      - Cross
      - Rate
      - Table
      - Bid
      - Ask
  /GetRealTimeCrossRateTableWithBidAsk:
    post:
      summary: Get Real Time Cross Rate Table With Bid Ask
      description: Returns a real-time currency cross-rate table.
      operationId: postGetrealtimecrossratetablewithbask
      x-api-path-slug: getrealtimecrossratetablewithbidask-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Real
      - Time
      - Cross
      - Rate
      - Table
      - With
      - Bid
      - Ask
  /GetHistoricalCrossRateBidAsk:
    post:
      summary: Get Historical Cross Rate Bid Ask
      description: Returns a cross-rate with bid/ask as of a historical date.
      operationId: postGethistoricalcrossratebask
      x-api-path-slug: gethistoricalcrossratebidask-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Historical
      - Cross
      - Rate
      - Bid
      - Ask
  /GetHistoricalCrossRatesBidAsk:
    post:
      summary: Get Historical Cross Rates Bid Ask
      description: Returns multiple cross-rates with bid/ask as of a historical date.
      operationId: postGethistoricalcrossratesbask
      x-api-path-slug: gethistoricalcrossratesbidask-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Historical
      - Cross
      - Rates
      - Bid
      - Ask
  /GetHistoricalCrossRatesBidAskRange:
    post:
      summary: Get Historical Cross Rates Bid Ask Range
      description: This operation returns a range of cross-rates for a currency pair.
      operationId: postGethistoricalcrossratesbaskrange
      x-api-path-slug: gethistoricalcrossratesbidaskrange-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Historical
      - Cross
      - Rates
      - Bid
      - Ask
      - Range
  /GetHistoricalCrossRatesBidAskAsOf:
    post:
      summary: Get Historical Cross Rates Bid Ask As Of
      description: This operation returns a range of cross-rates for a currency pair.
      operationId: postGethistoricalcrossratesbaskasof
      x-api-path-slug: gethistoricalcrossratesbidaskasof-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Historical
      - Cross
      - Rates
      - Bid
      - Ask
      - As
      - Of
  /GetOfficialCrossRateBidAsk:
    post:
      summary: Get Official Cross Rate Bid Ask
      description: Returns an official cross-rate as of a historical date.
      operationId: postGetofficialcrossratebask
      x-api-path-slug: getofficialcrossratebidask-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Official
      - Cross
      - Rate
      - Bid
      - Ask
  /GetOfficialCrossRatesBidAsk:
    post:
      summary: Get Official Cross Rates Bid Ask
      description: Returns an official cross-rate as of a historical date.
      operationId: postGetofficialcrossratesbask
      x-api-path-slug: getofficialcrossratesbidask-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Official
      - Cross
      - Rates
      - Bid
      - Ask
---