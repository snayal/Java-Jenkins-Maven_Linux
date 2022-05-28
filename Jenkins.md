# Jenkins 
***Running Jenkins with Docker***
-
- docker pull jenkins/jenkins:jdk11
- docker run --rm -ti \
-   -p 8080:8080 -p 50000:50000 \
-   -v jenkins-home:/var/jenkins_home \
-   jenkins/jenkins:jdk11

***Running Jenkins with Java***
- 
**Install using the step below**
- sudo wget -O /etc/yum.repos.d/jenkins.repo https://pkg.jenkins.io/redhat-stable/jenkins.repo

- sudo rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io.key
- sudo yum install jenkins
- sudo service jenkins status

**#Start Jenkins**
- Service Jenkins start

***or***
- sudo systemctl start jenkins
- $ sudo systemctl status jenkins

**#Setup Jenkins to start at boot**

- chkconfig Jenkins on
