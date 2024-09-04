#### Getting started with MigratoryData Java Client API V6

##### Prerequisites
Java Development Kit (JDK) 8+, Gradle 6+ 

#### Clone Project

Clone the getting started project from GitHub using your IDE of choice or using the following command:
> git clone https://github.com/migratorydata/getting-started-java-client-api.git

#### Start MigratoryData server using docker

If you don’t have a MigratoryData server installed on your machine but there is docker installed you can run the following command 
to start MigratoryData server, otherwise you can download and install the latest version for your os from [here](https://migratorydata.com/downloads/migratorydata-6/]).

```bash
docker pull migratorydata/server:latest
docker run -d --name my_migratorydata -p 8800:8800 migratorydata/server:latest
```

#### Configure
Update the code snippet from the file src/main/java/com/migratorydata/example/Config.java to your needs.

#### Build & Run
Use the following commands to build and run your project:
> ./gradlew clean build

> ./gradlew run

#### Documentation

For more information about the MigratoryData Client API for Java, please refer to the official documentation available at [MigratoryData Documentation](https://migratorydata.com/docs/client-api/java/).
