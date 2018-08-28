---
swagger: "2.0"
x-collection-name: PayRun
x-complete: 0
info:
  title: Pay Run.IO Get the HmrcSettings schema
  description: Returns the HmrcSettings schema object
  version: 17.18.6.206
host: api.test.payrun.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Schemas/AbsencePayInstruction.xsd:
    get:
      summary: Get the AbsencePayInstruction schema
      description: Returns the AbsencePayInstruction schema object
      operationId: GetAbsencePayInstructionSchema
      x-api-path-slug: schemasabsencepayinstruction-xsd-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - AbsencePayInstruction
      - Schema
  /Schemas/AbsenceYtdPayInstruction.xsd:
    get:
      summary: Get the AbsenceYtdPayInstruction schema
      description: Returns the AbsenceYtdPayInstruction schema object
      operationId: GetAbsenceYtdPayInstructionSchema
      x-api-path-slug: schemasabsenceytdpayinstruction-xsd-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - AbsenceYtdPayInstruction
      - Schema
  /Schemas/Address.xsd:
    get:
      summary: Get the Address schema
      description: Returns the Address schema object
      operationId: GetAddressSchema
      x-api-path-slug: schemasaddress-xsd-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Ress
      - Schema
  /Schemas/ArrayOfEmployee.xsd:
    get:
      summary: Get the ArrayOfEmployee schema
      description: Returns the ArrayOfEmployee schema object
      operationId: GetArrayOfEmployeeSchema
      x-api-path-slug: schemasarrayofemployee-xsd-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - ArrayOfEmployee
      - Schema
  /Schemas/BankAccount.xsd:
    get:
      summary: Get the BankAccount schema
      description: Returns the BankAccount schema object
      operationId: GetBankAccountSchema
      x-api-path-slug: schemasbankaccount-xsd-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - BankAccount
      - Schema
  /Schemas/BenefitPayInstruction.xsd:
    get:
      summary: Get the BenefitPayInstruction schema
      description: Returns the BenefitPayInstruction schema object
      operationId: GetBenefitPayInstructionSchema
      x-api-path-slug: schemasbenefitpayinstruction-xsd-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - BenefitPayInstruction
      - Schema
  /Schemas/BenefitYtdPayInstruction.xsd:
    get:
      summary: Get the BenefitYtdPayInstruction schema
      description: Returns the BenefitYtdPayInstruction schema object
      operationId: GetBenefitYtdPayInstructionSchema
      x-api-path-slug: schemasbenefitytdpayinstruction-xsd-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - BenefitYtdPayInstruction
      - Schema
  /Schemas/Common.xsd:
    get:
      summary: Get the Common schema
      description: Returns the Common schema object
      operationId: GetCommonSchema
      x-api-path-slug: schemascommon-xsd-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Common
      - Schema
  /Schemas/Employee.xsd:
    get:
      summary: Get the Employee schema
      description: Returns the Employee schema object
      operationId: GetEmployeeSchema
      x-api-path-slug: schemasemployee-xsd-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Employee
      - Schema
  /Schemas/EmployeePartner.xsd:
    get:
      summary: Get the EmployeePartner schema
      description: Returns the EmployeePartner schema object
      operationId: GetEmployeePartnerSchema
      x-api-path-slug: schemasemployeepartner-xsd-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - EmployeePartner
      - Schema
  /Schemas/Employer.xsd:
    get:
      summary: Get the Employer schema
      description: Returns the Employer schema object
      operationId: GetEmployerSchema
      x-api-path-slug: schemasemployer-xsd-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Employer
      - Schema
  /Schemas/HmrcSettings.xsd:
    get:
      summary: Get the HmrcSettings schema
      description: Returns the HmrcSettings schema object
      operationId: GetHmrcSettingsSchema
      x-api-path-slug: schemashmrcsettings-xsd-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - HmrcSettings
      - Schema
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