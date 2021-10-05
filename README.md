# Basic Gatling simulation
A basic gatling test using gradle and scala, based on the [gatling-gradle-plugin-demo](https://github.com/gatling/gatling-gradle-plugin-demo) repository.
Contains:
- Basic build.gradle config
- Basic sample of a simulation with a friendly structure

## Use sample project
- Verify that you have git installed on your pc
- Verify that you have Java installed on your pc, also
  you already setup the following environment variables: $PATH and $JAVA_HOME
- Clone the repository:
```shellscript
git clone https://github.com/eataborda/basic-gatling.git
```
- Move to the cloned repository

## Run simulation
There are two ways to run the simulations depending on the amount you want to run, Go to the root of the repository and execute the following command:
- Run all simulations:
```shellscript
./gradlew gatlingRun
```
- Run a specific simulation:
```shellscript
./gradlew gatlingRun-com.github.eataborda.gatling.BasicSimulation
```
To run a specific simulation class y necessary to identify:

The package that contains the simulation class: *com.github.eataborda.gatling*

The name of the simulation class: *BasicSimulation*