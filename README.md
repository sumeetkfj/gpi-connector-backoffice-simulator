# gpi-connector-backoffice-simulator
This is a postman collection for integrating with Tracker APIs and Pre-Validation API demonstrating the principles of TLS, LAU and JSON schema validation.

## Installation
Download the repo and import postman_collection.json to Postman. Postman is an API client tool that helps test APIs. [Get Postman!](https://www.getpostman.com/).

## Configuration
Configure the postman collection to your institution:
LAU:
* applicationId
* version
* laukey

Others:
* dn (needed for gpi Pre-Validation API)
* bic (needed for gpi Pre-Validation API)
* apikey (request on [SWIFT Developer Portal](https://developer.swift.com))
