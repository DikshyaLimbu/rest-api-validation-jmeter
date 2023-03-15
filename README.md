# rest-api-validation-jmeter
An API Validation script for [dummyapi.io](https://dummyapi.io/) website using Jmeter.

You need to generate an app-id to use in your API request header to send the API requests by loggin in to the site.

The test script performs the following 2 scenarios. The data structure for all responses can be found [here](https://dummyapi.io/docs/models).

# A. Get List of Users

-> Verify if the API is throwing 200 OK as status code.

-> Verify if the firstName, lastName, id, title, picture object keys are being populated or not.

-> Get value of id for user "Carolina" and use it to send API requests in B.

# B. Get a particular user by id
-> Verify response code is 200 OK.

-> Verify if the firstName matches as expected("Carolina").

[Screenshot](https://drive.google.com/file/d/1QB4VgbDTtznh5WN1RkZuR7xYPdaBn5cq/view?usp=share_link?)