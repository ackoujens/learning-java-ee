# learning-java-ee
Study of Java EE (J2EE)

## Covering
- Spring Framework / Spring Webflow / Spring Security / JPA (Hibernate) / JSF 2.0 (PrimeFaces) / Apache Maven 2 / Apache Tomcat / Subversion / Oracle RDBMS / Eclipse IDE
- Java EE Project setup using on Maven tool
- Basic example of Java Servlets & JSP classic concept

## Preperation
Followed this tutorial for TomCat setup on OSX
https://www.youtube.com/watch?v=_NeXuDTlqPw

Configure Tomcat users to be able to access the manager
https://www.mkyong.com/tomcat/tomcat-default-administrator-password/

Install Eclipse for Java EE developers
https://eclipse.org/downloads/

Install SubClipse in Eclipse
http://subclipse.tigris.org/update_1.8.x

Download Maven
https://maven.apache.org/download.cgi

You can use this tutorial if you're on a mac
https://www.youtube.com/watch?v=ghIvOYDs0BM

If running 'mvn --version' results in a failure, most likely you need to set your environment variables properly.
You can check out this link for setting this up
https://www.mkyong.com/java/how-to-set-java_home-environment-variable-on-mac-os-x/

Install m2eclipse in eclipse (Maven integration for eclipse)
http://download.eclipse.org/technology/m2e/releases

Install Spring Tool Suite in eclipse marketplace
https://marketplace.eclipse.org/content/spring-tool-suite-sts-eclipse

Add Apache Runtime Environment
Preferences > (search for server) > Runtime Environment
Add the correct version of your TomCat installation + directory
Select a JRE

Go to Window -> Show View -> Servers
Create a new instance of a TomCat Servers

Carry on to create a dynamic web project
