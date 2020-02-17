# BatchJob

## Usage
Pass desired execution time in seconds as a parameter to the JAR file.
Script will convert to milliseconds and run the dummyMethod in a loop until the timeout.

Default execution time is 60 seconds if no parameter is passed.
```
java -jar BatchJob.jar    // Run for 60 seconds
java -jar BatchJob.jar 30 // Run for 30 seconds
java -jar BatchJob.jar 15 // Run for 15 seconds
```
