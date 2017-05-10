# Scala-sbt

Simple container which will download and install "Scala" and it's build tool "sbt" on top of the base openjdk-8 image (which runs on debian)

## Environmental variables

| Identifier | Purpose |
|--------|--------|
|SCALA_VERSION | The version of scala you want to run.|
|SBT_URL | The URL from where to download SBT.|

## Installation and usage
you can run the docker using the following command:
`docker run --name scala-sbt mastermindzh/scala-sbt`
