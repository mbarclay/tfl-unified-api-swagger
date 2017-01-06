# Tfl Unified API Swagger Specification

TfL publish a [Swagger Specification](https://api.tfl.gov.uk/  "Official TfL API Swagger Specification") of their API.

This project builds upon TfL's published specification, all Swagger errors and warnings have been attended to (fixed). This has resulted in a few of the published services being removed (removal reason listed below). The following (known) endpoints that are in the TfL specification are __not__ present in this specification:

* __/Notification__ All endpoints, 4 in total. Not needed for my purposes, original specification also has a partially missing response schema.

* __/TravelTimes__ All endpoints, 2 in total. Not needed for my purposes, original specification missing response schema.

* __/StopPoint/Sms/{id}__ Not needed for my purposes, original specification missing response schema.

* __/Place/{type}/At/{lat}/{lon}__ Not needed for my purposes, original specification missing response schema.

All other endpoints should function correctly.

The __app_id__ and __api_key__ parameter has also been added to all endpoint specifications. An [API Key](https://api-portal.tfl.gov.uk/docs "Register for Tfl API") can be obtained from TfL.
