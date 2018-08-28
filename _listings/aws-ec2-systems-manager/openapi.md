swagger: "2.0"
x-collection-name: AWS EC2 Systems Manager
x-complete: 1
info:
  title: AWS EC2 Systems Manager API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=GetInventorySchema:
    get:
      summary: Get Inventory Schema
      description: |-
        Return a list of inventory type names for the account, or return a list of attribute
           names for a specific Inventory item type.
      operationId: getInventorySchema
      x-api-path-slug: actiongetinventoryschema-get
      parameters:
      - in: query
        name: MaxResults
        description: The maximum number of items to return for this call
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      - in: query
        name: TypeName
        description: The type of inventory item to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - Inventory
      - Schema