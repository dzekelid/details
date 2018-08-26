{
  "info": {
    "name": "Amazon EC2 Systems Manager API Describe Activations",
    "_postman_id": "4793c798-1259-405b-ab11-d0c582daebc0",
    "description": "Details about the activation, including: the date and time the activation was created,\n   the expiration date, the IAM role assigned to the instances in the activation, and the number of\n   instances activated by this registration.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Activations",
      "item": [
        {
          "id": "5c7518ea-d756-4ab1-8b0c-8ed4975ab954",
          "name": "describeActivations",
          "request": {
            "url": "http://example.com/api/?Action=DescribeActivations?Filters=Filters&MaxResults=MaxResults&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Details about the activation, including: the date and time the activation was created,\n   the expiration date, the IAM role assigned to the instances in the activation, and the number of\n   instances activated by this registration."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "91c5122f-71d6-44ec-aa12-121620acd963"
            }
          ]
        }
      ]
    }
  ]
}