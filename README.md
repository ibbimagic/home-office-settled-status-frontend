# Home Office Settled Status Frontend

Web application providing internal HMRC staff with an interface to check customer's settled status and rights to public funds.

## Running the tests

    sbt test it:test

## Running the tests with coverage

    sbt clean coverageOn test it:test coverageReport

## Running the app locally

    sm --start HOSS
    sm --stop HOME_OFFICE_SETTLED_STATUS_FRONTEND 
    sbt run

It should then be listening on port 9386

    browse http://localhost:9386/check-settled-status

### License


This code is open source software licensed under the [Apache 2.0 License]("http://www.apache.org/licenses/LICENSE-2.0.html")
