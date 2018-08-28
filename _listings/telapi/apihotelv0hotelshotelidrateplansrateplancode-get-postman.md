{
  "info": {
    "name": "hetras Hotel API Version 0 Get all the details for a specific rateplan in the hotel.",
    "_postman_id": "6453d431-c693-4179-9402-2d71ac05a0d4",
    "description": "Read the details about a specific rateplan for the defined hotel.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Folder",
      "item": [
        {
          "id": "04b1ce7f-4a36-4c70-b8f0-cc4de7d60c9b",
          "name": "Hotels_GetHotels",
          "request": {
            "url": "http://api.hetras-certification.net/api/hotel/v0/hotels",
            "method": "GET",
            "header": [
              {
                "key": "App-Id",
                "value": "{}",
                "description": "Application identifier",
                "disabled": false
              },
              {
                "key": "App-Key",
                "value": "{}",
                "description": "Application key",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of all the hotels of a chain your application has access to.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "00e90d29-b7e0-4327-8fc3-73c226dfc466"
            }
          ]
        }
      ]
    },
    {
      "name": "Details",
      "item": [
        {
          "id": "4dd5b27c-ac42-4290-a68b-1e33794e91fe",
          "name": "Hotels_GetHotel",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.hetras-certification.net",
              "path": [
                "api/hotel/v0/hotels/:hotelId"
              ],
              "variable": [
                {
                  "id": "hotelId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "App-Id",
                "value": "{}",
                "description": "Application identifier",
                "disabled": false
              },
              {
                "key": "App-Key",
                "value": "{}",
                "description": "Application key",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get the details of the hotel with the speccified hotel id.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fd3efc4c-a51a-465a-aee7-06aac9794585"
            }
          ]
        }
      ]
    },
    {
      "name": "Codesthe",
      "item": [
        {
          "id": "57ba72f1-6e34-4fe9-90fb-736612cb29b4",
          "name": "Codes_GetCodes",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.hetras-certification.net",
              "path": [
                "api/hotel/v0/hotels/:hotelId/codes"
              ],
              "query": [
                {
                  "key": "code",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "type",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "hotelId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "App-Id",
                "value": "{}",
                "description": "Application identifier",
                "disabled": false
              },
              {
                "key": "App-Key",
                "value": "{}",
                "description": "Application key",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "With this call you can find codes for a hotel by type or code. By default and without any filter criteria\r\n            defined it will return you all available codes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5b3b336d-a344-4d23-8e03-df11e0725a2d"
            }
          ]
        }
      ]
    },
    {
      "name": "Detailsa",
      "item": [
        {
          "id": "74b5091e-c719-4daf-8453-e21a1d2652c3",
          "name": "Codes_GetCode",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.hetras-certification.net",
              "path": [
                "api/hotel/v0/hotels/:hotelId/codes/:id"
              ],
              "variable": [
                {
                  "id": "hotelId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "App-Id",
                "value": "{}",
                "description": "Application identifier",
                "disabled": false
              },
              {
                "key": "App-Key",
                "value": "{}",
                "description": "Application key",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Read the details about a specific code available for the defined hotel."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "412ae8a7-077c-4869-9e96-ffe42ce84eec"
            }
          ]
        },
        {
          "id": "979af1c6-9047-498c-a6a9-23171837bfd5",
          "name": "RatePlans_GetRateplan",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.hetras-certification.net",
              "path": [
                "api/hotel/v0/hotels/:hotelId/rateplans/:rateplanCode"
              ],
              "variable": [
                {
                  "id": "hotelId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "rateplanCode",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "App-Id",
                "value": "{}",
                "description": "Application identifier",
                "disabled": false
              },
              {
                "key": "App-Key",
                "value": "{}",
                "description": "Application key",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Read the details about a specific rateplan for the defined hotel."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1a25e819-2db9-44fb-b32f-c3c52cfdc110"
            }
          ]
        }
      ]
    },
    {
      "name": "Rateplansthe",
      "item": [
        {
          "id": "7e2c817a-4996-4ae7-94d5-094ffdc092a4",
          "name": "RatePlans_GetRateplans",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.hetras-certification.net",
              "path": [
                "api/hotel/v0/hotels/:hotelId/rateplans"
              ],
              "query": [
                {
                  "key": "baseRateplan",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "channelCode",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "channelGroup",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "commissionable",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "group",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "includedServices",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "inlinecount",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "marketCodes",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "roomTypes",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "sellingStatus",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "skip",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "top",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "hotelId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "App-Id",
                "value": "{}",
                "description": "Application identifier",
                "disabled": false
              },
              {
                "key": "App-Key",
                "value": "{}",
                "description": "Application key",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "With this call you can find rateplans for a hotel by different filters. By default and without any filter criteria\r\n            defined it will return you all active rateplans."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "76361695-e0ea-49c4-9470-a664c28b9f2e"
            }
          ]
        }
      ]
    },
    {
      "name": "Count",
      "item": [
        {
          "id": "7ecf9ab5-66a1-4fb2-84ad-be2e0a5b0116",
          "name": "RatePlans_GetRateplansCount",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.hetras-certification.net",
              "path": [
                "api/hotel/v0/hotels/:hotelId/rateplans/$count"
              ],
              "query": [
                {
                  "key": "baseRateplan",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "channelCode",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "channelGroup",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "commissionable",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "group",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "includedServices",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "marketCodes",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "roomTypes",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "sellingStatus",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "hotelId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "App-Id",
                "value": "{}",
                "description": "Application identifier",
                "disabled": false
              },
              {
                "key": "App-Key",
                "value": "{}",
                "description": "Application key",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get the count of all rateplans in the hotel matching the given filter criteria.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "202f95ba-5696-4142-88a2-840901e7e3ee"
            }
          ]
        }
      ]
    }
  ]
}