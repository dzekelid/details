{
  "info": {
    "name": "LiveChat Get a single goal details",
    "_postman_id": "052d8e71-c180-4192-babc-287c788d7a3d",
    "description": "Returns the goal details for the given GOAL_ID.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Webhook",
      "item": [
        {
          "id": "afa0686f-eca8-4c88-9701-c5e67d41f2d1",
          "name": "Webhooks12345Delete",
          "request": {
            "url": "http://api.livechatinc.com/webhooks/12345",
            "method": "DELETE",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a webhook with the given ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fe28a95d-3887-41c3-8085-db2bd6bf1690"
            }
          ]
        }
      ]
    },
    {
      "name": "Chat",
      "item": [
        {
          "id": "c21430ed-0b35-4c94-8d28-0a4f0952aa63",
          "name": "ReportsChatsRatingsGet",
          "request": {
            "url": "http://api.livechatinc.com/reports/chats/ratings?date_from=%7B%7D&date_to=%7B%7D&group=%7B%7D&group_by=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Shows how many chats have been rated and how they have been rated during a specified period."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "42b77d3b-570f-47e2-b8c0-30244aa1d325"
            }
          ]
        },
        {
          "id": "4617395e-8290-43c7-8a01-5e7da42d2120",
          "name": "ReportsChatsEngagementGet",
          "request": {
            "url": "http://api.livechatinc.com/reports/chats/engagement?agent=%7B%7D&date_from=%7B%7D&date_to=%7B%7D&group_by=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "This report shows you where you get your chats from. They can come from i.e. automatic invitations, manual invitations or the visitors can start the chats by themselves."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "86d7ac85-f583-499e-9bef-ad1f84fadb37"
            }
          ]
        },
        {
          "id": "c67480c4-a7b6-45bb-b170-3d0eee5a9fe2",
          "name": "ReportsChatsRatingsRankingGet",
          "request": {
            "url": "http://api.livechatinc.com/reports/chats/ratings/ranking",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Shows the ratio of good to bad ratings for each operator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "27d036de-aa24-40c5-9e05-0521d78a5cf4"
            }
          ]
        }
      ]
    },
    {
      "name": "List",
      "item": [
        {
          "id": "06f43079-2780-49d5-96ec-7861cdb9c3e2",
          "name": "CannedResponsesABC123Get",
          "request": {
            "url": "http://api.livechatinc.com/canned_responses/ABC123",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns the list of all currently set canned responses."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3ff63be3-9208-4960-92ea-7d1d7328f9a1"
            }
          ]
        },
        {
          "id": "a80c81ba-895a-4494-a972-97235e2e0a77",
          "name": "GreetingsGet",
          "request": {
            "url": "http://api.livechatinc.com/greetings?groups=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns the list of all greetings."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f101fb17-5809-43b1-afde-d5ebf54d51f7"
            }
          ]
        },
        {
          "id": "b1baff4e-107b-4d22-8f8f-3ca679fce506",
          "name": "TagsGet",
          "request": {
            "url": "http://api.livechatinc.com/tags?group=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns tags from all groups."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f7d4b0af-ea0e-410c-91f3-acd661198687"
            }
          ]
        },
        {
          "id": "02f79db2-edfa-4b56-9690-627b8a226f42",
          "name": "TicketsGet",
          "request": {
            "url": "http://api.livechatinc.com/tickets?date_from=%7B%7D&status=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns all tickets."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2d3fd5d0-0924-421c-9b1a-26f29740787e"
            }
          ]
        },
        {
          "id": "d56d716e-d48b-4e1d-ac4b-5f70ffb97cb2",
          "name": "CannedResponsesGet",
          "request": {
            "url": "http://api.livechatinc.com/canned_responses",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns the list of all currently set canned responses."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "09946fb8-3b76-41e9-a339-24627c146c97"
            }
          ]
        },
        {
          "id": "d2b7a963-18c8-40b7-9a65-25de2493b399",
          "name": "GroupsGet",
          "request": {
            "url": "http://api.livechatinc.com/groups",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns all created groups."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d4eaad67-6ce3-4001-a05f-31d9e8f8f163"
            }
          ]
        },
        {
          "id": "64a04712-f1d1-4a5a-b4d5-19300da57642",
          "name": "GoalsGet",
          "request": {
            "url": "http://api.livechatinc.com/goals",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns all currently set goals. The active parameter indicates whether a goal is enabled or not."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "628baac0-37e5-4deb-a72e-c3510eb999bb"
            }
          ]
        },
        {
          "id": "217adaf8-e4eb-43d0-b241-79a49bf91f20",
          "name": "ChatsGet",
          "request": {
            "url": "http://api.livechatinc.com/chats",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns all ended chats."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8b746faa-eae0-4e22-9355-a29c578d42f0"
            }
          ]
        },
        {
          "id": "218045a4-9bf3-4e5c-becd-37f6ef972ec2",
          "name": "AgentsGet",
          "request": {
            "url": "http://api.livechatinc.com/agents",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns all LiveChat agents list"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "96a65d9b-7f67-406e-b768-0d9e156c59c6"
            }
          ]
        }
      ]
    },
    {
      "name": "Canned",
      "item": [
        {
          "id": "0a027022-7118-45e2-99e1-9763207c401a",
          "name": "CannedResponsesABC123Put",
          "request": {
            "url": "http://api.livechatinc.com/canned_responses/ABC123",
            "method": "PUT",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "tags[0]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Updates the specified canned response by setting the values of the parameters passed. Any parameters not provided will be left unchanged."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1bb8853d-cc6e-490e-8aec-d5946d644859"
            }
          ]
        }
      ]
    },
    {
      "name": "Remove",
      "item": [
        {
          "id": "b4548067-1e01-4282-afec-a0305a070521",
          "name": "CannedResponsesABC123Delete",
          "request": {
            "url": "http://api.livechatinc.com/canned_responses/ABC123",
            "method": "DELETE",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Removes a canned response with the given CANNED_RESPONSE_ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8d512adf-893b-4a5b-9bea-d254c50549c2"
            }
          ]
        },
        {
          "id": "340522f8-e11a-4a5b-b561-6a6eda3ac02d",
          "name": "GroupsABC123Delete2",
          "request": {
            "url": "http://api.livechatinc.com/groups/ABC123",
            "method": "DELETE",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Removes a group with the given GROUP_ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7fb46d0e-47f1-468f-806e-5a422f86d67f"
            }
          ]
        },
        {
          "id": "1f2d362c-70e6-4878-a070-b0ca9b3ae9f6",
          "name": "AgentsJohnPublicComDelete",
          "request": {
            "url": "http://api.livechatinc.com/agents/john@public.com",
            "method": "DELETE",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Removes an agent."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c8b63eb5-8a94-4daf-be29-3aa7119e5fbe"
            }
          ]
        },
        {
          "id": "c7135790-039b-4746-b8e1-1dfff9bf9c5d",
          "name": "GreetingsABC123Delete",
          "request": {
            "url": "http://api.livechatinc.com/greetings/ABC123",
            "method": "DELETE",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Removes a greeting."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b87920f7-15bf-475d-a445-c0a2ba1b5a60"
            }
          ]
        }
      ]
    },
    {
      "name": "Group",
      "item": [
        {
          "id": "7786e61c-579c-4cbf-bcc6-89e8147ce156",
          "name": "GroupsABC123Put",
          "request": {
            "url": "http://api.livechatinc.com/groups/ABC123",
            "method": "PUT",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "agents[0]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "agents[1]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "name",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Updates the specified group by setting the values of the parameters passed. Any parameters not provided will be left unchanged."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b39095a3-99cb-43a9-bdfe-7baa8c453333"
            }
          ]
        }
      ]
    },
    {
      "name": "New",
      "item": [
        {
          "id": "d5c3cdb4-a2d6-45a2-b180-d0984fed30c1",
          "name": "GreetingsPost",
          "request": {
            "url": "http://api.livechatinc.com/greetings",
            "method": "POST",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "name",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "rules[0][operator]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "rules[0][type]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "rules[0][value]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "rules[1][operator]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "rules[1][type]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "rules[1][value]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Use this function to create a new greeting."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f04be871-2cf0-4758-9f70-3b9d9efc809a"
            }
          ]
        },
        {
          "id": "1931ecc3-cca6-48bc-be47-fb1cd00f5fa2",
          "name": "WebhooksPost",
          "request": {
            "url": "http://api.livechatinc.com/webhooks",
            "method": "POST",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "data_types",
                  "value": "[{}]",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "event_type",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "url",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Creates a new webhook."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "98933e22-52ae-41d7-9d38-7fb5bff8f618"
            }
          ]
        },
        {
          "id": "ca788322-d2dc-4800-8e3e-64f7952b1ef9",
          "name": "CannedResponsesPost",
          "request": {
            "url": "http://api.livechatinc.com/canned_responses",
            "method": "POST",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "tags[0]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "tags[1]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "text",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Creates a new canned response."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7fd74d0b-83ac-41e9-9ddb-9ead2609463a"
            }
          ]
        },
        {
          "id": "b3289d12-4f74-4051-ad8f-23eb8bd25c7b",
          "name": "GroupsPost",
          "request": {
            "url": "http://api.livechatinc.com/groups",
            "method": "POST",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "agents[0]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "agents[1]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "name",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Creates a new group in your license."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c985385f-26c9-4cdf-b623-dbd898c2c91f"
            }
          ]
        },
        {
          "id": "ee24f7ed-3c54-4746-85e9-34d35e8d6c95",
          "name": "GoalsPost",
          "request": {
            "url": "http://api.livechatinc.com/goals",
            "method": "POST",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "match_type",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "name",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "type",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "url",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Creates a new goal."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9c2e18db-07c7-49da-bd2f-93a5ac1bbd40"
            }
          ]
        },
        {
          "id": "00d40d55-1ee0-4104-b01c-1de328fe34b2",
          "name": "AgentsPost",
          "request": {
            "url": "http://api.livechatinc.com/agents",
            "method": "POST",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "login",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "name",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Creates a new agent in your license."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cfc408f1-8a0e-4d89-ad1e-57bfa3b67e50"
            }
          ]
        }
      ]
    },
    {
      "name": "Display",
      "item": [
        {
          "id": "d53b2435-fc6d-4560-b33c-93ea0b91e9a1",
          "name": "WebhooksGet",
          "request": {
            "url": "http://api.livechatinc.com/webhooks",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of webhooks that have been created in a LiveChat account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8597567d-89cb-4338-9075-b02dc04955c9"
            }
          ]
        }
      ]
    },
    {
      "name": "Greetings",
      "item": [
        {
          "id": "9830f25c-972e-445d-83ca-2abf4da8b329",
          "name": "ReportsChatsGreetingsGet",
          "request": {
            "url": "http://api.livechatinc.com/reports/chats/greetings?date_from=%7B%7D&date_to=%7B%7D&group_by=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns the “greetings to chats to goals” conversion rates report.\n\ndisplayed is the number of displayed greetings. accepted tells you how many chats resulted from these greetings. goals tells you how many goals resulted from these greetings."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b697eb43-2dec-45e7-a5a8-dd8ff34c1a5b"
            }
          ]
        }
      ]
    },
    {
      "name": "Tag",
      "item": [
        {
          "id": "27eb8fcb-7fbc-4a41-a16d-3225bbffac27",
          "name": "TagsPost",
          "request": {
            "url": "http://api.livechatinc.com/tags",
            "method": "POST",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "author",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "group",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "tag",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Adds a new tag. Note that only the owner and the admins are authorized to use this."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9918ed38-d0fa-4e1f-a3b4-42a4f8608070"
            }
          ]
        }
      ]
    },
    {
      "name": "Single",
      "item": [
        {
          "id": "ddfe4795-eebd-4e1f-a056-6bcebdfcdf07",
          "name": "AgentsJohnPublicComGet",
          "request": {
            "url": "http://api.livechatinc.com/agents/john@public.com",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns complete details of the agent for the given LOGIN."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "84358b1e-8da9-43de-b4b7-22bfe4b40936"
            }
          ]
        },
        {
          "id": "6de7b4d3-1c8c-4e6e-8996-d7edb2472ceb",
          "name": "AgentsJohnPublicComPut",
          "request": {
            "url": "http://api.livechatinc.com/agents/john@public.com",
            "method": "PUT",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "job_title",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Returns complete details of the agent for the given LOGIN."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0d7ed9c7-b4a9-4512-a9bf-5b4f534b5fb9"
            }
          ]
        },
        {
          "id": "0704076c-ebba-443b-9db7-a11d906b6713",
          "name": "ChatsABC123Get",
          "request": {
            "url": "http://api.livechatinc.com/chats/ABC123",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns a single chat item for the given CHAT_ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4bdf3e63-a579-4eb8-be63-c98978235294"
            }
          ]
        },
        {
          "id": "b0141805-648e-438c-854a-263a8f54c78a",
          "name": "GreetingsABC123Get",
          "request": {
            "url": "http://api.livechatinc.com/greetings/ABC123",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns the specified greeting."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3d0b2dc5-ba72-42c4-be43-1923f8a114ef"
            }
          ]
        },
        {
          "id": "4ca1b8a1-a455-48f2-91a9-1bb5ca34f6ae",
          "name": "GroupsByGroupIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.livechatinc.com",
              "path": [
                "groups/:group_id"
              ],
              "variable": [
                {
                  "id": "group_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns group details for the given GROUP_ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1b16f181-94f6-4ef7-a3c0-26a0c27d1ae4"
            }
          ]
        },
        {
          "id": "0dd85698-e007-4fc2-87ae-6efbe59c47e5",
          "name": "GoalsABC123Get",
          "request": {
            "url": "http://api.livechatinc.com/goals/ABC123",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns the goal details for the given GOAL_ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7c9c43d9-3675-42ca-b463-2cdabd5f7986"
            }
          ]
        }
      ]
    },
    {
      "name": "Ticket",
      "item": [
        {
          "id": "839c9f9d-b2f3-4ab0-ba7c-3357061b2b21",
          "name": "TicketsPost",
          "request": {
            "url": "http://api.livechatinc.com/tickets",
            "method": "POST",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "message",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "requester[mail]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "requester[name]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "subject",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Creates a new ticket."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "37ffd63f-3fd9-4f35-91b2-7486dc307832"
            }
          ]
        },
        {
          "id": "0e688490-8b82-4635-9446-6f55b140f07a",
          "name": "ReportsTicketsTicketSourcesGet",
          "request": {
            "url": "http://api.livechatinc.com/reports/tickets/ticket_sources?date_from=%7B%7D&date_to=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Shows the distribution of the tickets between various channels."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0e2f0464-942f-422f-b959-6e92997a1630"
            }
          ]
        }
      ]
    },
    {
      "name": "Solved",
      "item": [
        {
          "id": "37cbac5d-a483-4c67-9b4f-a1bfe9a115ec",
          "name": "ReportsTicketsSolvedTicketsGet",
          "request": {
            "url": "http://api.livechatinc.com/reports/tickets/solved_tickets?date_from=%7B%7D&date_to=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Shows the number of the tickets solved during the specified period."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cc65f98e-e6a9-4a85-9b34-9e3955ed7e34"
            }
          ]
        }
      ]
    },
    {
      "name": "Chats",
      "item": [
        {
          "id": "721e79b1-fe6f-4ed7-9605-17f219a0e75d",
          "name": "ReportsChatsFirstResponseTimeGet",
          "request": {
            "url": "http://api.livechatinc.com/reports/chats/first_response_time",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "The average amount of time it takes the agents to respond to a new chat over a specified period of time."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a2e6d87a-61c4-4fa0-b3f3-d79a7a9a2f11"
            }
          ]
        }
      ]
    },
    {
      "name": "Total",
      "item": [
        {
          "id": "67da3495-aeac-4c46-981f-3e19c4a6388a",
          "name": "ReportsChatsTotalChatsGet",
          "request": {
            "url": "http://api.livechatinc.com/reports/chats/total_chats?agent=%7B%7D&date_from=%7B%7D&date_to=%7B%7D&group_by=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "X-API-Version",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Shows how many chats occurred during the specified period."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8da1fa8d-f1b7-41b3-b29f-aaeaf7a11be2"
            }
          ]
        }
      ]
    }
  ]
}