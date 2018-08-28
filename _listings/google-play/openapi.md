swagger: "2.0"
x-collection-name: Google Play
x-complete: 1
info:
  title: Google Play
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /enterprises/{enterpriseId}/products/{productId}/appRestrictionsSchema:
    get:
      summary: Get Restriction Schema
      description: Retrieves the schema that defines the configurable properties for
        this product. All products have a schema, but this schema may be empty if
        no managed configurations have been defined. This schema can be used to populate
        a UI that allows an admin to configure the product. To apply a managed configuration
        based on the schema obtained using this API, see Managed Configurations through
        Play.
      operationId: androidenterprise.products.getAppRestrictionsSchema
      x-api-path-slug: enterprisesenterpriseidproductsproductidapprestrictionsschema-get
      parameters:
      - in: path
        name: enterpriseId
        description: The ID of the enterprise
      - in: query
        name: language
        description: The BCP47 tag for the users preferred language (e
      - in: path
        name: productId
        description: The ID of the product
      responses:
        200:
          description: OK
      tags:
      - Schema