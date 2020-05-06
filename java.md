I've developed Java applications in [IntelliJ CE and Ultimate](https://www.jetbrains.com/idea/download/#section=mac) but I prefer to use Visual Studio Code with the following plugins:
1. 
1.
1. 

VS Code (more accurately Eclipse) is [moving to require Java 11](https://github.com/redhat-developer/vscode-java/wiki/JDK-Requirements#jdk11.requirement) which prompted the following configs:

Also make sure to configure Code's settings with additional JDKs downloaded from [here](https://adoptopenjdk.net/?variant=openjdk11&jvmVariant=hotspot), I'm currently running Java 1.8, 11 and 14 JVMs.

When setting your VS Code settings.json file, you can find the path to your various JDK locations with `$ /usr/libexec/java_home -v 1.8` for version 8 or by substituting 1.8 with 11 or 14 for other versions.
