# Docker-Tomcat-User-Xml
Dockerfile and User xml config for 8-jre-alpine

Sample docker file for fast deploy tomcat. Default tomcat Dockerfile doesn't create a user.

How to Use:
   --Clone this project which contains a Dockerfile and tomcat-users.xml file.
   -- edit the username and password in `tomcat-users.xml` file.
   -- create folder `/usr/local/tomcat` if doesn't exits.
   -- now build image with this Dockerfile and you are ready to rock.
If you are using cloud hosting like AWS or Digital Oscean don't forget to enable ports on firewall for incoming and outgoing traffic.
