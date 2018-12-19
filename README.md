# usaddress_cleaning
Scripts to clean file of addresses

This repo contains a python notebook for cleaning US addresses before submitting them to a geocoder. This is not a trivial task and this is not a perfect script. But for me it has handled some pretty nasty data and made it so that these poorly formatted addresses do not cause the geocoder to crash.


Once your address data are cleaned you can submit to a geocoding service (if the data are not confidential) or geocode offline on your local/secure computer.

For remote geocoding, the Google and ESRI online APIs are excellent but are not free if you have larger numbers of addresses (check the API docs for limtis and terms of use). If you work for an educational institution you may have an ESRI site license which would make use of the ESRI World Geocoding Service free.

The US Census geocoder is free and recommended if you have < 10,000 addresses and you don't want to write a script. It has a file upload option.

If you are working with secure data, a local install of ESRI ArcGIS / ArcPro with the latest version of the Business Analyst geocoding data can all be run locally (if you have the appropriate license keys).

Other options abound - just search online.
