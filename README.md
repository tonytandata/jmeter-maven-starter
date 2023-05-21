# jmeter-maven-starter
A starter JMeter project in Maven

## Folder structure
As documented in: https://cwiki.apache.org/confluence/display/JMETER/JMeterMavenPlugin
<br>Create the directory **src/test/jmeter** which is where you would place all your load tests

## Starting the GUI
To start the JMeter GUI:
<br>First you would need to run: `mvn clean verify`
<br>Then: `mvn jmeter:configure jmeter:gui`
<br>Note: Its been recommended to not run official load tests in the GUI itself.