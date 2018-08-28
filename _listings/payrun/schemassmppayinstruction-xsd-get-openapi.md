---
swagger: "2.0"
x-collection-name: PayRun
x-complete: 0
info:
  title: Pay Run.IO Get the SmpPayInstruction schema
  description: Returns the SmpPayInstruction schema object
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
  /Schemas/Link.xsd:
    get:
      summary: Get the Link schema
      description: Returns the Link schema object
      operationId: GetLinkSchema
      x-api-path-slug: schemaslink-xsd-get
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
      - Link
      - Schema
  /Schemas/NiAdjustmentPayInstruction.xsd:
    get:
      summary: Get the NiAdjustmentPayInstruction schema
      description: Returns the NiAdjustmentPayInstruction schema object
      operationId: GetNiAdjustmentPayInstructionSchema
      x-api-path-slug: schemasniadjustmentpayinstruction-xsd-get
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
      - NiAdjustmentPayInstruction
      - Schema
  /Schemas/NiPayInstruction.xsd:
    get:
      summary: Get the NiPayInstruction schema
      description: Returns the NiPayInstruction schema object
      operationId: GetNiPayInstructionSchema
      x-api-path-slug: schemasnipayinstruction-xsd-get
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
      - NiPayInstruction
      - Schema
  /Schemas/NiYtdPayInstruction.xsd:
    get:
      summary: Get the NiYtdPayInstruction schema
      description: Returns the NiYtdPayInstruction schema object
      operationId: GetNiYtdPayInstructionSchema
      x-api-path-slug: schemasniytdpayinstruction-xsd-get
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
      - NiYtdPayInstruction
      - Schema
  /Schemas/P45PayInstruction.xsd:
    get:
      summary: Get the P45PayInstruction schema
      description: Returns the P45PayInstruction schema object
      operationId: GetP45PayInstructionSchema
      x-api-path-slug: schemasp45payinstruction-xsd-get
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
      - P45PayInstruction
      - Schema
  /Schemas/PayInstruction.xsd:
    get:
      summary: Get the PayInstruction schema
      description: Returns the PayInstruction schema object
      operationId: GetPayInstructionSchema
      x-api-path-slug: schemaspayinstruction-xsd-get
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
      - PayInstruction
      - Schema
  /Schemas/PayRunJobInstruction.xsd:
    get:
      summary: Get the PayRunJobInstruction schema
      description: Returns the PayRunJobInstruction schema object
      operationId: GetPayRunJobInstructionSchema
      x-api-path-slug: schemaspayrunjobinstruction-xsd-get
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
      - PayRunJobInstruction
      - Schema
  /Schemas/PaySchedule.xsd:
    get:
      summary: Get the PaySchedule schema
      description: Returns the PaySchedule schema object
      operationId: GetPayScheduleSchema
      x-api-path-slug: schemaspayschedule-xsd-get
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
      - PaySchedule
      - Schema
  /Schemas/PensionPayInstruction.xsd:
    get:
      summary: Get the PensionPayInstruction schema
      description: Returns the PensionPayInstruction schema object
      operationId: GetPensionPayInstructionSchema
      x-api-path-slug: schemaspensionpayinstruction-xsd-get
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
      - PensionPayInstruction
      - Schema
  /Schemas/PensionYtdPayInstruction.xsd:
    get:
      summary: Get the PensionYtdPayInstruction schema
      description: Returns the PensionYtdPayInstruction schema object
      operationId: GetPensionYtdPayInstructionSchema
      x-api-path-slug: schemaspensionytdpayinstruction-xsd-get
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
      - PensionYtdPayInstruction
      - Schema
  /Schemas/PrimitivePayInstruction.xsd:
    get:
      summary: Get the PrimitivePayInstruction schema
      description: Returns the PrimitivePayInstruction schema object
      operationId: GetPrimitivePayInstructionSchema
      x-api-path-slug: schemasprimitivepayinstruction-xsd-get
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
      - PrimitivePayInstruction
      - Schema
  /Schemas/RtiJobInstruction.xsd:
    get:
      summary: Get the RtiJobInstruction schema
      description: Returns the RtiJobInstruction schema object
      operationId: GetRtiJobInstructionSchema
      x-api-path-slug: schemasrtijobinstruction-xsd-get
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
      - RtiJobInstruction
      - Schema
  /Schemas/SalaryPayInstruction.xsd:
    get:
      summary: Get the SalaryPayInstruction schema
      description: Returns the SalaryPayInstruction schema object
      operationId: GetSalaryPayInstructionSchema
      x-api-path-slug: schemassalarypayinstruction-xsd-get
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
      - SalaryPayInstruction
      - Schema
  /Schemas/SapPayInstruction.xsd:
    get:
      summary: Get the SapPayInstruction schema
      description: Returns the SapPayInstruction schema object
      operationId: GetSapPayInstructionSchema
      x-api-path-slug: schemassappayinstruction-xsd-get
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
      - SapPayInstruction
      - Schema
  /Schemas/SapYtdPayInstruction.xsd:
    get:
      summary: Get the SapYtdPayInstruction schema
      description: Returns the SapYtdPayInstruction schema object
      operationId: GetSapYtdPayInstructionSchema
      x-api-path-slug: schemassapytdpayinstruction-xsd-get
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
      - SapYtdPayInstruction
      - Schema
  /Schemas/ShppPayInstruction.xsd:
    get:
      summary: Get the ShppPayInstruction schema
      description: Returns the ShppPayInstruction schema object
      operationId: GetShppPayInstructionSchema
      x-api-path-slug: schemasshpppayinstruction-xsd-get
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
      - ShppPayInstruction
      - Schema
  /Schemas/ShppYtdPayInstruction.xsd:
    get:
      summary: Get the ShppYtdPayInstruction schema
      description: Returns the ShppYtdPayInstruction schema object
      operationId: GetShppYtdPayInstructionSchema
      x-api-path-slug: schemasshppytdpayinstruction-xsd-get
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
      - ShppYtdPayInstruction
      - Schema
  /Schemas/SmpPayInstruction.xsd:
    get:
      summary: Get the SmpPayInstruction schema
      description: Returns the SmpPayInstruction schema object
      operationId: GetSmpPayInstructionSchema
      x-api-path-slug: schemassmppayinstruction-xsd-get
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
      - SmpPayInstruction
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