## Software Development Methods ##

This repository includes assignments of *Software Development Methods* course at University of Helsinki, plus a small Java application.
The repository is for study purpose only.

Progress of the application is being tracked in [spent hours](https://github.com/solasuo/SoftwareDevelopmentMethods/blob/main/Documentation/hours.md).
Preliminary structure of the application: [Architecture](https://github.com/solasuo/SoftwareDevelopmentMethods/blob/main/Documentation/architecture.md) 

##Bloodecode application##

Blood test results can be complicated to interpret. With Bloodecode application users can "decode" the meaning of most common blood test abbreviations
(note: these may vary by country, the application currently interprets abbreviations used in Finland). A user can also search for reasons for abnormally
high or low values in blood test results.

A user can monitor their critical values by adding notes to selfmonitor database.

### Terminal commands ###

Run the program
```
mvn spring-boot:run
```
Run tests
```
mvn test
```
Generate test coverage report
```
mvn jacoco:report
```
Generate jar
```
mvn package
```
Run jar 
```
java -jar Bloodecode.jar
```
Generate Checkstyle report
```
mvn jxr:jxr checkstyle:checkstyle
```
