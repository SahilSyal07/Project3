Description 
========================================
This project takes an input from user and extracts a unique key from input body or request headers to call a third party URL.

Third Party url based on input key "1" and "2" respectively.
Here, Input is variable eg it can be 1,2 etc

http://dummy.restapiexample.com/api/v1/employee/1
http://dummy.restapiexample.com/api/v1/employee/2

Currently in the working code, the value is being extracted from the header. Extra added comments and code in blueprint will help change it to extract the same from Request body too.


### Additional Comments are added in the blueprint ###

========================================
To build this project use

    mvn install

To run the project you can execute the following Maven goal

    mvn camel:run
