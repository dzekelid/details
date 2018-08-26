{
  "info": {
    "name": "Constant Contact Get Guest Details",
    "_postman_id": "9f2a7246-e6f3-4be1-93c1-06dabc5657e3",
    "description": "Get Guest Details",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "List",
      "item": [
        {
          "id": "5a2abf59-7e57-424f-a31e-a5588aba1c04",
          "name": "list-activities",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.constantcontact.com",
              "path": [
                "ws",
                "customers",
                ":username/activities"
              ],
              "variable": [
                {
                  "id": "username",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Activities"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d6623dea-9f52-4148-9fde-da70ae3f1f93"
            }
          ]
        },
        {
          "id": "93263790-5525-44ad-a7f3-4f49541e6653",
          "name": "list-campaigns",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.constantcontact.com",
              "path": [
                "ws",
                "customers",
                ":username/campaigns"
              ],
              "query": [
                {
                  "key": "refresh",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "username",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Campaigns"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e4d6e648-9c0e-4b74-b003-671f00e1d2e6"
            }
          ]
        },
        {
          "id": "5d48f91c-e48e-4c1b-aca1-aacc5540a6ca",
          "name": "list-contacts",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.constantcontact.com",
              "path": [
                "ws",
                "customers",
                ":username/contacts"
              ],
              "query": [
                {
                  "key": "listid",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "updatedsince",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "username",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Contacts"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4c804197-3c0a-4a41-b2f9-81a7db134ed4"
            }
          ]
        },
        {
          "id": "b0cc6d86-e86a-46b2-8093-b7404e6bd16d",
          "name": "list-events",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.constantcontact.com",
              "path": [
                "ws",
                "customers",
                ":username/events"
              ],
              "variable": [
                {
                  "id": "username",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Events"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "247093b5-dadf-45cf-ada8-ee638658eb91"
            }
          ]
        },
        {
          "id": "05602e6f-cfcf-44e7-9a93-445f26075048",
          "name": "list-registrants",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.constantcontact.com",
              "path": [
                "ws",
                "customers",
                ":username/events/:event-id/registrants"
              ],
              "variable": [
                {
                  "id": "event-id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "username",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Registrants"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f9c2dd3e-91fa-4f62-bd51-7a715c0f4eb0"
            }
          ]
        },
        {
          "id": "345814b3-d0a6-4f82-8e15-e269366e82ae",
          "name": "get-list-of-guests",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.constantcontact.com",
              "path": [
                "ws",
                "customers",
                ":username/events/:event-id/registrants/:registrant-id/guests"
              ],
              "variable": [
                {
                  "id": "event-id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "registrant-id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "username",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get List of Guests"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "31e31daf-41e7-4eb0-9f20-ef0a16901f60"
            }
          ]
        }
      ]
    },
    {
      "name": "Activity",
      "item": [
        {
          "id": "bf4b3d83-3308-4aee-85ed-bad1383aea19",
          "name": "add-activity",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.constantcontact.com",
              "path": [
                "ws",
                "customers",
                ":username/activities"
              ],
              "variable": [
                {
                  "id": "username",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Add Activity"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c7a6c2c1-ec3e-47ea-b2b3-a713fd44dbeb"
            }
          ]
        },
        {
          "id": "bd95639a-b52e-40fd-8ecb-e5edfd85aa72",
          "name": "get-activity",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.constantcontact.com",
              "path": [
                "ws",
                "customers",
                ":username/activities/:activity-id"
              ],
              "variable": [
                {
                  "id": "activity-id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "username",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Activity"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d8be2d34-4bf1-4795-9662-a02468e9ba01"
            }
          ]
        }
      ]
    },
    {
      "name": "Campaign",
      "item": [
        {
          "id": "a0c6d5c5-6a8a-47ca-a84b-5cfb7edde456",
          "name": "add-campaign",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.constantcontact.com",
              "path": [
                "ws",
                "customers",
                ":username/campaigns"
              ],
              "query": [
                {
                  "key": "Content-Type",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "username",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Add Campaign"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d0ea1f67-9933-4d38-aaab-8a4604749498"
            }
          ]
        },
        {
          "id": "66499826-c4c0-41d9-9e98-ee32abdf497e",
          "name": "get-campaign",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.constantcontact.com",
              "path": [
                "ws",
                "customers",
                ":username/campaigns/:campaign-id"
              ],
              "variable": [
                {
                  "id": "campaign-id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "username",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Campaign"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cbf0eb9b-6d11-441d-8b34-08a579490e1a"
            }
          ]
        },
        {
          "id": "3a7e968a-413d-4e11-b973-f03b5583685f",
          "name": "update-campaign",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.constantcontact.com",
              "path": [
                "ws",
                "customers",
                ":username/campaigns/:campaign-id"
              ],
              "query": [
                {
                  "key": "Content-Type",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "campaign-id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "username",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Update Campaign"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b7ebd59f-de3b-4889-9bd2-7135da2db25e"
            }
          ]
        },
        {
          "id": "4c7bc00a-f069-45ab-bb57-9c6e75df4691",
          "name": "delete-campaign",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.constantcontact.com",
              "path": [
                "ws",
                "customers",
                ":username/campaigns/:campaign-id"
              ],
              "variable": [
                {
                  "id": "campaign-id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "username",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete Campaign"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f4494407-4746-4526-835f-4f5f619bd423"
            }
          ]
        },
        {
          "id": "421076c7-0e5e-4977-beaa-83b69cc834e8",
          "name": "get-campaign-events",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.constantcontact.com",
              "path": [
                "ws",
                "customers",
                ":username/campaigns/:campaign-id/events/"
              ],
              "variable": [
                {
                  "id": "campaign-id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "username",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Campaign Events"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7f621601-6ddc-421f-8af9-a30b3407866a"
            }
          ]
        }
      ]
    },
    {
      "name": "Contact",
      "item": [
        {
          "id": "7ea1c2bd-0afe-43d8-b084-6ee55f3ced87",
          "name": "add-contact",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.constantcontact.com",
              "path": [
                "ws",
                "customers",
                ":username/contacts"
              ],
              "query": [
                {
                  "key": "Content-Type",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "username",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Add Contact"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8e92b632-4698-498c-b9ab-175499769eef"
            }
          ]
        },
        {
          "id": "890996cf-3987-45c5-913b-880c69ed1411",
          "name": "get-contact",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.constantcontact.com",
              "path": [
                "ws",
                "customers",
                ":username/contacts/:contact-id"
              ],
              "variable": [
                {
                  "id": "contact-id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "username",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Contact"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "94bc1269-8b8a-4ed4-b5e6-3b3bc6861e40"
            }
          ]
        },
        {
          "id": "4dc92abf-41b4-4d29-9503-c4333a8f1c03",
          "name": "update-contact",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.constantcontact.com",
              "path": [
                "ws",
                "customers",
                ":username/contacts/:contact-id"
              ],
              "query": [
                {
                  "key": "Content-Type",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "contact-id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "username",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Update Contact"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7236779d-ab6c-4000-a8a5-2592e3218b8e"
            }
          ]
        }
      ]
    },
    {
      "name": "Opting-out",
      "item": [
        {
          "id": "7eec5c71-0cb8-4ae3-b139-a55ee679bb44",
          "name": "optingout-contact",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.constantcontact.com",
              "path": [
                "ws",
                "customers",
                ":username/contacts/:contact-id"
              ],
              "variable": [
                {
                  "id": "contact-id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "username",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Opting-out Contact"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b9e103de-1e70-4901-92c0-821d280d5c9a"
            }
          ]
        }
      ]
    },
    {
      "name": "Per-Contact",
      "item": [
        {
          "id": "e3350caf-8dc1-4082-8182-533783339481",
          "name": "get-percontact-campaign-events",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.constantcontact.com",
              "path": [
                "ws",
                "customers",
                ":username/contacts/:contact-id/events/"
              ],
              "variable": [
                {
                  "id": "contact-id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "username",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Per-Contact Campaign Events"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5e8e789d-d8a8-4a50-8807-6c956cf12d12"
            }
          ]
        }
      ]
    },
    {
      "name": "Event",
      "item": [
        {
          "id": "b4f6ed8b-d604-43ce-9734-e46b55018dbf",
          "name": "add-event",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.constantcontact.com",
              "path": [
                "ws",
                "customers",
                ":username/events"
              ],
              "query": [
                {
                  "key": "Content-Type",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "username",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Add Event"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cadbdcc0-9a03-472b-9d49-0d9ec4cd8359"
            }
          ]
        },
        {
          "id": "43b5d7d4-8719-49c7-8e0c-7fc479fdbd73",
          "name": "get-event",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.constantcontact.com",
              "path": [
                "ws",
                "customers",
                ":username/events/:event-id"
              ],
              "variable": [
                {
                  "id": "event-id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "username",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Event"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "459dc34e-7880-4915-a7f6-963650a2b9bf"
            }
          ]
        }
      ]
    },
    {
      "name": "Registrant",
      "item": [
        {
          "id": "9b861cd0-29f5-47d2-9d18-65af9fcb8ed1",
          "name": "get-registrant",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.constantcontact.com",
              "path": [
                "ws",
                "customers",
                ":username/events/:event-id/registrants/:registrant-id"
              ],
              "variable": [
                {
                  "id": "event-id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "registrant-id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "username",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Registrant"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c540101a-1303-4766-9a23-8634e8ca458f"
            }
          ]
        }
      ]
    },
    {
      "name": "Attendance",
      "item": [
        {
          "id": "d26a8be1-2b52-4dc8-833e-344c588f0225",
          "name": "get-attendance-status",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.constantcontact.com",
              "path": [
                "ws",
                "customers",
                ":username/events/:event-id/registrants/:registrant-id/attendancestatus"
              ],
              "variable": [
                {
                  "id": "event-id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "registrant-id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "username",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Attendance Status"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ef54656f-e9fe-44ea-8845-290bced09d12"
            }
          ]
        },
        {
          "id": "249f4444-5cb0-4669-9441-1e89d862e8a2",
          "name": "update-attendance-status",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.constantcontact.com",
              "path": [
                "ws",
                "customers",
                ":username/events/:event-id/registrants/:registrant-id/attendancestatus"
              ],
              "query": [
                {
                  "key": "Content-Type",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "event-id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "registrant-id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "username",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Update Attendance Status"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4d6a6e11-7911-4384-b490-6d9d4cc19762"
            }
          ]
        }
      ]
    },
    {
      "name": "Guest",
      "item": [
        {
          "id": "026ca16b-3150-4aa3-99e4-fadeb2597dec",
          "name": "get-guest-details",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.constantcontact.com",
              "path": [
                "ws",
                "customers",
                ":username/events/:event-id/registrants/:registrant-id/guests/:guest-id"
              ],
              "variable": [
                {
                  "id": "event-id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "guest-id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "registrant-id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "username",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Guest Details"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5949b3c1-2bf1-4e87-ac43-8562a3d29f44"
            }
          ]
        }
      ]
    }
  ]
}