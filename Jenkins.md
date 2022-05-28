***Running Jenkins with Docker***
- docker pull jenkins/jenkins:jdk11
- docker run --rm -ti \
-   -p 8080:8080 -p 50000:50000 \
-   -v jenkins-home:/var/jenkins_home \
-   jenkins/jenkins:jdk11

***Running Jenkins with Java***
- 
