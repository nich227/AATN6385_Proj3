# CS 6385 - Project 3

## How to run
Note: These instructions assume that you already have Maven and Java 11 installed. If not, please install these first before following these steps.
1.	Create a new folder, with a descriptive name (e.g. ```project-3```) and go into this folder.
2.	Copy the ```pom.xml``` file to the root of this folder.
3.	Create new folders within this folder, with this structure: ```src/main/kotlin/com/cs6385```
4.	Copy the ```HeuristicNetworkTop.kt```, ```Runner.kt```, ```WorstToBestAlg.kt```, ```GeneticAlg.kt``` and ```Coordinate2D.kt``` files to this folder.
5.	Go back to the root project-3 folder and run 
```bash
mvn clean package 
```
in the terminal.
6.	A new target folder should have been created after the build is successful. Go into this target folder and run in the terminal: 
```bash 
java -jar project3-1.0-SNAPSHOT.jar <nValue>
```