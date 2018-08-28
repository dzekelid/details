---
swagger: "2.0"
x-collection-name: PayPal
x-complete: 0
info:
  title: Paypal Payment Details
  description: Use the PaymentDetails API operation to obtain information about a
    payment. You can identify the payment by your tracking ID, the PayPal transaction
    ID in an IPN message, or the pay key associated with the payment.
  version: 1.0.0
host: svcs.sandbox.paypal.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /AdaptivePayments/PaymentDetails:
    post:
      summary: Payment Details
      description: Use the PaymentDetails API operation to obtain information about
        a payment. You can identify the payment by your tracking ID, the PayPal transaction
        ID in an IPN message, or the pay key associated with the payment.
      operationId: AdaptivePayments.PaymentDetails.post
      x-api-path-slug: adaptivepaymentspaymentdetails-post
      responses:
        200:
          description: OK
      tags:
      - Payments
  /AdaptivePayments/PreapprovalDetails:
    post:
      summary: Preapproval Details
      description: Use the PreapprovalDetails API operation to obtain information
        about an agreement between you and a sender for making payments on the sender???s
        behalf.
      operationId: AdaptivePayments.PreapprovalDetails.post
      x-api-path-slug: adaptivepaymentspreapprovaldetails-post
      responses:
        200:
          description: OK
      tags:
      - Payments
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---