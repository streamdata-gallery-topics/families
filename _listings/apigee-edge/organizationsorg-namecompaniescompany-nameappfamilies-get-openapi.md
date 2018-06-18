---
swagger: "2.0"
x-collection-name: Apigee Edge
x-complete: 0
info:
  title: Apigee Edge Get Organizations Name Companies Company Name Appfamilies
  description: An expanded list of all app families in an organization, listing Apps
    in the collection.
  version: 1.0.0
host: api.enterprise.apigee.com
basePath: /v1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /organizations/{org_name}/companies/{company_name}/appfamilies:
    get:
      summary: Get Organizations Name Companies Company Name Appfamilies
      description: An expanded list of all app families in an organization, listing
        Apps in the collection.
      operationId: getOrganizationsOrgNameCompaniesCompanyNameAppfamilies
      x-api-path-slug: organizationsorg-namecompaniescompany-nameappfamilies-get
      parameters:
      - in: path
        name: company_name
        description: Mention the company name
      - in: path
        name: org_name
        description: Mention the organization name
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Companies
      - Companies
      - Applications
      - Families
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