---
swagger: "2.0"
x-collection-name: PayPal
x-complete: 1
info:
  title: PayPal (Sandbox)
  description: bring-payments-to-apps-mobile-and-social-with-adaptive-payments-bsandbox-api-b
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
---