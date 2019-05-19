# Simple-Spring-Boot-Application
Hi Friends!
I hope this simple application helps you to understand about spring boot
The below points helps you to import and run locally in your system.

1. Please download the project in your system
2. Import the project in Eclipse IDE by File->Import->Maven->Existing Maven Project->Browse this project->Click Finish.
3. Go to the project location and open command prompt there and give "mvn clean install" which will download the dependencies
listed in pom.xml
4. I have explicitly had set the port number 9090 in application.properties as "server.port=9090"
and removed white label error page after launching this application.
5. I have included index.html as a static html page inside "resources/static/index.html" so that whenever we boot this application,
in the browser on giving "localhost:9090" it will render the static index.html 
6. That's it you are ready to start/boot this application by giving either an command "mvn spring-boot:run" in command prompt
or just clicking Run as -> Java Application.
