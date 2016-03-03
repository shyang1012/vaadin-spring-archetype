# Introduction #

To use the archetype you should Download the last stable version (right now SNAPSHOT version) from the [Download Page](http://code.google.com/p/vaadin-spring-archetype/downloads/list).

In future I hope this artifact will be deployed on a maven repository and anyone can use it without this previous step.

# Installation #

After you [download](http://code.google.com/p/vaadin-spring-archetype/downloads/list) the file you should open a new Terminal window and type in it:

```
mvn install:install-file                              \
   -Dfile=vaadin-spring-archetype-1.2.1-SNAPSHOT.jar  \
   -DgroupId=com.vaadin                               \
   -DartifactId=vaadin-spring-archetype               \
   -Dversion=1.2.1-SNAPSHOT                           \
   -Dpackaging=jar                                    \
   -DgeneratePom=true
```

This maven command shows the following output:

```

[INFO] Scanning for projects...
[INFO]                                                                         
[INFO] ------------------------------------------------------------------------
[INFO] Building Maven Stub Project (No POM) 1
[INFO] ------------------------------------------------------------------------
[INFO] 
[INFO] --- maven-install-plugin:2.3.1:install-file (default-cli) @ standalone-pom ---
[INFO] Installing /Users/.../vaadin-spring-archetype-1.1-SNAPSHOT.jar to /Users/.../.m2/repository/com/vaadin/vaadin-spring-archetype/1.2.1-SNAPSHOT/vaadin-spring-archetype-1.2.1-SNAPSHOT.jar
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time: 1.758s
[INFO] Finished at: Thu May 12 08:25:53 CEST 2011
[INFO] Final Memory: 3M/81M
[INFO] ------------------------------------------------------------------------

```

If the output is like the shown above, the artifact is just installed in your local repository and you can continue with the steps shown at [create a project](CreateAProject.md).