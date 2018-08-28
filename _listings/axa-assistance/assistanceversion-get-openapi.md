---
swagger: "2.0"
x-collection-name: AXA Assistance
x-complete: 0
info:
  title: AXA Assistance Provide basic details about the current deployed version of
    the assistance API
  description: Provide basic details about the current deployed version of the assistance
    API
  version: 1.0.0
host: sandbox.api.axa-assistance.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /assistance/version:
    get:
      summary: Provide basic details about the current deployed version of the assistance
        API
      description: Provide basic details about the current deployed version of the
        assistance API
      operationId: getAssistanceVersion
      x-api-path-slug: assistanceversion-get
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Provide
      - basic
      - detailAssistance
      - about
      - the
      - current
      - deployed
      - version
      - of
      - the
      - assistance
      - API
  /information/version:
    get:
      summary: Provide basic details about the current deployed version of the information
        API
      description: Provide basic details about the current deployed version of the
        information API
      operationId: getInformationVersion
      x-api-path-slug: informationversion-get
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Provide
      - basic
      - detailAssistance
      - about
      - the
      - current
      - deployed
      - version
      - of
      - the
      - information
      - API
  /insurance/version:
    get:
      summary: Provide basic details about the current deployed version of the insurance
        API
      description: Provide basic details about the current deployed version of the
        insurance API
      operationId: getInsuranceVersion
      x-api-path-slug: insuranceversion-get
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Provide
      - basic
      - detailAssistance
      - about
      - the
      - current
      - deployed
      - version
      - of
      - the
      - insurance
      - API
  /network/version:
    get:
      summary: Provide basic details about the current deployed version of the network
        API
      description: Provide basic details about the current deployed version of the
        network API
      operationId: getNetworkVersion
      x-api-path-slug: networkversion-get
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Provide
      - basic
      - detailAssistance
      - about
      - the
      - current
      - deployed
      - version
      - of
      - the
      - network
      - API
  /ondemand/version:
    get:
      summary: Provide basic details about the current deployed version of the on
        demand API
      description: Provide basic details about the current deployed version of the
        on demand API
      operationId: getOndemandVersion
      x-api-path-slug: ondemandversion-get
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Provide
      - basic
      - detailAssistance
      - about
      - the
      - current
      - deployed
      - version
      - of
      - the
      - "on"
      - demand
      - API
  /sales/version:
    get:
      summary: Provide basic details about the current deployed version of the sales
        API
      description: Provide basic details about the current deployed version of the
        sales API
      operationId: getSalesVersion
      x-api-path-slug: salesversion-get
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Provide
      - basic
      - detailAssistance
      - about
      - the
      - current
      - deployed
      - version
      - of
      - the
      - saleAssistance
      - API
  /service/version:
    get:
      summary: Provide basic details about the current deployed version of the service
        API
      description: Provide basic details about the current deployed version of the
        service API
      operationId: getServiceVersion
      x-api-path-slug: serviceversion-get
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Provide
      - basic
      - detailAssistance
      - about
      - the
      - current
      - deployed
      - version
      - of
      - the
      - service
      - API
  /user/version:
    get:
      summary: Provide basic details about the current deployed version of the User
        API
      description: Provide basic details about the current deployed version of the
        User API
      operationId: getUserVersion
      x-api-path-slug: userversion-get
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Provide
      - basic
      - detailAssistance
      - about
      - the
      - current
      - deployed
      - version
      - of
      - the
      - User
      - API
  /assistance/v1/home/cases:
    get:
      summary: Gets details of cases
      description: Gets details of cases
      operationId: getAssistanceV1HomeCases
      x-api-path-slug: assistancev1homecases-get
      parameters:
      - in: query
        name: declaration_id
        description: ID of the declaration which has trigger the cases
      - in: query
        name: lastname
        description: Lastname of the person associated to the case
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - detailAssistance
      - of
      - cases
  /sales/v1/individual/appliance/certificates/{certificate_id}:
    get:
      summary: Get appliance (Extended warranty, purchase insurance ) certificate
        details.
      description: Get appliance (Extended warranty, purchase insurance ) certificate
        details.
      operationId: getSalesV1IndividualApplianceCertificatesCertificate_id
      x-api-path-slug: salesv1individualappliancecertificatescertificate-id-get
      parameters:
      - in: header
        name: accept-language
        description: Accepted language, IANA language codification
      - in: path
        name: certificate_id
        description: Certificate unique identifier
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - appliance
      - (Extended
      - warranty
      - ""
      - purchase
      - insurance
      - )
      - certificate
      - details.
  /sales/v1/individual/car_rental/certificates/{certificate_id}:
    get:
      summary: Gets the car rental certificate details.
      description: Gets the car rental certificate details.
      operationId: getSalesV1IndividualCar_rentalCertificatesCertificate_id
      x-api-path-slug: salesv1individualcar-rentalcertificatescertificate-id-get
      parameters:
      - in: header
        name: accept-language
        description: Accepted language, IANA language codification
      - in: path
        name: certificate_id
        description: Certificate unique identifier
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - car
      - rental
      - certificate
      - details.
  /sales/v1/individual/travel/certificates/{certificate_id}:
    get:
      summary: Gets the travel certificate details.
      description: Gets the travel certificate details.
      operationId: getSalesV1IndividualTravelCertificatesCertificate_id
      x-api-path-slug: salesv1individualtravelcertificatescertificate-id-get
      parameters:
      - in: header
        name: accept-language
        description: Accepted language, IANA language codification
      - in: path
        name: certificate_id
        description: Certificate unique identifier
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - travel
      - certificate
      - details.
  /information/v1/countries/{country_id}:
    get:
      summary: Retrieve a country detail
      description: Retrieve a country detail
      operationId: getInformationV1CountriesCountry_id
      x-api-path-slug: informationv1countriescountry-id-get
      parameters:
      - in: header
        name: accept-language
        description: Language/Country
      - in: path
        name: country_id
        description: country id
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Retrievecountry
      - detail
  /service/v1/medical_consultations/{medical_consultation_id}:
    get:
      summary: Provides detail of a medical consultation
      description: Provides detail of a medical consultation
      operationId: getServiceV1Medical_consultationsMedical_consultation_id
      x-api-path-slug: servicev1medical-consultationsmedical-consultation-id-get
      parameters:
      - in: path
        name: medical_consultation_id
        description: ID of the medical consultation
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - ProvideAssistance
      - detail
      - ofmedical
      - consultation
  /service/v1/medical_consultations/{medical_consultation_id}/prescriptions/{prescription_id}:
    get:
      summary: Provides detail of a prescription
      description: Provides detail of a prescription
      operationId: getServiceV1Medical_consultationsMedical_consultation_idPrescriptionsPrescription_id
      x-api-path-slug: servicev1medical-consultationsmedical-consultation-idprescriptionsprescription-id-get
      parameters:
      - in: path
        name: medical_consultation_id
        description: ID of the medical consultation
      - in: path
        name: prescription_id
        description: ID of the prescription
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - ProvideAssistance
      - detail
      - ofprescription
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