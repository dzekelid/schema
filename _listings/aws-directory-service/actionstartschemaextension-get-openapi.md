---
swagger: "2.0"
x-collection-name: AWS Directory Service
x-complete: 0
info:
  title: AWS Directory Service API Start Schema Extension
  version: 1.0.0
  description: Applies a schema extension to a Microsoft AD directory.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CancelSchemaExtension:
    get:
      summary: Cancel Schema Extension
      description: Cancels an in-progress schema extension to a Microsoft AD directory.
      operationId: cancelSchemaExtension
      x-api-path-slug: actioncancelschemaextension-get
      parameters:
      - in: query
        name: DirectoryId
        description: The identifier of the directory whose schema extension will be
          canceled
        type: string
      - in: query
        name: SchemaExtensionId
        description: The identifier of the schema extension that will be canceled
        type: string
      responses:
        200:
          description: OK
      tags:
      - Schemas
  /?Action=ListSchemaExtensions:
    get:
      summary: List Schema Extensions
      description: Lists all schema extensions applied to a Microsoft AD Directory.
      operationId: listSchemaExtensions
      x-api-path-slug: actionlistschemaextensions-get
      parameters:
      - in: query
        name: DirectoryId
        description: The identifier of the directory from which to retrieve the schema
          extension information
        type: string
      - in: query
        name: Limit
        description: The maximum number of items to return
        type: string
      - in: query
        name: NextToken
        description: The ListSchemaExtensions
        type: string
      responses:
        200:
          description: OK
      tags:
      - Schema Extension
  /?Action=StartSchemaExtension:
    get:
      summary: Start Schema Extension
      description: Applies a schema extension to a Microsoft AD directory.
      operationId: startSchemaExtension
      x-api-path-slug: actionstartschemaextension-get
      parameters:
      - in: query
        name: CreateSnapshotBeforeSchemaExtension
        description: If true, creates a snapshot of the directory before applying
          the schema extension
        type: string
      - in: query
        name: Description
        description: A description of the schema extension
        type: string
      - in: query
        name: DirectoryId
        description: The identifier of the directory for which the schema extension
          will be applied to
        type: string
      - in: query
        name: LdifContent
        description: The LDIF file represented as a string
        type: string
      responses:
        200:
          description: OK
      tags:
      - Schema Extension
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