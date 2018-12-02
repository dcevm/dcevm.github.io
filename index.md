# DCEVM

This project is a fork of original [DCEVM](http://ssw.jku.at/dcevm/) project. The purpose of the project is to maintain enhanced class redefinition functionality for OpenJDK HotSpot 7/8/9/10/11 and Oracle JVM.

## NEWS Dcevm-11(beta) on Trava OpenJDK

 * [Java 11](https://github.com/TravaOpenJDK/trava-jdk-11-dcevm/releases) with integrated hotswap-agent.jar, including full jdk package.

## Binaries
 * [Java 8 update 181](https://github.com/dcevm/dcevm/releases/download/light-jdk8u181/DCEVM-8u181-installer.jar)
 * [Java 8 update 152](https://github.com/dcevm/dcevm/releases/download/light-jdk8u152/DCEVM-8u152-installer.jar)
 * [Java 7 update 79, build 3](https://github.com/dcevm/dcevm/releases/download/light-jdk7u79%2B3/DCEVM-light-7u79-installer.jar)
 * [All releases](https://github.com/dcevm/dcevm/releases)
 
Old full version (with parent class modification support):
 * [Java 7 update 79, build 8](https://github.com/dcevm/dcevm/releases/download/full-jdk7u79%2B8/DCEVM-full-7u79-installer.jar)
 

The full version supports more features (for example, it supports the removal of superclasses), but it is harder to maintain. Thus, it is supported for fewer versions of OpenJDK. The light version supports fewer features, but it is still more advanced than the default OpenJDK redefinition functionality, and it is easier to keep in sync with the OpenJDK HotSpot.


## Sources

Sources of the patches are available [here](https://github.com/dcevm/dcevm).

## Usage

* Run `java -jar installer.jar`
* Follow the instructions to install DCEVM into existing JDK/JRE
