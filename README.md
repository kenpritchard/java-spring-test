# java-spring-test
Test that you can clone a project thru a f/w, build it using both gradle and maven, and run it. If this works, everything else should work.


### Prerequisites
1. Execute `javac -version` to make sure the JDK is installed, if not install it
2. Ensure the $JAVA_HOME environment variable is set
3. Install ant: https://ant.apache.org/
4. Install maven: https://maven.apache.org/
5. Install gradle: https://gradle.org/
6. Install the Sprint Tool Suite: https://spring.io/tools

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
1. `java -jar target/java-spring-maven-test-0.1.0.jar`
2. Open http://localhost:8080/ in your browser to verify
3. Use ctrl-c in the terminal to stop the application
