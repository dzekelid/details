---
swagger: "2.0"
x-collection-name: EPA Envirofacts
x-complete: 0
info:
  title: U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility
    Report (DFR) Detailed Facility Report Demographics Report Service
  description: Returns a complex object with Demographics from the 2010 Census and
    2010 American Community Survey based on a 3 mile radius around the facility spatial
    coordinates.
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
  /dfr_rest_services.get_sdwa_site_visits:
    get:
      summary: Detailed Facility Report SDWA Sanitary Site Visits Service
      description: This procedure obtains data for the SDWA, Sanitary Site Visits
        section of the DFR.
      operationId: this-procedure-obtains-data-for-the-sdwa-sanitary-site-visits-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-sdwa-site-visits-get
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
      - Sanitary
      - Site
      - Visits
      - Service
  /dfr_rest_services.get_sdwa_sanitary_surveys:
    get:
      summary: Detailed Facility Report SDWA Sanitary Surveys Service
      description: This procedure obtains data for the SDWA, Sanitary Surveys section
        of the DFR.
      operationId: this-procedure-obtains-data-for-the-sdwa-sanitary-surveys-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-sdwa-sanitary-surveys-get
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
      - Sanitary
      - Surveys
      - Service
  /dfr_rest_services.get_sdwa_lead_and_copper:
    get:
      summary: Detailed Facility Report SDWA Lead and Copper Service
      description: This procedure obtains data for the SDWA, Lead and Copper Rule
        section of the DFR.
      operationId: this-procedure-obtains-data-for-the-sdwa-lead-and-copper-rule-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-sdwa-lead-and-copper-get
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
      - Lead
      - Copper
      - Service
  /dfr_rest_services.get_rcra_compliance:
    get:
      summary: Detailed Facility Report RCRA Compliance Service
      description: This procedure obtains data for the RCRA Compliance section of
        the DFR.
      operationId: this-procedure-obtains-data-for-the-rcra-compliance-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-rcra-compliance-get
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
      - RCRA
      - Compliance
      - Service
  /dfr_rest_services.get_permits:
    get:
      summary: Detailed Facility Report Permits Service
      description: |-
        This procedure obtains data for the following sections of the Detailed Facility Report.
        > Facility Information (FRS) in the Facility Summary.
        > Regulatory Interests in the Facility Summary.
        > Also Reports in the Facility Summary.
        > Facility/System Characteristics in Facility/System Characteristics.
        > Facility Contact Information in Facility/System Characteristics.
        > Facility SIC Codes in Facility/System Characteristics section.
        > Facility NAICS Codes in Facility/System Characteristics section.
      operationId: this-procedure-obtains-data-for-the-following-sections-of-the-detailed-facility-report--facility-inf
      x-api-path-slug: dfr-rest-services-get-permits-get
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
      - Permits
      - Service
  /dfr_rest_services.get_notices:
    get:
      summary: Detailed Facility Report Notices Service
      description: This procedure obtains data for the Notices/Informal Actions section
        of the DFR.
      operationId: this-procedure-obtains-data-for-the-noticesinformal-actions-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-notices-get
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
      - Notices
      - Service
  /dfr_rest_services.get_nnnPermits:
    get:
      summary: Detailed Facility Report Permits by Statute Service
      description: This procedure obtains data for the Permits by Statute section
        of the DFR.
      operationId: this-procedure-obtains-data-for-the-permits-by-statute-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-nnnpermits-get
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
      - Permits
      - By
      - Statute
      - Service
  /dfr_rest_services.get_naics:
    get:
      summary: Detailed Facility Report NAICS Code Service
      description: This procedure obtains data for the Facility NAICS Codes section
        in Facility/System Characteristics of the Detailed Facility Report.
      operationId: this-procedure-obtains-data-for-the-facility-naics-codes-section-in-facilitysystem-characteristics-o
      x-api-path-slug: dfr-rest-services-get-naics-get
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
      - NAICS
      - Code
      - Service
  /dfr_rest_services.get_map:
    get:
      summary: Detailed Facility Report Map Service
      description: Returns an object with the facility's latitude and longitude coordinates.
      operationId: returns-an-object-with-the-facilitys-latitude-and-longitude-coordinates-
      x-api-path-slug: dfr-rest-services-get-map-get
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
      - Map
      - Service
  /dfr_rest_services.get_inspections:
    get:
      summary: Detailed Facility Report Inspections Summary Service
      description: This procedure obtains data for Enforcement and Compliance Summary
        Section of the Detailed Facility report.
      operationId: this-procedure-obtains-data-for-enforcement-and-compliance-summary-section-of-the-detailed-facility-
      x-api-path-slug: dfr-rest-services-get-inspections-get
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
      - Inspections
      - Summary
      - Service
  /dfr_rest_services.get_icis_formal_actions:
    get:
      summary: Detailed Facility Report ICIS Formal Actions Service
      description: This procedure obtains data for the Integrated Compliance Information
        System, Formal Enforcement Actions section of the DFR.
      operationId: this-procedure-obtains-data-for-the-integrated-compliance-information-system-formal-enforcement-acti
      x-api-path-slug: dfr-rest-services-get-icis-formal-actions-get
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
      - ICIS
      - Formal
      - Actions
      - Service
  /dfr_rest_services.get_formal_actions:
    get:
      summary: Detailed Facility Report Formal Actions Service
      description: This procedure obtains data for the Formal Enforcement Actions
        section of the DFR.
      operationId: this-procedure-obtains-data-for-the-formal-enforcement-actions-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-formal-actions-get
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
      - Formal
      - Actions
      - Service
  /dfr_rest_services.get_enforcement_summary:
    get:
      summary: Detailed Facility Report Enforcement Summary Service
      description: This procedure obtains data for the Enforcement and Compliance
        Summary in the Facility Summary section of the Detailed Facility Report.
      operationId: this-procedure-obtains-data-for-the-enforcement-and-compliance-summary-in-the-facility-summary-secti
      x-api-path-slug: dfr-rest-services-get-enforcement-summary-get
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
      - Enforcement
      - Summary
      - Service
  /dfr_rest_services.get_dfr:
    get:
      summary: Detailed Facility Report Service
      description: This procedure is the overall service for the Detailed Facility
        Report. It returns all of the data displayed in the DFR web report by invoking
        individual procedures that each return a targeted portion of the DFR.
      operationId: this-procedure-is-the-overall-service-for-the-detailed-facility-report--it-returns-all-of-the-data-d
      x-api-path-slug: dfr-rest-services-get-dfr-get
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
      - Service
  /dfr_rest_services.get_demographics:
    get:
      summary: Detailed Facility Report Demographics Report Service
      description: Returns a complex object with Demographics from the 2010 Census
        and 2010 American Community Survey based on a 3 mile radius around the facility
        spatial coordinates.
      operationId: returns-a-complex-object-with-demographics-from-the-2010-census-and-2010-american-community-survey-b
      x-api-path-slug: dfr-rest-services-get-demographics-get
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
      - Demographics
      - Report
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