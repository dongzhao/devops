# Docker local dev-ops setup
## Prerequisites 
Install Docker from 
## Install Jenkins
Type in command below to start installing and running Jenkins docker image

`c:\Users\donz\docker run -p 8080:8080 -p 50000:50000 -v jenkins_home:/var/jenkins_home jenkins/jenkins:lts-jdk11`

On the first time booting of Jenkins during installation, copy and paste the initial admin password from docker installation log on the command window as below:

`Please use the following password to proceed to installation: `

`4fd517ecd5de409a8d90a4791ad8b707`

And then Open http://localhost:8080, enter the admin password to continue the Jenkins setting untill it's completed.
