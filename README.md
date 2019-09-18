
# Lab: Lambda with Dynamo

## [](https://github.com/codefellows/seattle-java-401d5/tree/master/class-32/lab#overview)Overview

Let's use Lambda to handle database changes in real time!

## [](https://github.com/codefellows/seattle-java-401d5/tree/master/class-32/lab#feature-tasks)Feature Tasks

### [](https://github.com/codefellows/seattle-java-401d5/tree/master/class-32/lab#java-insertupdate-functionality)Java Insert/Update Functionality

-   Create a lambda function, in Java, that can add a record to your Taskmaster table.
-   Run this only in "Test" mode
-   It should receive the same object that your API was handling earlier.
-   Repeat for "PUT" / update functionality
-   Do NOT handle images at this point.
-   You might want to keep this  [warm](https://read.acloud.guru/how-to-keep-your-lambda-functions-warm-9d7e1aa6e2f0)...

### [](https://github.com/codefellows/seattle-java-401d5/tree/master/class-32/lab#javascript-or-python)Javascript or Python

-   Create a lambda function that will handle a  [Dynamo Event](https://docs.aws.amazon.com/lambda/latest/dg/with-ddb.html)
    -   Initial Task: Log out the deltas
    -   Stretch Goal: Update the history!

### [](https://github.com/codefellows/seattle-java-401d5/tree/master/class-32/lab#setup-a-dynamo-trigger)Setup a Dynamo Trigger

-   Configure your DynamoDB Table to invoke your lambda function on database change operations.

## Contributors
* Jackie 
* Matt Stuhring
* Jack Kinne
* Nhu Trinh
* Renee Messick
* Peter Lee
* Jane Hur