# Hubb API Postman collection
Thie is a simple Postman collection and envionment to do basic auth and API endpoint requests.

* Download the JSON files and import the collection and environment into your Postman APP.
* Enter your client_id, client_secret, scope, and eventId into the environment variables. grant_type is always set to client_credentials per the Hubb API doc.
* Make sure the the Hubb environment is selected with your collection
* Send "Hubb - Get auth token" will use the variables in your environment to create a token and update the access_token variable in your environment
* All other GET requests use the access_token and eventId to access endpoints