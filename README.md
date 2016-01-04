# Example multistep form with backbone.js

Just having fun making a multistep form with backbone. This example is made in Rails with a Mongodb, Coffeescript and Sass. It saves the temporary form data in HTML5 Web Storage. The form works with client validations and server validations.

## Installation

    # install mongodb
    brew install mongodb

    # install gems
    bundle

    # Run mongod service just in case it didn't start
    sudo mongod 

    # starting rails server
    rails s

    # View in broswer
    127.0.0.1:3000

## Todo

* Support for multi model forms.
* Inline field error messages.