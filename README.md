General-Purpose-Ant-Scripts
===========================

"General Purpose Ant Scripts" is a collection of ant scripts and ant scripts templates that organises the project system.

delivery.xml
------------

Script to deliver and execute shell comands on a ssh host. 
On Debian-7 you also need to install special jar files:

```bash
mkdir -p /var/lib/jenkins/.ant/lib
wget -o /var/lib/jenkins/.ant/lib/jsch-0.1.51.jar http://central.maven.org/maven2/com/jcraft/jsch/0.1.51/jsch-0.1.51.jar
wget -o /var/lib/jenkins/.ant/lib/ant-jsch-1.9.4.jar http://central.maven.org/maven2/org/apache/ant/ant-jsch/1.9.4/ant-jsch-1.9.4.jar
```

