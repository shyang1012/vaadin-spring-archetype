# Introduction #

To create a new project using this archetype you should follow the steps showing in next section.


# Generate a new project #

  * Open a new terminal and go to the folder where you want to create the new project.

  * Generate the project by typing:

```
mvn archetype:generate                              \
  -DarchetypeGroupId=com.vaadin                     \
  -DarchetypeArtifactId=vaadin-spring-archetype     \
  -DarchetypeVersion=1.2.1-SNAPSHOT                 \
  -DgroupId=com.mycompany                           \
  -DartifactId=myApplication                        \
  -Dversion=0.1-SNAPSHOT
```

  * To start working with the recently created project go to _myApplication_ folder in a terminal and type:

```
mvn clean install
```

  * If you want test the app without enter any line of code you should type:

```
mvn clean install tomcat:run
```

  * Go to [http://localhost:8080/myApplication](http://localhost:8080/myApplication) and you see a white page with **Hello World!** Label.