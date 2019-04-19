#### Project created by command from command line:

```text
mvn archetype:generate -DarchetypeArtifactId=jersey-quickstart-grizzly2 -DarchetypeGroupId=org.glassfish.jersey.archetypes -DinteractiveMode=false -DgroupId=com.dekses -DartifactId=jersey-docker-demo -Dpackage=com.dekses.jersey.docker.demo -DarchetypeVersion=2.22.2
```

#### Next commands for run it

```text
cd jersey-docker-demo

mvn install

mvn exec:java
```

#### Query to verify if everything's OK

```text
curl http://localhost:8080/myapp/myresource
```

