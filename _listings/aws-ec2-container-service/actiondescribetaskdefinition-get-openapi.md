---
swagger: "2.0"
x-collection-name: AWS EC2 Container Service
x-complete: 0
info:
  title: Amazon EC2 Container Service API Describe Task Definition
  version: 1.0.0
  description: Describes a task definition.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DeregisterTaskDefinition:
    get:
      summary: Deregister Task Definition
      description: Deregisters the specified task definition by family and revision.
      operationId: deregisterTaskDefinition
      x-api-path-slug: actionderegistertaskdefinition-get
      parameters:
      - in: query
        name: taskDefinition
        description: The family and revision (family:revision) or            full
          Amazon Resource Name (ARN) of the task definition to deregister
        type: string
      responses:
        200:
          description: OK
      tags:
      - Task Definitions
  /?Action=DescribeTaskDefinition:
    get:
      summary: Describe Task Definition
      description: Describes a task definition.
      operationId: describeTaskDefinition
      x-api-path-slug: actiondescribetaskdefinition-get
      parameters:
      - in: query
        name: taskDefinition
        description: The family for the latest ACTIVE revision,                family
          and revision (family:revision) for a            specific revision in the
          family, or full Amazon Resource Name (ARN) of the task definition to            describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Task Definitions
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