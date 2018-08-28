{
  "info": {
    "name": "U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility Report (DFR) Detailed Facility Report CWA Effluent Compliance Service",
    "_postman_id": "584f198c-495f-4c88-bea9-83403ecbfc0e",
    "description": "This procedure obtains data for the CWA Effluent Compliance section on the DFR.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "e931400c-5c39-4d4b-97ff-06c5b6af106c",
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
          "id": "70616b6e-2d3e-4b32-932e-e035b74c89c2"
        }
      ]
    },
    {
      "id": "9b018c26-b458-4453-b34d-ece79012b272",
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
          "id": "fb359582-e3ba-463c-983f-2e3fbb8251cf"
        }
      ]
    },
    {
      "id": "54d60b69-0bf0-4076-ba66-f33b544a1749",
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
          "id": "43848ace-c724-40fd-a178-2493732230e5"
        }
      ]
    },
    {
      "id": "e2008268-8c04-49d2-9a57-1af72ff51d7c",
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
          "id": "4e5f2cf5-8b83-4c6f-8817-b0b1df26effe"
        }
      ]
    },
    {
      "id": "5019cdcd-d998-4d14-988c-f5783bbf7633",
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
          "id": "65a553ca-1e86-4a1c-a067-d40151d8402e"
        }
      ]
    },
    {
      "id": "0c283802-2b02-4bfc-b9d6-79b8b646a691",
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
          "id": "918d0327-c092-4338-a591-d283760fdb73"
        }
      ]
    },
    {
      "id": "136ffa92-bd96-4d90-9255-d5bdd72d1a23",
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
          "id": "7870f7ed-5b61-4c4e-8fa5-878488eb4f25"
        }
      ]
    },
    {
      "id": "bceea0f2-7d39-4b62-95c0-a43536bf110c",
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
          "id": "4ea32aca-d3d1-4293-9181-fa1a3ca3a8c8"
        }
      ]
    }
  ]
}