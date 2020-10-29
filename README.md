# angular7-sonarqube

# Required
Angualr-cli : 7.3.7
Sonarqube server is required, download from
https://binaries.sonarsource.com/CommercialDistribution/sonarqube-developer/sonarqube-developer-7.9.4.zip
Java 11 required, download from 
https://download.oracle.com/otn/java/jdk/11.0.9+7/eec35ebefb3f4133bd045b891f05db94/jdk-11.0.9_windows-x64_bin.exe?AuthParam=1603933716_253fe30935da4bcd785567d1afca6c6a

After downloading java 11 set location of java under wrapper.conf of sonar (C:\sonarqube-7.9.4\conf)
wrapper.java.command=C:\Program Files\Java\jdk-11.0.9\bin\java


## Test sonar scanner
### sonar with debug mode
yarn run sonar -X 

## Sonar report

you can see full report using localhost:9000, which is configured in sonar-project.propeties file.