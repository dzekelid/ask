---
name: Google Fusion Tables
x-slug: google-fusion-tables
description: Fusion Tables is an experimental data visualization web application to
  gather, visualize, and share data tables.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
x-kinRank: "9"
x-alexaRank: ""
tags: Ask
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/ask/master/_listings/google-fusion-tables/apis.md
specificationVersion: "0.14"
apis:
- name: Google Fusion Tables API Get Tasks
  x-api-slug: google-fusion-tables-api
  description: Retrieves a list of tasks.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2//tables/{tableId}/tasks
  tags: Task
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/ask/master/_listings/google-fusion-tables/tablestableidtasks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/ask/master/_listings/google-fusion-tables/tablestableidtasks-get-openapi.md
- name: Google Fusion Tables API Delete Task
  x-api-slug: google-fusion-tables-api
  description: Deletes a specific task by its ID, unless that task has already started
    running.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2//tables/{tableId}/tasks/{taskId}
  tags: Task
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/ask/master/_listings/google-fusion-tables/tablestableidtaskstaskid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/ask/master/_listings/google-fusion-tables/tablestableidtaskstaskid-delete-openapi.md
- name: Google Fusion Tables API Get Task
  x-api-slug: google-fusion-tables-api
  description: Retrieves a specific task by its ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2//tables/{tableId}/tasks/{taskId}
  tags: Task
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/ask/master/_listings/google-fusion-tables/tablestableidtaskstaskid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/ask/master/_listings/google-fusion-tables/tablestableidtaskstaskid-get-openapi.md
- name: Google Fusion Tables API
  x-api-slug: google-fusion-tables-api
  description: Fusion Tables is an experimental data visualization web application
    to gather, visualize, and share data tables.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2
  tags: Ask
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/ask/master/_listings/google-fusion-tables/openapi.md
x-common:
- type: x-documentation
  url: https://developers.google.com/fusiontables/docs/v2/reference/
- type: x-forums
  url: https://groups.google.com/forum/#!forum/fusion-tables-api-announce
- type: x-website
  url: https://developers.google.com/fusiontables/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---