# FuncUnit.MVC
============
This is a nuget package that adds an ASP.Net MVC 4 Area (FunctionalTests) to an existing ASP.Net MVC application. 
The area includes a RunnerController that will run FuncUnit tests.

To Add new Functional Tests to your applicaiton add new Controllers to the Area, include the Index action and view to render the html that needs to be tested.
Include a Test.cshtml to include the script block that includes FuncUnit Tests. This code will be called by the runner to execute the tests.

A basic Allways Pass test is included to demonstrate all the files needed for new tests and to make sure all the files FuncUnit needs are wired up correctly.

## Usage

Once the package in installed, navigate in a browser to /FunctionalTests/Runner to run all tests.

## Install
    install-package FuncUnit.MVC4


Brought to you by Eric Hexter http://LosTechies.com/erichexter

