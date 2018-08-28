{
  "info": {
    "name": "U.S. EPA Enforcement and Compliance History Online (ECHO) - Effluent Charting and Reporting Detailed Effluent Chart Service",
    "_postman_id": "793c2bac-d1a3-41b2-b3f7-1f110a22b1d9",
    "description": "Discharge Monitoring Report (DMR) data supporting each effluent chart for one NPDES permit. Includes Discharge Monitoring Reports and NPDES Violations.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "c776b573-9a02-463e-ac71-b80cf0a4bcd8",
      "name": "downloads-tabular-discharge-monitoring-report-dmr-and-compliance-data-for-one-npdes-permit-as-a-csv-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/eff_rest_services.download_effluent_chart?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Downloads tabular Discharge Monitoring Report (DMR) and compliance data for one NPDES permit as a CSV."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "8e276422-7e60-4030-b172-bc58c2f947a0"
        }
      ]
    },
    {
      "id": "3b014c91-100e-4918-aa2b-2164b36b9857",
      "name": "discharge-monitoring-report-dmr-data-supporting-each-effluent-chart-for-one-npdes-permit--includes-d",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/eff_rest_services.get_effluent_chart?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Discharge Monitoring Report (DMR) data supporting each effluent chart for one NPDES permit. Includes Discharge Monitoring Reports and NPDES Violations."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "e56bf184-a9bc-46c3-9aad-a7defb70f1b7"
        }
      ]
    }
  ]
}