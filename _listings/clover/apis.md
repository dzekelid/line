---
name: Clover
x-slug: clover
description: Clover, a First Data company, builds the largest open-architecture point
  of sale solution aimed at small &amp; medium sized business owners. Our products
  are changing the consumer/merchant experience for the better, opening avenues for
  seamless customer-merchant interactions. There are five versions of Clover, including
  the Clover Station, Clover Mobile, Clover Mini, Clover Go, and Clover Flex. With
  Clover, First Data is aiming to create the largest open architecture operating system
  for commerce-enabling solutions and applications for business owners.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
x-kinRank: "7"
x-alexaRank: "23096"
tags: Line
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/line/master/_listings/clover/apis.md
specificationVersion: "0.14"
apis:
- name: ' - Get all line items for an order'
  x-api-slug: v3merchantsmidordersorderidline-items-get
  description: Get all line items for an order.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/line/master/_listings/clover/v3merchantsmidordersorderidline-items-get-openapi.md
- name: ' - Create a new line item'
  x-api-slug: v3merchantsmidordersorderidline-items-post
  description: Create a new line item.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/line/master/_listings/clover/v3merchantsmidordersorderidline-items-post-openapi.md
- name: ' - Get a line item'
  x-api-slug: v3merchantsmidordersorderidline-itemslineitemid-get
  description: Get a line item.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/line/master/_listings/clover/v3merchantsmidordersorderidline-itemslineitemid-get-openapi.md
- name: ' - Update a line item'
  x-api-slug: v3merchantsmidordersorderidline-itemslineitemid-post
  description: Update a line item.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/line/master/_listings/clover/v3merchantsmidordersorderidline-itemslineitemid-post-openapi.md
- name: ' - Void a line item'
  x-api-slug: v3merchantsmidordersorderidline-itemslineitemid-delete
  description: Void a line item.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/line/master/_listings/clover/v3merchantsmidordersorderidline-itemslineitemid-delete-openapi.md
- name: ' - Create a discount on an order or line item'
  x-api-slug: v3merchantsmidordersorderidline-itemslineitemiddiscounts-post
  description: Create a discount on an order or line item.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/line/master/_listings/clover/v3merchantsmidordersorderidline-itemslineitemiddiscounts-post-openapi.md
- name: ' - Delete a discount'
  x-api-slug: v3merchantsmidordersorderidline-itemslineitemiddiscountsdiscountid-delete
  description: Delete a discount.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/line/master/_listings/clover/v3merchantsmidordersorderidline-itemslineitemiddiscountsdiscountid-delete-openapi.md
- name: ' - Apply a modification to a line item'
  x-api-slug: v3merchantsmidordersorderidline-itemslineitemidmodifications-post
  description: 'Create a modification, a record of a modifier as it exists at the
    time it is applied to the lineItem. To view current modifications use an ''expand=modifications''
    query parameter on the lineItem. To learn more about applying a modification see:
    https://docs.clover.com/build/working-with-orders/#add-item-modifiers'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/line/master/_listings/clover/v3merchantsmidordersorderidline-itemslineitemidmodifications-post-openapi.md
- name: ' - Remove a modification from a line item'
  x-api-slug: v3merchantsmidordersorderidline-itemslineitemidmodificationsmodificationid-delete
  description: Delete a modification by UUID, removing the record of an applied modification
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/line/master/_listings/clover/v3merchantsmidordersorderidline-itemslineitemidmodificationsmodificationid-delete-openapi.md
- name: ' - Create multiple line items in bulk.'
  x-api-slug: v3merchantsmidordersorderidbulk-line-items-post
  description: Create multiple line items in bulk..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/line/master/_listings/clover/v3merchantsmidordersorderidbulk-line-items-post-openapi.md
- name: ' - Void a line item'
  x-api-slug: v3merchantsmidordersorderidvoided-line-items-post
  description: Void a line item.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/line/master/_listings/clover/v3merchantsmidordersorderidvoided-line-items-post-openapi.md
- name: ' - Get order line items that were recorded after a void'
  x-api-slug: v3merchantsmidvoided-line-items-get
  description: Get order line items that were recorded after a void.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/line/master/_listings/clover/v3merchantsmidvoided-line-items-get-openapi.md
- name: ' - Create or exchange a line item'
  x-api-slug: v3merchantsmidordersorderidline-itemsoldlineitemidexchangelineitemid-post
  description: Create or exchange a line item.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clover-logo.png
  humanURL: https://www.clover.com
  baseURL: https:///merchants/https://api.clover.com
  tags: SaaS, Technology, Mobile, internet, Point of Sale, Pos, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/line/master/_listings/clover/v3merchantsmidordersorderidline-itemsoldlineitemidexchangelineitemid-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://cloudflare.api.gallery.streamdata.io
- type: x-api-stack
  url: http://clover.stack.network
- type: x-crunchbase
  url: https://crunchbase.com/organization/clover
- type: x-developer
  url: https://www.clover.com/developers
- type: x-documentation
  url: https://docs.clover.com/
- type: x-github
  url: https://github.com/clover
- type: x-twitter
  url: https://twitter.com/CloverPOS
- type: x-website
  url: https://www.clover.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---