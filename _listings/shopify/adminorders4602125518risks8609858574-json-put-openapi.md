---
swagger: "2.0"
x-collection-name: Shopify
x-complete: 0
info:
  title: Shopify Update an existing risk detail line on an order
  description: Update an existing risk detail line on an order.
  version: 1.0.0
host: DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /admin/orders/4554953422/refunds/calculate.json:
    post:
      summary: Calculate a refund for a line item and shipping
      description: Calculate a refund for a line item and shipping.
      operationId: postAdminOrders4554953422RefundsCalculate.json
      x-api-path-slug: adminorders4554953422refundscalculate-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Calculate
      - Refunda
      - Line
      - Item
      - Shipping
  /admin/orders/4602125518/risks/8609858574.json:
    put:
      summary: Update an existing risk detail line on an order
      description: Update an existing risk detail line on an order.
      operationId: putAdminOrders4602125518Risks8609858574.json
      x-api-path-slug: adminorders4602125518risks8609858574-json-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Existing
      - Risk
      - Detail
      - Line
      - "On"
      - Order
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