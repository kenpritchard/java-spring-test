# java-spring-test
Test that you can clone a project thru a f/w, build it using both gradle and maven, and run it. If this works, everything else should work.




### Clone and Build
1. `git clone https://github.com/kenpritchard/java-spring-test`
2. `cd java-spring-test`
3. `./gradlew build` (Build with gradle)
4. `mvn package` (Build with maven)

### Run Gradle Build
1. `java -jar build/libs/java-spring-gradle-test-0.1.0.jar`
2. Open http://localhost:8080/ in your browser to verify
3. Use ctrl-c in the terminal to stop the application

### Run Maven Build
1. `java -jar build/libs/java-spring-maven-test-0.1.0.jar`
2. Open http://localhost:8080/ in your browser to verify
3. Use ctrl-c in the terminal to stop the application
