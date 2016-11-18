Overview
This web app was developed using the Grails framework, with log-in functions from Spring Security Core. The app would require a postgres database (named fonix in this example) for storing and retrieving user information.

Instructions
* Install Grails (https://grails.org/)
* Setup a Postgres database if using
* Set the Postgres username to corresponding user
* Pull this repo
* In IDE, run Grails compile
* Initiate Grails and run the app
  * >Grails
  * >run-app

Under construction
* Create user
* Signing-in creates an encrypted code associated with the user in the db
* Entering the code to complete two-factor authentication
