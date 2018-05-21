---
swagger: "2.0"
x-collection-name: Data.Gov
x-complete: 1
info:
  title: Data.gov API
  description: the-datagov-catalog-is-powered-by-ckan-a-powerful-open-source-data-platform-that-includes-a-robust-api-please-be-aware-that-datagov-and-the-datagov-ckan-api-only-contain-metadata-about-datasets-this-metadata-includes-urls-and-descriptions-of-datasets-but-it-does-not-include-the-actual-data-within-each-dataset
  version: "3"
host: catalog.data.gov
basePath: /api/3/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /workers/tasks/{id}:
    get:
      summary: Get Workers Tasks
      description: Get a tasks status given its ID
      operationId: getWorkersTasks
      x-api-path-slug: workerstasksid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Workers
      - Tasks
---