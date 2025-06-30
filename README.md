Build Spigot versions using [taskfile](https://taskfile.dev/).

Java versions:\
[Debian/Ubuntu](https://docs.azul.com/core/install/debian)\
[Windows/macOS](https://www.azul.com/downloads/#zulu)

On ubuntu, just run `task java-setup` to setup Zulu Java\
Then do `task java-XX` to setup Java. Replace XX withg the version of Java you need. 8, 16, 17 & 21 is preconfigured

MC 1.8 to 12.2: Java 8\
MC 1.13 to 1.13.2: Java 8 or 11\
MC 1.14 to 1.14.4: Java 8 or 12\
MC 1.15 to 1.15.2: Java 8 or 13\
MC 1.16 to 1.16.5: Java 8 or 14\
MC 1.17: Java 16\
MC 1.17.1 to 1.20.5: Java 17\
MC 1.20.5 to latest: Java 21
