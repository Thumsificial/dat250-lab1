# DAT250 Lab 1

## Installation
### Java
Java was already installed, however I wanted to try the installation using SDKman,
so I used it to download an updated version with no problems.

### IDE
Intellij was already installed.

### Gradle
Gradle was installed with no problems.

### Git
Git was already installed.

### Containers
Podman was installed with no problems.

## Exercise
### Source code versioning
Repo created without any problems.

### Build System
Building went fine, and was tested with the commands:
```
./gradlew check
./gradlew build
./gradlew run
```

### Fix compilation errors
The compilation errors were fixed by adding the dependency. However,
the problem still persists in the IDE, but are fixed when running it from the terminal.

### Quality Assurance
Refactoring was done, and tests were added, which ran with no problems. Tests were generated using the code with chatGPT.
And ran without any issues.

### Package Application
Using podman was a bit confusing, and I had some issues at the start with building the image,
because I did not start the machine, only created it. I was also a bit confused about the dockerfile,
but after getting told it was just a file with the name `Dickerfile`, everything went smoothly.

### DockerHub
The following container includes the image of the converter application:

[Container](https://hub.docker.com/r/thomasuls/dat250lab1)