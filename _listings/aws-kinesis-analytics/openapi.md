swagger: "2.0"
x-collection-name: AWS Kinesis Analytics
x-complete: 1
info:
  title: AWS Kinesis Analytics API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DiscoverInputSchema:
    get:
      summary: Discover Input Schema
      description: Infers a schema by evaluating sample records on the specified streaming
        source (Amazon Kinesis stream or Amazon Kinesis Firehose delivery stream).
      operationId: discoverInputSchema
      x-api-path-slug: actiondiscoverinputschema-get
      parameters:
      - in: query
        name: InputStartingPositionConfiguration
        description: Point at which you want Amazon Kinesis Analytics to start reading
          records from the specified streaming source discovery purposes
        type: string
      - in: query
        name: ResourceARN
        description: Amazon Resource Name (ARN) of the streaming source
        type: string
      - in: query
        name: RoleARN
        description: ARN of the IAM role that Amazon Kinesis Analytics can assume
          to access the stream on your behalf
        type: string
      responses:
        200:
          description: OK
      tags:
      - Schema