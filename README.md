### Prerequisites

* graalvm-native
* gcc, zlib-devel, glibc-devel

### Build and run

````sh
mvn package -Pnative && target/getting-started-1.0-SNAPSHOT-runner
````

### Try it out

````sh
curl localhost:8080/hello/greeting/baka
````

### Readings

* https://quarkus.io/guides/building-native-image-guide
* https://github.com/quarkusio/quarkus-quickstarts/

