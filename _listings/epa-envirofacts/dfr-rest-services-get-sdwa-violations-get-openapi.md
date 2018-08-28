---
swagger: "2.0"
x-collection-name: EPA Envirofacts
x-complete: 0
info:
  title: U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility
    Report (DFR) Detailed Facility Report SDWA Violations Service
  description: This procedure obtains data for the SDWA Violations section of the
    DFR.
  contact:
    name: US EPA, OECA Integration, Targeting and Access Branch
  version: 0.0.0
host: ofmpub.epa.gov
basePath: /echo
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /dfr_rest_services.get_water_quality:
    get:
      summary: Detailed Facility Report Water Quality Service
      description: This procedure obtains data for the Water Quality section of the
        DFR.
      operationId: this-procedure-obtains-data-for-the-water-quality-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-water-quality-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - Water
      - Quality
      - Service
  /dfr_rest_services.get_tribes:
    get:
      summary: Detailed Facility Report Tribes Service
      description: This procedure obtains data for the Tribes and Reservations section
        of the DFR.
      operationId: this-procedure-obtains-data-for-the-tribes-and-reservations-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-tribes-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - Tribes
      - Service
  /dfr_rest_services.get_tri_releases:
    get:
      summary: Detailed Facility Report TRI Releases Service
      description: This procedrue obtains data for the TRI Releases section of the
        DFR.
      operationId: this-procedrue-obtains-data-for-the-tri-releases-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-tri-releases-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - TRI
      - Releases
      - Service
  /dfr_rest_services.get_tri_history:
    get:
      summary: Detailed Facility Report TRI History Service
      description: This procedure obtains data for the TRI History section of the
        DFR.
      operationId: this-procedure-obtains-data-for-the-tri-history-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-tri-history-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - TRI
      - History
      - Service
  /dfr_rest_services.get_spatial_metadata:
    get:
      summary: Detailed Facility Report Spatial Metadata Service
      description: Returns an object with the facility coordinate spatial metadata.
      operationId: returns-an-object-with-the-facility-coordinate-spatial-metadata-
      x-api-path-slug: dfr-rest-services-get-spatial-metadata-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - Spatial
      - Metadata
      - Service
  /dfr_rest_services.get_sic_codes:
    get:
      summary: Detailed Facility Report SIC Code Service
      description: This procedure obtains data for the Facility SIC Codes section
        in Facility/System Characteristics of the Detailed Facility Report.
      operationId: this-procedure-obtains-data-for-the-facility-sic-codes-section-in-facilitysystem-characteristics-of-
      x-api-path-slug: dfr-rest-services-get-sic-codes-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - SIC
      - Code
      - Service
  /dfr_rest_services.get_sdwis_compliance:
    get:
      summary: Detailed Facility Report SDWIS Compliance Service
      description: This procedure obtains data for the SDWA Compliance section of
        the DFR.
      operationId: this-procedure-obtains-data-for-the-sdwa-compliance-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-sdwis-compliance-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - SDWIS
      - Compliance
      - Service
  /dfr_rest_services.get_sdwa_violations:
    get:
      summary: Detailed Facility Report SDWA Violations Service
      description: This procedure obtains data for the SDWA Violations section of
        the DFR.
      operationId: this-procedure-obtains-data-for-the-sdwa-violations-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-sdwa-violations-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - SDWA
      - Violations
      - Service
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