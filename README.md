# Docker-Tomcat-User-Xml
Dockerfile and User xml config for 8-jre-alpine

Sample docker file for fast deploy tomcat. Default tomcat Dockerfile doesn't create a user.

How to Use:<br>
   --Clone this project which contains a Dockerfile and tomcat-users.xml file.<br>
   -- edit the username and password in `tomcat-users.xml` file.<br>
   -- create folder `/usr/local/tomcat` if doesn't exits.<br>
   -- now build image with this Dockerfile and you are ready to rock.<br>
If you are using cloud hosting like AWS or Digital Oscean don't forget to enable ports on firewall for incoming and outgoing traffic.
