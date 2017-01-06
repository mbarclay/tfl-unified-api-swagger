# Tfl Unified API Swagger Specification
This project builds upon TfL's [published specification](https://api.tfl.gov.uk/  "Official TfL API Swagger Specification"), all Swagger errors and warnings have been attended to (fixed). This has resulted in a few of the published services being removed (removal reason listed below). The following known endpoints that are in the TfL specification are __not__ present in this specification:

* __/Notification__ All endpoints, 4 in total. Not needed for my purposes, original specification also has a partially missing response schema.

* __/TravelTimes__ All endpoints, 2 in total. Not needed for my purposes, original specification missing response schema.

* __/StopPoint/Sms/{id}__ Not needed for my purposes, original specification missing response schema.

* __/Place/{type}/At/{lat}/{lon}__ Not needed for my purposes, original specification missing response schema.

## Further Details
* All endpoints should function correctly.
* Some missing schema's have been added.
* Any unused schemas have been removed.

The __app_id__ and __api_key__ parameter has been added to all endpoint specifications. An [API Key](https://api-portal.tfl.gov.uk/docs "Register for Tfl API") can be obtained from TfL.

You can view the validated swagger generation that this specification produces [here](https://generator.swagger.io/?url=https://raw.githubusercontent.com/mbarclay/tfl-unified-api-swagger/master/tfl-unified-api.swagger.yaml "Malcolm Barclay's validated Tfl Unified API Swagger Specification").
