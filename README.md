# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

 Ruby version - ruby 3.0.3p157 (2021-11-24 revision 3fb7d2cadc) [x86_64-darwin21]

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...



Rails Useful Commands:

* `rails generate scaffold NAME-OF-ROUTE COL-IN-DB: TYPE-OF-COL COL-IN-DB: TYPE-OF-COL`
    * This command creates the relevent files and config to CRUD Route
    * After run the `scaffold` commend, you need to make a migration between the modle and the DB table.
        * For clarify things, will see in the `scaffold` output, under `active_record` -> `create db/migrate/   RANDOM-NUMBER_create_NAME-OF-ROUTE.rb`, there is the ruby code that we will use in the next commend.
            * `rails db:migrate`
            * Done!
* `rails generate controller NAME-OF-CONTROLLER`
    * This commend will generate a new controller files
* `rails routes --expanded` 
    * This commend will give us the list of all the routes generated in you application

