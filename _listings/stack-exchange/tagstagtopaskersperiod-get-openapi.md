---
swagger: "2.0"
x-collection-name: Stack Exchange
x-complete: 0
info:
  title: Stack Exchange Get Tags Top Askers
  description: "Returns the top 30 askers active in a single tag, of either all-time
    or the last 30 days.\n \nThis is a view onto the data presented on the tag info
    page on the sites.\n \nThis method returns a list of tag score objects."
  version: "2.0"
host: api.stackexchange.com
basePath: /2.2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /tags/{tag}/top-askers/{period}:
    get:
      summary: Get Tags Top Askers
      description: "Returns the top 30 askers active in a single tag, of either all-time
        or the last 30 days.\n \nThis is a view onto the data presented on the tag
        info page on the sites.\n \nThis method returns a list of tag score objects."
      operationId: returns-the-top-30-askers-active-in-a-single-tag-of-either-alltime-or-the-last-30-days-this-is-a-vie
      x-api-path-slug: tagstagtopaskersperiod-get
      parameters:
      - in: query
        name: callback
        description: All API responses are JSON, we do support JSONP with the callback
          query parameter
      - in: query
        name: filter
        description: '#DiscussionThe Stack Exchange API allows applications to exclude
          almost every field returned'
      - in: query
        name: page
      - in: query
        name: pagesize
      - in: path
        name: period
      - in: query
        name: site
        description: Each of these methods operates on a single site at a time, identified
          by the site parameter
      - in: path
        name: tag
      responses:
        200:
          description: OK
      tags:
      - Tags
      - Top Askers
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