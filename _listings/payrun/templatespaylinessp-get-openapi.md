---
swagger: "2.0"
x-collection-name: PayRun
x-complete: 0
info:
  title: Pay Run.IO Gets the pay line ssp template
  description: Return the pay line ssp data object template
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
  /Employer/{EmployerId}/Employee/{EmployeeId}/PayLine/{PayLineId}:
    get:
      summary: Gets the specified pay line from the employee
      description: Returns the specified pay line from employee
      operationId: GetPayLineFromEmployee
      x-api-path-slug: employeremployeridemployeeemployeeidpaylinepaylineid-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployeeId
        description: The employees unique identifier
      - in: path
        name: EmployerId
        description: The employers unique identifier
      - in: path
        name: PayLineId
        description: The pay line unique identifier
      responses:
        200:
          description: OK
      tags:
      - Specified
      - Pay
      - Line
      - From
      - Employee
  /Employer/{EmployerId}/ReportLine/{ReportLineId}:
    get:
      summary: Gets the specified report line from the employer
      description: Returns the specified pay line from employee
      operationId: GetReportLineFromEmployer
      x-api-path-slug: employeremployeridreportlinereportlineid-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployerId
        description: The employers unique identifier
      - in: path
        name: ReportLineId
        description: The report line unique identifier
      responses:
        200:
          description: OK
      tags:
      - Specified
      - Report
      - Line
      - From
      - Employer
  /Templates/payline:
    get:
      summary: Gets the pay line template
      description: Return the pay line data object template
      operationId: GetPayLineTemplate
      x-api-path-slug: templatespayline-get
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
      - Pay
      - Line
      - Template
  /Templates/paylinebenefit:
    get:
      summary: Gets the pay line benefit template
      description: Return the pay line benefit data object template
      operationId: GetPayLineBenefitTemplate
      x-api-path-slug: templatespaylinebenefit-get
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
      - Pay
      - Line
      - Benefit
      - Template
  /Templates/paylineni:
    get:
      summary: Gets the pay line NI template
      description: Return the pay line NI data object template
      operationId: GetPayLineNiTemplate
      x-api-path-slug: templatespaylineni-get
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
      - Pay
      - Line
      - NI
      - Template
  /Templates/paylinepension:
    get:
      summary: Gets the pay line pension template
      description: Return the pay line pension data object template
      operationId: GetPayLinePensionTemplate
      x-api-path-slug: templatespaylinepension-get
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
      - Pay
      - Line
      - Pension
      - Template
  /Templates/paylinesap:
    get:
      summary: Gets the pay line sap template
      description: Return the pay line sap data object template
      operationId: GetPayLineSapTemplate
      x-api-path-slug: templatespaylinesap-get
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
      - Pay
      - Line
      - Sap
      - Template
  /Templates/paylineshpp:
    get:
      summary: Gets the pay line shpp template
      description: Return the pay line shpp data object template
      operationId: GetPayLineShppTemplate
      x-api-path-slug: templatespaylineshpp-get
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
      - Pay
      - Line
      - Shpp
      - Template
  /Templates/paylinesmp:
    get:
      summary: Gets the pay line smp template
      description: Return the pay line smp data object template
      operationId: GetPayLineSmpTemplate
      x-api-path-slug: templatespaylinesmp-get
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
      - Pay
      - Line
      - Smp
      - Template
  /Templates/paylinespp:
    get:
      summary: Gets the pay line spp template
      description: Return the pay line spp data object template
      operationId: GetPayLineSppTemplate
      x-api-path-slug: templatespaylinespp-get
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
      - Pay
      - Line
      - Spp
      - Template
  /Templates/paylinessp:
    get:
      summary: Gets the pay line ssp template
      description: Return the pay line ssp data object template
      operationId: GetPayLineSspTemplate
      x-api-path-slug: templatespaylinessp-get
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
      - Pay
      - Line
      - Ssp
      - Template
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