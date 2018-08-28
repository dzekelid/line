---
swagger: "2.0"
x-collection-name: Transport for London Unified
x-complete: 0
info:
  title: Transport for London Unified Line  Mode modes  Status
  description: Gets the line status of for all lines for the given modes.
  version: v1
host: api.tfl.gov.uk
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Line/Meta/DisruptionCategories:
    get:
      summary: Line  Meta  Disruption Categories
      description: Gets a list of valid disruption categories.
      operationId: Line_MetaDisruptionCategories
      x-api-path-slug: linemetadisruptioncategories-get
      responses:
        200:
          description: OK
      tags:
      - Line
      - ""
      - Meta
      - ""
      - Disruption
      - Categories
  /Line/Meta/Modes:
    get:
      summary: Line  Meta  Modes
      description: Gets a list of valid modes.
      operationId: Line_MetaModes
      x-api-path-slug: linemetamodes-get
      responses:
        200:
          description: OK
      tags:
      - Line
      - ""
      - Meta
      - ""
      - Modes
  /Line/Meta/ServiceTypes:
    get:
      summary: Line  Meta  Service Types
      description: Gets a list of valid servicetypes to filter on.
      operationId: Line_MetaServiceTypes
      x-api-path-slug: linemetaservicetypes-get
      responses:
        200:
          description: OK
      tags:
      - Line
      - ""
      - Meta
      - ""
      - Service
      - Types
  /Line/Meta/Severity:
    get:
      summary: Line  Meta  Severity
      description: Gets a list of valid severity codes.
      operationId: Line_MetaSeverity
      x-api-path-slug: linemetaseverity-get
      responses:
        200:
          description: OK
      tags:
      - Line
      - ""
      - Meta
      - ""
      - Severity
  /Line/Mode/{modes}:
    get:
      summary: Line  Mode modes
      description: Gets lines that serve the given modes..
      operationId: Line_GetByMode
      x-api-path-slug: linemodemodes-get
      parameters:
      - in: path
        name: modes
        description: A comma-separated list of modes e
      responses:
        200:
          description: OK
      tags:
      - Line
      - ""
      - Mode
      - Modes
  /Line/Mode/{modes}/Disruption:
    get:
      summary: Line  Mode modes  Disruption
      description: Get disruptions for all lines of the given modes..
      operationId: Line_DisruptionByMode
      x-api-path-slug: linemodemodesdisruption-get
      parameters:
      - in: path
        name: modes
        description: A comma-separated list of modes e
      responses:
        200:
          description: OK
      tags:
      - Line
      - ""
      - Mode
      - Modes
      - ""
      - Disruption
  /Line/Mode/{modes}/Route:
    get:
      summary: Line  Mode modes  Route
      description: Gets all lines and their valid routes for given modes, including
        the name and id of the originating and terminating stops for each route.
      operationId: Line_RouteByMode
      x-api-path-slug: linemodemodesroute-get
      parameters:
      - in: path
        name: modes
        description: A comma-separated list of modes e
      - in: query
        name: serviceTypes
        description: A comma seperated list of service types to filter on
      responses:
        200:
          description: OK
      tags:
      - Line
      - ""
      - Mode
      - Modes
      - ""
      - Route
  /Line/Mode/{modes}/Status:
    get:
      summary: Line  Mode modes  Status
      description: Gets the line status of for all lines for the given modes.
      operationId: Line_StatusByMode
      x-api-path-slug: linemodemodesstatus-get
      parameters:
      - in: query
        name: detail
        description: Include details of the disruptions that are causing the line
          status including the affected stops and routes
      - in: path
        name: modes
        description: A comma-separated list of modes to filter by
      responses:
        200:
          description: OK
      tags:
      - Line
      - ""
      - Mode
      - Modes
      - ""
      - Status
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