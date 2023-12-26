# nikhildevopscicd
# Prerequisites
#
- AWS Account
- Github
- JDK 11 
- Maven 3
- Ec2 instances (Jenkin sever, Nexus server, and sonar server) 
  
Step 1 - Initially, we retrieved the code from GitHub and created a pipeline using Jenkins to build it using Maven. 


![jenkins flow](https://github.com/npurohit00/nikhildevopscicd/assets/57475931/4a9e7296-0876-457a-bdd6-db23dfc77315)


A unit test was then conducted with Maven. Subsequently, code analysis was performed with SonarQube, and the artifacts were uploaded to the Nexus repository. Additionally, we set up a Slack notification to keep the team informed.

