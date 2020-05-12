# TEST for [jaxws-maven-plugin](https://github.com/eclipse-ee4j/metro-jax-ws)

Compile with
```bash
mvn clean generate-sources -P generate-adapters
```
or (via docker)
```bash
docker run -it --rm --name maven-compiler -v "$PWD:/usr/src/mymaven -w /usr/src/mymaven maven:3.6.3-openjdk-11 mvn clean generate-sources -P generate-adapters
```
