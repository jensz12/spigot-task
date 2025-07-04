Build Spigot versions using [taskfile](https://taskfile.dev/).

# Usage

- `build-latest` will build the latest stable version.
- `build-specific` takes an argument of `-- MC Version`and then builds a specific version of Minecraft.
- `setup` Downloads the latest version of BuildTools

# Java stuff

Uses Azuls Zulu JDK for Java.\
[Windows downloads can be found here](https://www.azul.com/downloads/?os=windows&package=jdk#zulu)

## Usage on Debian based systems

- `java` takes an argument using `-- java version`. Uninstalls all prior Zulu java versions, and then installs the version provided.
- `java-setup` Adds the Zulu Java deb repo, and makes it avalible for apt.

## Java versions

Minecraft needs the following Java versions

- 1.8 to 12.2: Java 8
- 1.13 to 1.13.2: Java 8 or 11
- 1.14 to 1.14.4: Java 8 or 12
- 1.15 to 1.15.2: Java 8 or 13
- 1.16 to 1.16.5: Java 8 or 14
- 1.17: Java 16
- 1.17.1 to 1.20.5: Java 17
- 1.20.5 to latest: Java 21

# Spigot MC Versions

A list of all versions supported by Spigot

## 1.21

- 1.21.7
- 1.21.6
- 1.21.5
- 1.21.4
- 1.21.3
- 1.21.1

## 1.20

- 1.20.6
- 1.20.4
- 1.20.2
- 1.20.1

## 1.19

- 1.19.2
- 1.19.2
- 1.19.2
- 1.19.1
- 1.19

## 1.18

- 1.18.2
- 1.18.1
- 1.18

## 1.17

- 1.17.1
- 1.17

## 1.16

- 1.16.5
- 1.16.4
- 1.16.3
- 1.16.2
- 1.16.1

# 1.15

- 1.15.2
- 1.15

## 1.14

- 1.14.4
- 1.14.3
- 1.14.2
- 1.14.1
- 1.14

## 1.13

- 1.13.2
- 1.13.1
- 1.13

## 1.12

- 1.12.2
- 1.12.1
- 1.12

## 1.11

- 1.11.2
- 1.11.1
- 1.11

## 1.10

- 1.10.2

## 1.9

- 1.9.4
- 1.9.2
- 1.9

## 1.8

- 1.8.8
- 1.8.3
- 1.8
