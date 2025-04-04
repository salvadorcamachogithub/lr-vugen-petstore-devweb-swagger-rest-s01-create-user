Updated: 04.2025
Script created by Salvador Camacho

This script was created with best practices, so it is more resilient, such as:
* Transaction naming
* No add cookies
* No third party
* One validation per transaction
* Think times at the end of each transaction to better simulate user behavior
* Main URL and users parametrized, Public AOS by default, credentials parametrized

This script uses a Swagger file from https://petstore.swagger.io/ to show how Swagger files can be used with DevWeb
The first transaction creates a new user, the second transaction finds pets by "available" status and extracts the ids from the response

Runtime Settings were set to log only on errors and generate snapshot on errors, think times 75% to 150%

This script has 2 transactions
PetStore-DevWeb-Swagger-REST-S01-01 Create User
PetStore-DevWeb-Swagger-REST-S01-02 Find Pet By Status