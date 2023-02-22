# Run
```
export SPEECH_KEY=YOU_KEY
export SPEECH_REGION=YOU_REGION

 mvn clean dependency:copy-dependencies
javac -cp ".:target/dependency/*" Program.java
java -cp ".:target/dependency/*" Program
```
