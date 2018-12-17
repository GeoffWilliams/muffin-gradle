# Java + Gradle project

# Creating

## Library (.jar file)
```
gradle init --type java-library
```

## Application (Executable .jar file)
```
gradle init --type java-application
```

You must also
[define the main class in MANIFEST.mf](https://stackoverflow.com/q/32567167/3441106).

Note that this approach will only work in the simplest of cases


##Building
```
./gradlew build
```

## Running (executable only)

```
java -jar build/libs/muffin-gradle.jar 
```
