# Tomcat installation on EC2 Linux
-
**Prerquist softwares**
1. java

#Downloading apche tomcat from web
```sh
- cd /opt
- wget https://downloads.apache.org/tomcat/tomcat-9/v9.0.63/bin/apache-tomcat-9.0.63.tar.gz
- tar -xvzf /opt/apache-tomcat-9.0.63.tar.gz
- mv apache-tomcat-9.0.63 tomcat
- cd tomcat/
```
#Start the tomcat service
```sh
- cd /opt/bin/
-  ./startup.sh
 ```
 
 #Access tomcat from web
```sh
- <ec2 public ip>:8080
- click app manager button

```
#for App manager access, modify context.xml
#Find context.xml location
```sh

- find / -name context.xml 
 
 --
  /opt/tomcat/webapps/examples/META-INF/context.xml
  /opt/tomcat/webapps/host-manager/META-INF/context.xml
  /opt/tomcat/webapps/manager/META-INF/context.xml
--
```
#modify context.xml
```sh



