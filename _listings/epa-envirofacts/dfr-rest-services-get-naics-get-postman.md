{
  "info": {
    "name": "U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility Report (DFR) Detailed Facility Report NAICS Code Service",
    "_postman_id": "4449d3ea-f1c0-48a4-8196-a37132906ada",
    "description": "This procedure obtains data for the Facility NAICS Codes section in Facility/System Characteristics of the Detailed Facility Report.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "cbccb1e1-98d0-4e1a-87c1-a137a932f6e2",
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
          "id": "8fc07a39-9cd7-45d1-a4f8-15998fd37f58"
        }
      ]
    },
    {
      "id": "94fd4a24-2866-4e28-b98b-312e592fabda",
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
          "id": "6829da17-ae15-4ee7-bfb3-afc4fea8a878"
        }
      ]
    },
    {
      "id": "e6115127-7419-42f7-99ae-21097a40441a",
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
          "id": "7d495cb8-10e7-430c-b99b-e25b43582fbb"
        }
      ]
    },
    {
      "id": "c5c11717-9c9c-47ed-9af9-3d870f4e1690",
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
          "id": "e193fb73-ecd4-4f2b-8495-0660b841445c"
        }
      ]
    },
    {
      "id": "ac17afba-b23e-4a85-a55c-e75eca50c9af",
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
          "id": "1b4a206b-ffa6-48ea-b2f7-d8ff674e2c8b"
        }
      ]
    },
    {
      "id": "3661b3c3-1264-4605-a2b9-c63568bde934",
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
          "id": "5906e6d1-cffc-4b86-85c0-8e4b723e0d1b"
        }
      ]
    },
    {
      "id": "fe7d8bdd-16d0-4eaf-8cca-6f9419276dc6",
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
          "id": "58509fec-68db-429b-bedf-56b1a74bdb72"
        }
      ]
    },
    {
      "id": "56d05ba7-e39b-4dab-afd2-7d9d53bdd55f",
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
          "id": "d656160c-f632-4138-9e09-07af25553148"
        }
      ]
    },
    {
      "id": "d134109c-b0bd-454a-b692-8d76a41d19e5",
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
          "id": "e17f34ef-05bd-42b3-a8fd-dc687cc7f143"
        }
      ]
    },
    {
      "id": "e81f11ec-5ab9-41a6-b01b-37a91024a946",
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
          "id": "8c80531d-8f56-491c-b770-1e9321456db3"
        }
      ]
    },
    {
      "id": "390132c9-8374-48a4-8554-2bc6c0bdd199",
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
          "id": "2a35ba85-b029-4688-9af9-5c992a6db5be"
        }
      ]
    },
    {
      "id": "b3a08dfb-821e-4c0b-a6a8-fe0d25e6e79d",
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
          "id": "40886e7a-1e8d-4bc7-a2df-a2dd2fc80eab"
        }
      ]
    },
    {
      "id": "be8dc640-27bc-4028-8a85-8f6393b2ddd4",
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
          "id": "3457a631-2c72-411a-b320-f02f640a6407"
        }
      ]
    },
    {
      "id": "02e1b8eb-8aec-4137-9c75-0380852eae55",
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
          "id": "ca380f4b-1e8b-40f1-8311-2aa045f94ae5"
        }
      ]
    },
    {
      "id": "70dcec46-7bab-453e-9f7d-8ea868b9822a",
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
          "id": "a8c72d7d-258b-4df4-ab88-f8ec64557cf8"
        }
      ]
    },
    {
      "id": "4937e31d-716f-46d5-a5b8-7b87bdb92409",
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
          "id": "fbb2fce2-a0fb-447e-bc5d-ae0ca6aa0ac7"
        }
      ]
    },
    {
      "id": "c9e82d0e-278d-40ec-ac12-5f25805ce280",
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
          "id": "9846d0b1-72a3-44a7-bf6e-490aa248cb7f"
        }
      ]
    },
    {
      "id": "22c72eed-f06a-4332-890b-2675a0f056d1",
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
          "id": "cfa4f40a-5a7a-40d6-a8c9-547841a3d037"
        }
      ]
    },
    {
      "id": "9b8a9a83-4d84-40b9-a9e6-94d529b4640e",
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
          "id": "e4e06604-43ce-4595-8cf8-4f7f9696fc36"
        }
      ]
    }
  ]
}