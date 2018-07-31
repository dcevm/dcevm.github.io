# DCEVM

This project is a fork of original [DCEVM](http://ssw.jku.at/dcevm/) project. The purpose of the project is to maintain enhanced class redefinition functionality for OpenJDK HotSpot 7/8 and Oracle JVM.

## Binaries


Light:
 * [Java 7 update 79, build 3](https://github.com/dcevm/dcevm/releases/download/light-jdk7u79%2B3/DCEVM-light-7u79-installer.jar)
 * [Java 8 update 152](https://github.com/dcevm/dcevm/releases/download/light-jdk8u152/DCEVM-8u152-installer.jar)
 * [Java 8 update 181](https://github.com/dcevm/dcevm/releases/download/light-jdk8u181/DCEVM-8u181-installer.jar)
 * [All releases](https://github.com/dcevm/dcevm/releases)
 
Full:
 * [Java 7 update 79, build 8](https://github.com/dcevm/dcevm/releases/download/full-jdk7u79%2B8/DCEVM-full-7u79-installer.jar)
 
Java9
 * [Java 9](https://github.com/HotswapProjects/openjdk-jdk9/releases)
 
Full version supports more features (for example, it supports removal of superclasses), but is harder to maintain. Thus, it is only supported for fewer versions of OpenJDK. Light version supports less features (still, it is pretty advanced compared to OpenJDK out-of-the box redefinition functionality), but is easier to keep up with the OpenJDK HotSpot.

## Sources

Sources of the patches are available [here](https://github.com/dcevm/dcevm).

### Java9

Sources for dcevm9 are available [here](https://github.com/HotswapProjects/openjdk-jdk9/tree/dcevm)

## Usage

* Run `java -jar installer.jar`
* Follow the instructions to install DCEVM into existing JDK/JRE
