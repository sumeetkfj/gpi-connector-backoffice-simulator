# gpi-connector-backoffice-simulator
This is a postman collection for integrating with Tracker APIs and Pre-Validation API demonstrating the principles of TLS, LAU and JSON schema validation.

## Installation
Download the repo and import postman_collection.json to Postman. Postman is an API client tool that helps test APIs. [Get Postman!](https://www.getpostman.com/)

## Configuration
Configure the postman collection to your institution. [Check how to change collection variables in Postman](https://learning.getpostman.com/docs/postman/environments_and_globals/variables/#defining-collection-variables).

LAU variables:
* applicationId
* version
* laukey

Other variables:
* dn (needed for gpi Pre-Validation API)
* bic (needed for gpi Pre-Validation API)
* apikey (request your API key by creating an APP on [SWIFT Developer Portal](https://developer.swift.com))

URLs are preloaded with the SWIFT Sandbox API URLs starting with `https://sandbox.swift.com`, change the URL to point to your development, test or local URLs where the service is running.

If you see a bug, create a PR! Viola, happy API testing! 
