# Lab Exercises 2021
[![Build Status](https://travis-ci.com/nikiboura/Lab_exercises_2021.svg?token=ki4LJ9spppXtZBbs1sCm&branch=development)](https://travis-ci.com/nikiboura/Lab_exercises_2021)

## Overview
The purpose of this repository is to include some Lab exercises in Java, for the needs of the lab tutorials of the Software Engineering in Practice course in order to get familiar with Software Engineering Tools!
It uses **Maven** to automate the build process of the two modules, **JUnit** for testing services, **TravisCI** for continuous integration services , **Jacoco** for Code Coverage services.

## <a name="Lab Exercises"></a>Lab Exercises
* [Maven Lab assignment](#maven-lab-assignment)
* [Unit Testing Lab assignment](https://github.com/nikiboura/Lab_exercises_2021/blob/development/unittesting/README.md)
* [Design Patterns Lab assignment](https://github.com/nikiboura/Lab_exercises_2021/tree/development/sourcecodeanalyze)

 
<img align="left" width="40" height="40" src="media/maven.png">

## <a name="maven-lab-assignment"></a> Maven Lab assignment

**Java application using Maven that generates a histogram.**

The purpose of this project is to create a Java application using the Maven build-automation tool that reads a file with students’ grades from the command line, and generates its histogram .

The goal of this project is to:

Get familiar with Maven build-automation tool

-Present the structure of a multi-module Maven project

-Get familiar with a the JFreeChart Library

## Technologies and tools used and required to build the project

The project was build in Eclipse using the Maven Plugin in Eclipse
In order to do this you should have installed Maven Plugin in Eclipse

Here is how you can do it: [How to download Maven in Eclipse](https://hiplab.mc.vanderbilt.edu/projects/soempi/eclipse_m2e_install.html)

In order to build the project you also need to intall Maven.

Here is how you can do it(on Windows): [How to install Maven on Windows](https://mkyong.com/maven/how-to-install-maven-in-windows/)


## Build Project

After you install the Maven on Windows follow the steps below to build and run the Maven Project:

1.Clone this repository with the git clone command

2.Run the following command in the repository root directory to build the modules

	mvn package

3.The jar is located in the target directory and can be executed as following:

	java -jar gradeshistogram/target/gradeshistogram-0.0.1-SNAPSHOT-jar-with-dependencies.jar grades.txt

(the grades.txt is the file that contains the student's grades and it is given from the command line)







