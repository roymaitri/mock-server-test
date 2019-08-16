Pre-requisites - Postman / node.js and Newman

## Steps to execute using Postman
* Import the collection (BDD.postman_collection.json) in the Postman
* Import the environment (postman.postman_environment.json) in the Postman
* Run it as a collection Runner

## Steps to execute using command line
* Run the following command while in the same folder as the collection and environment files:
`newman run BDD.postman_collection.json -e postman.postman_environment.json`
