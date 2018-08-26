{
  "info": {
    "name": "Vinli Get Vehicle Details",
    "_postman_id": "c2b7925f-b7fe-4cae-a8cb-5200d6313749",
    "description": "Get vehicle details.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "List",
      "item": [
        {
          "id": "5ea11c53-5d96-42fb-b758-2bffc86a1894",
          "name": "DevicesCf217c2dDf3c41f7B6108bc3e11b4b79VehiclesGet",
          "request": {
            "url": "http://events.vin.li/api/v1/devices/cf217c2d-df3c-41f7-b610-8bc3e11b4b79/vehicles",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "{}",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List a device's vehicles."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b0e83519-5bc4-42fb-9e76-125d942201e0"
            }
          ]
        },
        {
          "id": "02eedd42-40a9-4013-a89a-7fb0dc5d47e7",
          "name": "Vehicles9aa35c64B04643cc9cd84c353a6d0b30TripsGet",
          "request": {
            "url": "http://events.vin.li/api/v1/vehicles/9aa35c64-b046-43cc-9cd8-4c353a6d0b30/trips",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "{}",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List all of a vehicle's trips."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3f4221bc-38bb-4a5c-8fdf-4715b0f46d06"
            }
          ]
        },
        {
          "id": "2556b750-e07f-4f9d-9458-510329be6782",
          "name": "Vehicles9aa35c64B04643cc9cd84c353a6d0b30DistancesGet",
          "request": {
            "url": "http://events.vin.li/api/v1/vehicles/9aa35c64-b046-43cc-9cd8-4c353a6d0b30/distances",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "{}",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get list of  a vehicles distances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "40a79621-9516-4880-895e-d79d7a8c8780"
            }
          ]
        },
        {
          "id": "0f8023a4-e96d-486a-9311-342bb5a2157d",
          "name": "Vehicles9aa35c64B04643cc9cd84c353a6d0b30OdometerTriggersGet",
          "request": {
            "url": "http://events.vin.li/api/v1/vehicles/9aa35c64-b046-43cc-9cd8-4c353a6d0b30/odometer_triggers",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "{}",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List all odometer triggers for a vehicle."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "710eba21-8505-4c25-ac68-b546e1cdcd93"
            }
          ]
        },
        {
          "id": "1461a058-46f2-4d6f-847c-b0f06c606a33",
          "name": "Vehicles428bc62116e7489bA02aEb98526d01efCollisionsGet",
          "request": {
            "url": "http://events.vin.li/api/v1/vehicles/428bc621-16e7-489b-a02a-eb98526d01ef/collisions",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "{}",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of collisions for a vehicle."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5ff8aa01-9dc7-4e8c-9a87-c87fa9fef7e6"
            }
          ]
        },
        {
          "id": "306cdaa5-2a09-4485-b5e0-62ce68ff0e10",
          "name": "Vehicles9aa35c64B04643cc9cd84c353a6d0b30OdometersGet",
          "request": {
            "url": "http://events.vin.li/api/v1/vehicles/9aa35c64-b046-43cc-9cd8-4c353a6d0b30/odometers",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "{}",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List all odometer reports for a vehicle."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b3100859-08ae-4d60-bcab-9997e1653e96"
            }
          ]
        }
      ]
    },
    {
      "name": "Vehicle",
      "item": [
        {
          "id": "5b862378-4cba-4c7a-92be-62647e77667c",
          "name": "VehiclesAa44769b3c0a46629bad25481cf5198fGet",
          "request": {
            "url": "http://events.vin.li/api/v1/vehicles/aa44769b-3c0a-4662-9bad-25481cf5198f",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "{}",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get vehicle details."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c6252f56-f77c-4201-88dd-55f9d40d1ea5"
            }
          ]
        }
      ]
    },
    {
      "name": "Devices",
      "item": [
        {
          "id": "067e34a2-c2e9-45b6-8ce3-0b2a8878f31c",
          "name": "Devices821374c0D6d811e39c1a0800200c9a66VehiclesLatestGet",
          "request": {
            "url": "http://events.vin.li/api/v1/devices/821374c0-d6d8-11e3-9c1a-0800200c9a66/vehicles/_latest",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "{}",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get device's latest vehicle."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "95bac897-354f-4153-9ea8-a7ead8abfb9a"
            }
          ]
        }
      ]
    },
    {
      "name": "Report",
      "item": [
        {
          "id": "f4dc08c7-98c3-4fd8-8635-89461c112dce",
          "name": "Vehicles8480c5b76f3e40b3A78e3555617d44b0ReportCardsGet",
          "request": {
            "url": "http://events.vin.li/api/v1/vehicles/8480c5b7-6f3e-40b3-a78e-3555617d44b0/report_cards",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "{}",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Report cards for a vehicle."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "eb2d7201-c88d-4a34-9130-183b260df6e2"
            }
          ]
        }
      ]
    }
  ]
}