# sample-springboot-gradle-application
This is ample spring boot application with gradle using corporate/company proxy

# build.properties
global location's build.properties file is where optimum way to define proxy and any custom gradle variables

# to run this application
in CMD execute below for the first time to install dependencies 

```bash
gradlew bootRun
```

for the next executions use must below, as the dependencies are already downloaded no need to download again and again and it slows down the execution
```bash
gradlew bootRun --offline
```

If any changes the build.gradle file (add/remove dependecies or its version) force gradle to download the dependecies again using below CMD

```bash
gradlew bootRun --refresh-dependencies
```

To build war at last
```bash
gradlew war --offline
```

To clean gradle (clean build)
```bash
gradlew clean
```
