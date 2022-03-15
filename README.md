# Google Maps REST Testing
We use POST and DELETE Rest methods to add and delete a google maps using rest services

## Why is there an "1. Google maps REST xml" and "2. Google maps REST http"?
The "1. Google maps REST xml" was created by using XML code and rest services. We added the body of the POST in xml format.
The "2. Google maps REST http" was created by using JSON code and rest services. We added the body of the POST in JSON format.

### What does the Add service do?
We used POST with a media type that consisted of the co-oridnates, address, website, etc. to get corresponding status, place_id, scope, reference, and id. 

### What does the Delete service do?
We used the place_id in our DELETE method's media type and deleted the particular place.

## What tools are used to test Google Maps Rest Services?
1. SoapUI REST HTTP
2. SoapUI REST XML
3. Postman
