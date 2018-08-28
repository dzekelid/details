{
  "info": {
    "name": "U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility Report (DFR) Detailed Facility Report Tribes Service",
    "_postman_id": "7a1448a2-0d00-4872-bfbe-e45a0b17c24f",
    "description": "This procedure obtains data for the Tribes and Reservations section of the DFR.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "7c93f8fa-7027-406a-be72-68fd9eae6752",
      "name": "this-procedure-obtains-data-for-air-compliance-in-the-environmental-conditions-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_air_compliance?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for Air Compliance in the Environmental Conditions Section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "f03be5d3-76af-4608-95b6-5c10fbe8a2e5"
        }
      ]
    },
    {
      "id": "1ce80aff-69a5-4fd9-b11b-fb06d485271b",
      "name": "this-procedure-obtains-data-for-air-quality-in-the-environmental-conditions-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_air_quality?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for Air Quality in the Environmental Conditions Section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "314f8307-cbed-4c99-a27d-d960296a1499"
        }
      ]
    },
    {
      "id": "ccd25b93-09d8-4b9b-8917-bafe5765cec2",
      "name": "this-procedure-obtains-data-for-the-compliance-monitoring-history-5-years-in-the-enforcement-and-com",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_compliance_history?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the Compliance Monitoring History (5 years) in the Enforcement and Compliance Section of the Detailed Facility report."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "a0bb5432-6f6f-4f4f-8e6b-556f3422a832"
        }
      ]
    },
    {
      "id": "73db97dd-f18b-4d64-9cf1-ede13f11739c",
      "name": "this-procedure-obtains-data-for-compliance-summary-data-in-the-enforcement-and-compliance-section-of",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_compliance_summary?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for Compliance Summary Data in the Enforcement and Compliance Section of the Detailed Facility report."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "aedb5fae-dda2-46f9-b66f-474b632bf12a"
        }
      ]
    },
    {
      "id": "42efd94a-b62e-4ce0-b425-2326e3a96011",
      "name": "this-procedure-obtains-data-for-the-cwa-facilitylevel-status-section-located-in-the-three-year-compl",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_cwa_3yr_compliance?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the CWA Facility-Level Status section located in the Three Year Compliance Status by Quarter portion of the DFR. Valid Compliance Statuses are as follows:\n> \"In Viol\" = Facility is in violation\n> \"No Viol\" = No violation found\n> \"Unk\" = Unknown status\n> \"SNC/Cat 1\" = SNC/Category I violation found"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "50b8aaf5-7f6d-48bb-8da3-973eecee505e"
        }
      ]
    },
    {
      "id": "e6a54662-142d-47eb-9126-9401443b989e",
      "name": "this-procedure-obtains-data-for-the-cwa-compliance-schedule-violations-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_cwa_cs_compliance?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the CWA Compliance Schedule Violations section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "3a33399a-90b8-4ab3-bbc9-ea6f43ffbecc"
        }
      ]
    },
    {
      "id": "4195c3b0-2f4c-44d9-b039-c51ce08ea600",
      "name": "this-procedure-obtains-data-for-the-cwa-pollutant-discharge-section-located-in-the-three-year-compli",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_cwa_eff_alr?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the CWA Pollutant Discharge section located in the Three Year Compliance Status by Quarter portion of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "7771199a-47c6-4fa1-84d2-a8600b3d1dfa"
        }
      ]
    },
    {
      "id": "6cf76a38-7ff6-438d-883d-10e67743c575",
      "name": "this-procedure-obtains-data-for-the-cwa-effluent-compliance-section-on-the-dfr---",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_cwa_eff_compliance?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the CWA Effluent Compliance section on the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "6d3b55aa-cc58-411a-967e-ee5a1d2f98d1"
        }
      ]
    },
    {
      "id": "f9995f40-74ff-43d5-b59e-a803e2427df8",
      "name": "this-procedure-obtains-data-for-the-cwa-permit-schedule-violations-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_cwa_ps_compliance?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the CWA Permit Schedule Violations section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "a6e7c896-9e6d-4b7f-920f-1bdae67d5a0f"
        }
      ]
    },
    {
      "id": "c7c5e8c7-7b36-4dab-add2-7a3993fac32b",
      "name": "this-procedure-obtains-data-for-the-cwa-sncrnc-history-section-located-in-the-three-year-ompliance-s",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_cwa_rnc_compliance?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the CWA SNC/RNC History section located in the Three Year ompliance Status by Quarter portion of the DFR. Valid Compliance Statuses are as follows.\n> S = SNC/Category I - an enforcement action has been issued, and the facility is not meeting its compliance schedule\n> E = SNC/Category I - effluent violations of monthly average limits (Technical Review Criteria and chronic)\n> X = SNC/Category I - effluent violations of non-monthly average limits (Technical Review Criteria and chronic)\n> T = SNC/Category I - compliance schedule reporting violation\n> D = SNC/Category I - reporting violation - nonreceipt of DMR\n> N = RNC/Category II - reportable non-compliance\n> P = Resolved Pending - an enforcement action has been issued, and facility compliance with the action is pending final completion\n> R = Resolved - the facility has returned to compliance with its permit conditions, either with or without issuance of an enforcement action\n> C = Not considered in RNC/SNC based on manual review of data by state or EPA region. This manual override status is also indicated by a superscripted \"m\".\n> Blank = Not considered in RNC/SNC\n> N/A = EPA's data system is not able to determine the facility-level compliance status based upon the information available. This information may be available from a state database."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "03657ca2-0030-479a-b1b9-ab48de2426da"
        }
      ]
    },
    {
      "id": "91699857-a4f9-457b-8cf1-465c5dfe7f8c",
      "name": "this-procedure-obtains-data-for-the-cwa-single-event-violations-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_cwa_se_compliance?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the CWA Single Event Violations section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "2eb38e69-62ab-4bb6-8ba0-c9b3757e4f7f"
        }
      ]
    },
    {
      "id": "a5c8adf4-741e-4ae4-9877-b3956cbde263",
      "name": "returns-a-complex-object-with-demographics-from-the-2010-census-and-2010-american-community-survey-b",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_demographics?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Returns a complex object with Demographics from the 2010 Census and 2010 American Community Survey based on a 3 mile radius around the facility spatial coordinates."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "e7c42ae7-6632-4acd-a0c6-d875a9cad4a8"
        }
      ]
    },
    {
      "id": "212b9c29-e1e3-4886-9866-e8f08805234a",
      "name": "this-procedure-is-the-overall-service-for-the-detailed-facility-report--it-returns-all-of-the-data-d",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_dfr?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure is the overall service for the Detailed Facility Report. It returns all of the data displayed in the DFR web report by invoking individual procedures that each return a targeted portion of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "7f711dff-de33-4d57-9f2b-2779686a2a8a"
        }
      ]
    },
    {
      "id": "ab22f3d4-570c-4e12-bbd1-150c227a158b",
      "name": "this-procedure-obtains-data-for-the-enforcement-and-compliance-summary-in-the-facility-summary-secti",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_enforcement_summary?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the Enforcement and Compliance Summary in the Facility Summary section of the Detailed Facility Report."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "8a429f97-29bf-423f-b97c-90b9d284ac75"
        }
      ]
    },
    {
      "id": "bc25a0fa-53ab-412b-a668-914c961d92f9",
      "name": "this-procedure-obtains-data-for-the-formal-enforcement-actions-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_formal_actions?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the Formal Enforcement Actions section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "44c60103-103f-4056-8cbf-df8f5c4e0e8a"
        }
      ]
    },
    {
      "id": "8e8bf24a-63f8-47e2-85f1-40d3357a7188",
      "name": "this-procedure-obtains-data-for-the-integrated-compliance-information-system-formal-enforcement-acti",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_icis_formal_actions?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the Integrated Compliance Information System, Formal Enforcement Actions section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "b96b411a-e27c-42bb-bb56-f9df8184bc79"
        }
      ]
    },
    {
      "id": "528abb83-b570-414b-8c10-759dd08e6917",
      "name": "this-procedure-obtains-data-for-enforcement-and-compliance-summary-section-of-the-detailed-facility-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_inspections?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for Enforcement and Compliance Summary Section of the Detailed Facility report."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "0bf29259-cfec-4267-b79b-5bd196ddcf8a"
        }
      ]
    },
    {
      "id": "bee9507a-36c6-4763-811e-80f8924d022d",
      "name": "returns-an-object-with-the-facilitys-latitude-and-longitude-coordinates-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_map?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Returns an object with the facility's latitude and longitude coordinates."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "687fdf10-492b-4c7a-ae3a-d4dc02289af1"
        }
      ]
    },
    {
      "id": "dbd7672f-e787-4bc4-9da6-977d1425ca42",
      "name": "this-procedure-obtains-data-for-the-facility-naics-codes-section-in-facilitysystem-characteristics-o",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_naics?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the Facility NAICS Codes section in Facility/System Characteristics of the Detailed Facility Report."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "5ca6cc76-5952-46b7-81cc-518f80de7db9"
        }
      ]
    },
    {
      "id": "eadba368-9329-4cff-874e-96eec1c30e44",
      "name": "this-procedure-obtains-data-for-the-permits-by-statute-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_nnnPermits?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the Permits by Statute section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "55ae16ea-e556-44c3-9a45-7826b198a456"
        }
      ]
    },
    {
      "id": "a9a84e98-4255-4df8-97fa-d262857772ab",
      "name": "this-procedure-obtains-data-for-the-noticesinformal-actions-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_notices?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the Notices/Informal Actions section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "32d6b37b-ed0e-4e8b-9492-a798caa23c7e"
        }
      ]
    },
    {
      "id": "d171e1a2-4268-4bbf-9c1b-fbf3b13ba250",
      "name": "this-procedure-obtains-data-for-the-following-sections-of-the-detailed-facility-report--facility-inf",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_permits?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the following sections of the Detailed Facility Report.\n> Facility Information (FRS) in the Facility Summary.\n> Regulatory Interests in the Facility Summary.\n> Also Reports in the Facility Summary.\n> Facility/System Characteristics in Facility/System Characteristics.\n> Facility Contact Information in Facility/System Characteristics.\n> Facility SIC Codes in Facility/System Characteristics section.\n> Facility NAICS Codes in Facility/System Characteristics section."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "7875d3bf-d35c-454f-bd9b-ffd918b0acff"
        }
      ]
    },
    {
      "id": "24474c7e-f5f2-43fa-96ee-5c68cc8d2940",
      "name": "this-procedure-obtains-data-for-the-rcra-compliance-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_rcra_compliance?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the RCRA Compliance section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "8938be4c-82b9-4028-9207-504cb886e894"
        }
      ]
    },
    {
      "id": "6dbb132d-a495-4c4b-b3b9-74dc538d2360",
      "name": "this-procedure-obtains-data-for-the-sdwa-lead-and-copper-rule-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_sdwa_lead_and_copper?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the SDWA, Lead and Copper Rule section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "c6f0fa11-6c14-4a39-9152-1989a07c4e2f"
        }
      ]
    },
    {
      "id": "ebb402c5-d493-4897-b7c6-a8d64e4d8ae3",
      "name": "this-procedure-obtains-data-for-the-sdwa-sanitary-surveys-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_sdwa_sanitary_surveys?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the SDWA, Sanitary Surveys section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "d9eafe21-f199-4f48-a59b-6854482ffe51"
        }
      ]
    },
    {
      "id": "3934518b-124d-4a75-80cd-b0682ea37388",
      "name": "this-procedure-obtains-data-for-the-sdwa-sanitary-site-visits-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_sdwa_site_visits?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the SDWA, Sanitary Site Visits section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "fed2635f-48b6-4ba0-84c7-a026cfb84b61"
        }
      ]
    },
    {
      "id": "0aea5a39-ae23-4aa2-8a2a-e1cae50e8a17",
      "name": "this-procedure-obtains-data-for-the-sdwa-violations-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_sdwa_violations?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the SDWA Violations section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "3d9f7719-cea6-42db-aabb-e76d503811dc"
        }
      ]
    },
    {
      "id": "08970adf-6d28-4428-b241-ff6bc8eb3d4a",
      "name": "this-procedure-obtains-data-for-the-sdwa-compliance-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_sdwis_compliance?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the SDWA Compliance section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "e1740f57-990e-4254-ade0-d1ac83dc323c"
        }
      ]
    },
    {
      "id": "dd05b729-545d-4a94-b38f-a6c2cefee302",
      "name": "this-procedure-obtains-data-for-the-facility-sic-codes-section-in-facilitysystem-characteristics-of-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_sic_codes?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the Facility SIC Codes section in Facility/System Characteristics of the Detailed Facility Report."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "1b6748a7-d950-424c-8b66-02bcb2fde500"
        }
      ]
    },
    {
      "id": "9fb6f7a9-70fa-43a9-a55b-f9e874697baf",
      "name": "returns-an-object-with-the-facility-coordinate-spatial-metadata-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_spatial_metadata?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Returns an object with the facility coordinate spatial metadata."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "9133b1d6-5d3f-4e7e-bc5a-a5d185b39259"
        }
      ]
    },
    {
      "id": "d48f8cf9-7d44-420d-adc7-2341484151c8",
      "name": "this-procedure-obtains-data-for-the-tri-history-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_tri_history?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the TRI History section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "59b34654-1ec2-42ef-af42-0fa4114d35b7"
        }
      ]
    },
    {
      "id": "32f660cf-d103-49da-9c0e-389c4f27d2a3",
      "name": "this-procedrue-obtains-data-for-the-tri-releases-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_tri_releases?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedrue obtains data for the TRI Releases section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "bf7d22a3-5779-46e4-9226-8245b1fb3b59"
        }
      ]
    },
    {
      "id": "65f4a604-0b81-4ba1-b126-77e24b3e40cf",
      "name": "this-procedure-obtains-data-for-the-tribes-and-reservations-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_tribes?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the Tribes and Reservations section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "e26618db-656a-448f-86c2-6b2da914d4e8"
        }
      ]
    }
  ]
}