{
  "info": {
    "name": "U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility Report (DFR) Detailed Facility Report RCRA Compliance Service",
    "_postman_id": "8c08674c-c500-482f-8c41-976cc2c7c359",
    "description": "This procedure obtains data for the RCRA Compliance section of the DFR.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "56bd2426-392c-4db9-bfe7-102d22377055",
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
          "id": "8a5b65f5-6245-461a-9892-62b43c606c69"
        }
      ]
    },
    {
      "id": "e1312690-7b87-4968-b201-1a9fd4488ef8",
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
          "id": "f27e4cd2-50a1-46ee-ab09-9d769315ee0f"
        }
      ]
    },
    {
      "id": "372ae326-559f-4034-8eca-b2aca827ff37",
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
          "id": "262f8b44-bec1-4f06-9321-e58fa556c15a"
        }
      ]
    },
    {
      "id": "f470affd-07f2-4757-a4bf-fd82668d820f",
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
          "id": "3959f151-a025-4d6c-841e-f688c7bca193"
        }
      ]
    },
    {
      "id": "fb30961b-bec4-48f4-988d-3d6df5390f57",
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
          "id": "912cdef4-3c16-4ffc-9504-36c6db96d459"
        }
      ]
    },
    {
      "id": "9c357954-5081-46fe-ab8e-294d8ad96859",
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
          "id": "fd6b3039-2d58-486c-a23c-82657749bd06"
        }
      ]
    },
    {
      "id": "79efd67d-f860-46ca-becf-8f5d6b99bfbf",
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
          "id": "642fdf4a-e6fc-4828-bf6e-f1f1edb77bab"
        }
      ]
    },
    {
      "id": "0102c31a-ae96-47da-b545-6bcbef2276b7",
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
          "id": "a7057a8f-9c05-4128-950e-bada31d7d416"
        }
      ]
    },
    {
      "id": "0eae5742-a392-47d2-b00e-c52bb43c4d49",
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
          "id": "b93265a2-b95c-43d8-bc16-22e290608bd0"
        }
      ]
    },
    {
      "id": "c2144dd8-8189-412d-9711-62668f976303",
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
          "id": "c7086504-c479-4371-b148-bda9ba5b5c8a"
        }
      ]
    },
    {
      "id": "3ddba05b-2b9c-4095-89de-7c73cd5ea791",
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
          "id": "f85c8a97-efb5-41e7-8ab1-039e2267c4f7"
        }
      ]
    },
    {
      "id": "a9f84f69-186c-45a1-9486-18c2a51bb45c",
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
          "id": "2e70fb05-1fd7-42ed-b7d8-0c6dabd504c9"
        }
      ]
    },
    {
      "id": "e434940e-d11b-482d-b634-26cefbb6ddd1",
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
          "id": "090656cf-cd3c-4b2a-83ee-0240dcc06cf7"
        }
      ]
    },
    {
      "id": "abb4859c-ce08-4bcb-84cb-2552cf7e7a27",
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
          "id": "090dac62-f2ac-4bfc-890f-cdbf978e3381"
        }
      ]
    },
    {
      "id": "d1524769-74e8-4a94-87d5-144d00ff05df",
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
          "id": "8d48c353-bdc0-4be6-9298-5c1bc4379529"
        }
      ]
    },
    {
      "id": "f52511a4-3889-4a38-9c6d-37d421b2e93c",
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
          "id": "98a3cf43-974e-4b63-91e4-1b203af8ecde"
        }
      ]
    },
    {
      "id": "36720312-ac3c-4986-8297-650e88804924",
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
          "id": "037e4d08-f86c-4076-9603-564f5ef15e35"
        }
      ]
    },
    {
      "id": "49677b4a-659a-453c-b684-42dba0daaeec",
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
          "id": "33a43c0b-c6c6-4e67-8b95-e7152b138412"
        }
      ]
    },
    {
      "id": "1099ca55-d9cb-4220-af70-e92a8568eade",
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
          "id": "6e535734-9b67-4da0-987f-34bfcea634ae"
        }
      ]
    },
    {
      "id": "19188faa-95a3-46f3-a99e-6e6141acd364",
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
          "id": "b3473f5a-e7ec-40f5-9472-a95815c4c7fe"
        }
      ]
    },
    {
      "id": "1fc98689-0213-47c4-bd8b-0f5189cbc62c",
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
          "id": "9e745d95-ec38-4345-b9e1-e3fc52f7ba53"
        }
      ]
    },
    {
      "id": "acbd9a60-1b6e-4567-a1ed-e61ac0a2957d",
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
          "id": "8e645d22-95ee-4d48-9bd9-acacdac33f46"
        }
      ]
    },
    {
      "id": "0ac68675-cae2-4dae-a828-b02b4ec94cef",
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
          "id": "73a8e99b-2756-4613-8432-260b4279495c"
        }
      ]
    }
  ]
}