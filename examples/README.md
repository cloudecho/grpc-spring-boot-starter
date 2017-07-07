# gRPC spring boot starter Examples

## Local Mode
### If Maven
1. Try the local-grpc-server example first run:

    ````
    cd examples/local-grpc-client/
    mvn spring-boot:run
    ````

2. In a different terminal window run:

    ````
    cd examples/local-grpc-server/
    mvn spring-boot:run
    ````

### If Gradle
1. Try the local-grpc-server example first run:

    ````
    ./gradlew :example:local-grpc-server:bootRun
    ````

2. In a different terminal window run:

    ````
    ./gradlew :example:local-grpc-client:bootRun
    ````
### Finally
visit http://localhost:8080/ can see result.

## Cloud Mode

1. Try the cloud-eureka-server example first run:

    ````
    ./gradlew :example:cloud-eureka-server:bootRun
    ````

2. Try the cloud-zipkin-server example first run:

    ````
    ./gradlew :example:cloud-zipkin-server:bootRun
    ````

3. In a different terminal window run:

    ````
    ./gradlew :example:cloud-grpc-server:bootRun
    ````

4. In a different terminal window run:

    ````
    ./gradlew :example:cloud-grpc-client:bootRun
    ````

visit http://localhost:8080/ can see result.