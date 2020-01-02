## Jacklyn Codebase Starter - Web Application Resource (WAR)
This starter provides a project template for building applications using Jacklyn Codebase that will be deployed on any standard Java web server. Suitable web servers must run on Java 6 at minimum and must support at least Servlet 3.0.

Uses in-memory HSQLDB as application database and utilizes port 7081 for command interface by default. You can change database and port settings in ...\WEB-INF\conf\unify.xml.

## Build the Project

```
mvn clean package
```
 
### Quick Run
* Download an already assembled deployable package [here](https://github.com/tcdng/jacklyn-app-war/releases/download/1.1.0/jacklyn.war).
* Deploy downloaded WAR file into suitable web server.
* Open a browser and enter `http://localhost:[Port Number]/jacklyn` into the address bar.
* Login with login ID 'SYSTEM' and password 'system'.