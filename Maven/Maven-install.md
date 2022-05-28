# Maven Installation in jenkins server
-
go to folder /opt

```sh
cd /opt
ls -altr
```



#go to the link https://maven.apache.org/install.html <br>
#copy link   https://dlcdn.apache.org/maven/maven-3/3.8.5/binaries/apache-maven-3.8.5-bin.tar.gz
```sh
- wget https://dlcdn.apache.org/maven/maven-3/3.8.5/binaries/apache-maven-3.8.5-bin.tar.gz
- tar -xvzf apache-maven-3.8.5-bin.tar.gz
```
#move apache-maven  to Maven folder
```sh
- mv apache-maven-3.8.5 maven
- cd maven/
- pwd
```
#update .bash_profile
```sh
- M2_HOME=/opt/maven
- M2=/opt/maven/bin
- PATH=$PATH:$HOME/bin:$JAVA_HOME:$M2:$M2_HOME

```


