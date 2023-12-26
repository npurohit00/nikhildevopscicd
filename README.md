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


Step 2 - A unit test was then conducted with Maven. Subsequently, code analysis was performed with SonarQube, and the artifacts were uploaded to the Nexus repository. 


![Screenshot (5)](https://github.com/npurohit00/nikhildevopscicd/assets/57475931/26757d39-b8a9-4ceb-9958-7213b87ebbee)


![Screenshot (8)](https://github.com/npurohit00/nikhildevopscicd/assets/57475931/00f7533f-4fa7-4d11-9866-1c2247bb47e9)


Step 3 - Additionally, we set up a Slack notification to keep the team informed.

![Screenshot (6)](https://github.com/npurohit00/nikhildevopscicd/assets/57475931/f407c9b7-1b04-41b1-bb17-e41fe85b0faf)



