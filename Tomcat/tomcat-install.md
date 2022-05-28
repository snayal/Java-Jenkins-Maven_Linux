# Tomcat installation on EC2 Linux
-
**Prerquist softwares**
1. java

#Downloading apche tomcat from web
```sh
cd /opt
wget https://downloads.apache.org/tomcat/tomcat-9/v9.0.63/bin/apache-tomcat-9.0.63.tar.gz.sha512
tar -xvzf /opt/apache-tomcat-9.0.63.tar.gz.sha512
```
#Start the tomcat service
```sh
cd /opt

chmod +x /opt/apache-tomcat-<version>/bin/startup.sh 
chmod +x /opt/apache-tomcat-<version>/bin/shutdown.sh
```

