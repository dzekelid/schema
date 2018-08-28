swagger: "2.0"
x-collection-name: Factual
x-complete: 1
info:
  title: Factual
  description: access-to-the-places-and-business-data-available-at-factual-
  version: 1.0.0
host: api.v3.factual.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /t/{table_name}/schema:
    get:
      summary: Get Table Name Schema
      description: Get table name schema.
      operationId: getTTableNameSchema
      x-api-path-slug: ttable-nameschema-get
      parameters:
      - in: path
        name: table_name
      responses:
        200:
          description: OK
      tags:
      - Table
      - Name
      - Schema