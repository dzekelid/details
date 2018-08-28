{
  "info": {
    "name": "Easycron API Get detail of a cron job.",
    "_postman_id": "db2b97cb-b672-4dc8-b097-994519f2db8e",
    "description": "Get detail of a cron job.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Cron",
      "item": [
        {
          "id": "19798930-99f7-41c1-bcde-16de0d6b4fbe",
          "name": "addCronJob",
          "request": {
            "url": "http://www.easycron.com/rest/add?cookies=%7B%7D&cron_expression=%7B%7D&cron_job_name=%7B%7D&email_me=%7B%7D&log_output_length=%7B%7D&posts=%7B%7D&testfirst=%7B%7D&token=%7B%7D&url=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Add a cron job."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e73bdd6c-8287-4496-8667-377b894c39b4"
            }
          ]
        },
        {
          "id": "466e90f6-b71d-4486-b159-01eccf01edbc",
          "name": "deleteCronJob",
          "request": {
            "url": "http://www.easycron.com/rest/delete?id=%7B%7D&token=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Delete a cron job."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3cba2b15-9f59-46a4-96f7-d0c726888c3a"
            }
          ]
        }
      ]
    },
    {
      "name": "Detail",
      "item": [
        {
          "id": "62a415a2-8cf3-4669-86a7-56b197d28112",
          "name": "getDetailCronJob",
          "request": {
            "url": "http://www.easycron.com/rest/detail?id=%7B%7D&token=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get detail of a cron job."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2e6f258d-bccb-498a-b2a0-a17c480c1d3c"
            }
          ]
        }
      ]
    }
  ]
}